# MDPlant

学习如何使用MDPlant

* [list](#list)
* [indent](#indent)
* [menu](#menu)
* [粘贴图片](#粘贴图片)
* [table](#table)

## list

```
vscode Plugin https://github.com/ZengjfOS/MDPlant
HowDocs https://github.com/LowLevelOfLogic/HowDocs

docs/images/0003_green_image.png
docs/images/0003_red_image.png

docs/refers/0003_green_image.tar.bz2
docs/refers/0003_red_image.tar.bz2
```

* [vscode Plugin](https://github.com/ZengjfOS/MDPlant)
* [HowDocs](https://github.com/LowLevelOfLogic/HowDocs)

![0003_green_image.png](images/0003_green_image.png)

![0003_red_image.png](images/0003_red_image.png)

* [0003_green_image.tar.bz2](refers/0003_green_image.tar.bz2)
* [0003_red_image.tar.bz2](refers/0003_red_image.tar.bz2)

## indent

from

```
* title
  * program 1
    * text 1
  * program 2
    * text 2
    * program 3
      * text 3
      * program 4
        * text 4
    * program 5
      * text 5
  * program 6
    * text 6
```

to

```
* title
  ├── program 1
  │   └── text 1
  ├── program 2
  │   ├── text 2
  │   ├── program 3
  │   │   ├── text 3
  │   │   └── program 4
  │   │       └── text 4
  │   └── program 5
  │       └── text 5
  └── program 6
      └── text 6
```

salt和这个功能类似

## menu

生成菜单

## 粘贴图片

* 网络上复制图片到粘贴板，或者截屏到粘贴板
* windows
  * ctrl + enter
* macos
  * cmd + enter

## table

生成索引表格
