# Death to Cookies, Long Live JSON Web Tokens
## Martin Gontovnikas ([mgonto](http://twitter.com/mgonto))

**Slides**: 


Previously JS developer, now Developer Advocate

Auth0 - authentication

Browser <--> Server

- Session begins, known by server
- User is authenticated on server within session, and ID passed back to browser via cookies.

Cookies used to work well, but now we're doing more in the browser and less on the server.

- Cookies don't play well w/ CORS ()
- Cookies require stateful servers. (session = state!)

Stateless = given x request, always give y response (no side effects)

HTTP is stateless protocol. Adding cookies is actually a hack on top of HTTP.
APIs should be stateless!

If I'm doing an authenticated request, I want that request to flow from client to server, from server to server. (These days, we use many servers)

## Better Approach = JSON Web Tokens!

- Now server doesn't have to save user in memory
- JSON Web Token has secret that only the server knows
- Server checks if Token was created by -> then get userID from payload, and do a lookup in DB
- 
- A state of being 'logged in' does not exist. It just means a JWT is saved in localStorage. In order to log out, just delete the JWT from localStorage.

auze.ro/cascadia-jwt