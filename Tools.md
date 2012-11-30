### convert eps to svg
* convert eps to pdf
  * `ps2pdf in.eps out.pdf`
* convert pdf to svg
  * `inkscape out.pdf --export-plain-svg=out.svg`

### concatenating multiple svg files
* [https://github.com/astraw/svg_stack](svg_stack)
    * `svg_stack.py --direction=h --margin=100 *.svg > combined.svg`
    * only works with svg 2000 header

### convert svg files to uniform format
* librsvg2-bin debian/ubuntu package
    * `rsvg-convert in.svt -f svg -o out.svg`
