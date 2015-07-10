# Responsive Color
## Clarissa Peterson ([clarissa](http://twitter.com/clarissa))

**Slides**: [slideshare.net/clarissapeterson/colorincss](http://www.slideshare.net/clarissapeterson/colorincss)

**Technicolor**: original way to add color to motion pictures

**Web**: CSS, began with 256 "web-safe" colors

### Color Basics
**Hue**: colors (blue, green)
**Value**: light/darkness (how much white or black is added)
**Saturation**: color intensity (how much gray is added)

Now: 256^3 (R,G,B) = 16.8 million possible colors on screens!

### Color Problems
- **Color Blindness**: 1 in 20 people!
  - We can't *rely* on color to convey meaning

### Color Differences
- Men vs. women
- Languages (some African countries call red & orange the same name)
- Screen calibration/settings
- Light (natural vs. fluorescent)

### Testing
- Test in various lights
- Higher contrast on smaller screens?
- Test a printed version (people still do this)

CSS4 -> @media(light-level: dim) {}

CSS blending -> **background-blend-mode**

> We know with responsive design to adapt layout to different devices... why aren't we doing the same with color?
