# Efficient Web Type, c. 1556
## Kenneth Ormandy ([kennethormandy](http://twitter.com/kennethormandy))

**Slides**: ___________

Typography began in steel.

Haultin:
- Printer
- Publisher
- Punchcutter
- Protestant
-> Designing the Bible, 100 years after Gutenberg

Created the first French pocket Bible due to Typography decisions and ease of reading.

### Web Typography:

**normalize-opentype.css**: standardize font settings and remove "sub-settings" of other font generators which exclude certain ligatures

- **WOFF2**: Brotli compression (reduces file size)
- Really don't need to worry about anything except WOFF anymore
- Google actually has a CLI for font conversion... otherwise Font Squirrel
- Maybe use JS script imports instead of CSS links

**Tool: TypeKit WebFont Loader (or Observer)** - async loading!

"FOUT" = Flash of Unstyled Text
