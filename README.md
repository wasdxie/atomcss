# atomcss
通用的一些css属性

写css的时候起名字很烦，也不好起，所以总结了一些通用的css属性分为以下几个方面

## 1.外边距简写系列 

m-1 ... m-40  对应 .m-1{margin:1px} ... .m-40{margin:40}

ml-1 ... ml-40 对应 .ml-1{margin-left:1px} ... ml-40{margin-left:40px}

mr-1 ... mr-40 对应 .mr-1{margin-right:1px} ... mr-40{margin-right:40px}

mt-1 ... mt-40 对应 .ml-1{margin-top:1px} ... ml-40{margin-top:40px}

mb-1 ... mb-40 对应 .mb-1{margin-bottom:1px} ... mb-40{margin-bottom:40px}


## 2.内边距简写系列

p-1 ... p-40 对应 .p-1{padding:1px} ... p-40{padding:40px}


pl-1 ... pl-40 对应 .pl-1{padding-left:1px} ... pl-40{padding-left:40px}

pr-1 ... pr-40 对应 .pr-1{padding-right:1px} ... pr-40{padding-right:40px}

pt-1 ... pt-40 对应 .pt-1{padding-top:1px} ... pt-40{padding-top:40px}

pb-1 ... pb-40 对应 .pb-1{padding-bottom:1px} ... ml-40{padding-bottom:40px}


## 3.flex简写系列

.flex{display: flex;}

.flex-wrap{display: flex;flex-wrap: wrap;}

.flex-column{display: flex;flex-direction: column;}

.flex-x-center{display:flex;justify-content:center}

.flex-y-center{display:flex;align-items:center}

.flex-xy-center{display:flex;justify-content:center;align-items:center}


## 4.字体大小简写系列

.font-12{font-size:12px}

.font-14{font-size:14px}

.font-16{font-size:16px}

.font-18{font-size:18px}

.font-20{font-size:20px}

## 5.字体加粗简写系列

.weight-500{font-weight:500}

.weight-600{font-weight:600}

.weight-blod{font-weight:blod}

## 6.字体颜色简写系列

.color-337aff {
  color: #337aff;
}

## 7.display 简写系列

.inline-block{display:inline-block}

.block{display:block}

## 8. margin 左右居中简写系列

.margin-x-center{margin-left:auto;margin-right:auot}

## 9.position 简写系列

.absolute{position:absolute}

.relative{position:relative}

## 10.添加可点击小箭头简写系列

.pointer {
  cursor: pointer;
}

## 11.text-align 居中简写
.ta-c {
  text-align: center;
}

## 12.去除滚动条系列
/*
 去除滚动条 firefox
 */
 
.clear-scrollbar {
  scrollbar-width: none;
}

/*
 去除滚动条 chrome
 */
 
.clear-scrollbar::-webkit-scrollbar {
  display: none;
}



