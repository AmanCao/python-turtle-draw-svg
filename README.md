# python-turtle-draw-svg


[![GitHub issues](https://img.shields.io/github/issues/tfx2001/python-turtle-draw-svg.svg?style=flat-square)](https://github.com/tfx2001/python-turtle-draw-svg/issues)
[![GitHub forks](https://img.shields.io/github/forks/tfx2001/python-turtle-draw-svg.svg?style=flat-square)](https://github.com/tfx2001/python-turtle-draw-svg/network)
[![GitHub stars](https://img.shields.io/github/stars/tfx2001/python-turtle-draw-svg.svg?style=flat-square)](https://github.com/tfx2001/python-turtle-draw-svg/stargazers)
[![GitHub license](https://img.shields.io/github/license/tfx2001/python-turtle-draw-svg.svg?style=flat-square)](https://github.com/tfx2001/python-turtle-draw-svg/blob/master/LICENSE)




可以把位图转化为svg然后使用turtle库画出来。

# Usage

```
usage: main.py [-h] [-c COLOR] filename

Convert an bitmap to SVG and use turtle libray to draw it.

positional arguments:
  filename              The file(*.jpg, *.png, *.bmp) name of the file you
                        want to convert.

optional arguments:
  -h, --help            show this help message and exit
  -c COLOR, --color COLOR
                        How many colors you want to draw.(If the number is too
                        large that the program may be very slow.)
```

# Dependents

See `requirements.txt` .

# Reference

1. [potrace.exe](http://potrace.sourceforge.net/)
2. [Python123](https://www.python123.io/index/turtle_drawing/5a006e85283c653c6d3219d8)
3. [深度掌握SVG路径path的贝塞尔曲线指令](https://www.zhangxinxu.com/wordpress/2014/06/deep-understand-svg-path-bezier-curves-command/)

# License

The GNU GPLv3 License.

Copyright (c) 2018 tfx2001
