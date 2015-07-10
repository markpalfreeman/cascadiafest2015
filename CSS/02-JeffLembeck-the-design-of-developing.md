# The Design of Developing
## Jeff Lembeck ([jefflembeck](http://twitter.com/jefflembeck))

**Slides**: ___________

*The Family Meal* (Ferian Adria) cookbook is a guideline for how we should make software.

Make something accessible, good for the community, making lives simpler.

**Grunticon** started as a weekend project, and began getting used by the public. Issues and pull requests started pouring in, and they needed a strategy to handle change and growth.

**Tests** -> Refactor

### Postel's Law, 1981:
> Be conservative in what you do, be liberal about what you accept from others.

### Favorite Patterns
- **Filter Pattern**: take standard in, return standard out
  - Ex: gulp pipe()
- **Cantrip Pattern**: no standard in, no standard out
  - Ex: rm, touch, mkdir
- **Source Pattern**: no standard in, return standard out
- **Compiler Pattern**: like filter pattern, but reads and writes files by itself

"What kind of tool do you want users to interact with?"
-> Ease of use, less cognitive overhead

"Write programs that do one thing, and do it well. Write programs that work together."

Grunticon now makes use of small, single-use programs. Testable! Simple!

### Lessons learned
- Make user experience something you take pride in
- Let public know they're heard
- Make contribution guidelines and code of conduct
- Find all the empathy you can muster and utilize it

> You'd be surprised how well humans respond to trust.

> What matters is that you think about people when you make things.

