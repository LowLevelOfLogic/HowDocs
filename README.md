# README

这个是一个文档模板目录示例架构

## docs

NO.|文件名称|摘要
:--:|:--|:--
0003| [MDPlant](docs/0003_MDPlant.md) | 学习如何使用MDPlant
0002| [green_image](docs/0002_green_image.md) | 分析绿色图片原理
0001| [red_image](docs/0001_red_image.md) | 分析红色图片原理

## 目录及文件规则

### 示例目录层次

```
.
├── README.md
└── docs
    ├── 0001_red_image.md
    ├── 0002_green_image.md
    ├── images
    │   ├── 0001_red_image.png
    │   └── 0002_green_image.png
    └── refers
        ├── 0001_red_image.tar.bz2
        └── 0002_green_image.tar.bz2

3 directories, 7 files
```

### 目录说明

* 所有的总结文档放在docs目录，示例：
  * docs/0001_red_image.md
  * docs/0002_green_image.md
* 所有的引用图片放在docs/images目录，示例：
  * docs/0001_red_image.md 引用 0001_red_image.png
  * docs/0002_green_image.md 引用 0002_green_image.png
* 所有的引用文档资料放在docs/refers目录，示例：
  * docs/0001_red_image.md 引用 0001_red_image.tar.bz2
  * docs/0002_green_image.md 引用 0002_green_image.tar.bz2

### 文档名命规范说明

* 文档名命格式：[文档索引]_[内容名称].[后缀]
  * 文档索引: 采用四位表示: xxxx，例如：0231;
  * 内容名称: 不能有空格、特殊字符;
  * 后缀: 正常的文件后缀就行;
* 文档索引必须唯一，文档索引依次增加，便于查找及排序；
* 同一文档内的图片索引必须相同，便于查找及排序；
* 同一文档内的文档资料索引必须相同，便于查找及排序；
