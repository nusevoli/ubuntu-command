
## custom resolution virtial half 4k
```
#cvt  1900 1890 24
xrandr --newmode "1904x1890_24.00"  114.00  1904 2000 2192 2480  1890 1893 1903 1919 -hsync +vsync
xrandr --addmode Virtual1 "1904x1890_24.00"

xrandr --output Virtual1 --mode "1904x1890_24.00"
```

## 4k
```
xrandr --newmode "3800x1890_24.00"  227.75  3800 3984 4376 4952  1890 1893 1903 1919 -hsync +vsync
xrandr --addmode Virtual1 "3800x1890_24.00"
xrandr --output Virtual1 --mode "3800x1890_24.00"
```
