## cz-grid 是什么

cz-grid 是一个 css 栅格布局样式库

## 解决了什么问题

不论是现在还是以前，我们前端开发每天都会重复的写一些布局，其中大部分是分栏布局，就比如一行展示几列，超出的部分换行显示的这些场景

当然现在也有很多优秀的样式库，比如 BootStrap、Mui...，如果我们为了快速布局去引用 BootStrap 这么大的样式文件着实有点浪费网络资源，所以 cz-grid.css 的初衷是基于 BootStrap 的栅格系统来设计的

在 cz-grid.css 中，你可以像使用 BootStrap 的栅格那样使用 cz-grid

## 来个例子

### 外层容器

```
<div class="cz-container"></div>
```

### 流式布局

如果你需要让布局铺满全屏，可以使用这个 class 作为最外层的容器

```
<div class="cz-container-fixed"></div>
```

### 分栏

```
# 三栏布局
<div class="row">
  <div class="col-md-4">column</div>
  <div class="col-md-4">column</div>
  <div class="col-md-4">column</div>
  <div class="col-md-4">column</div>
</div>
```

## 样式属性

| 属性                | 描述                     |
| ------------------- | ------------------------ |
| .cz-container       | 顶层容器，用于在页面居中 |
| .cz-container-fixed | 流式布局，全屏效果       |
| .row                | 与.col-\*结合使用        |
| .col-xs-\*          | 手机端适配类             |
| .col-sm-\*          | pad 端适配类             |
| .col-md-\*          | pc 显示器适配类          |
| .col-lg-\*          | 桌面端适配类             |

## 阅读源码、

```
# clone
git clone https://github.com/cz-frontend/cz-grid.git

# 进入项目
cd cz-grid/src/styles/cz.grid.css
```

## 写在后面

觉得不错欢迎你的 Star、Fork，或者加入锤子前端官方技术群，一起学习交流技术吧！

### 锤子前端官方交流群

<img src='./src/images/code.jpg' style="width: 120px;height: 120px;" />
