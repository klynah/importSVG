importSVG
=========

uses [simple_svg_parser](https://github.com/evanw/simple_svg_parser)

<!-- example SVGs from [FlatIcon’s Landscapes collection](https://www.flaticon.com/packs/landscapes-collection) -->

### svg2drawbot

```python
svg = SVGImage('tests2/desert.svg')
size(svg.width, svg.height)
svg.draw()
```

### svg2robofont

```python
g = CurrentGlyph()
g.clear()
svgPen = SVGPen('tests2/desert.svg', g.getPen())
```
