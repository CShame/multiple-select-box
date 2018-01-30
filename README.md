# multiple-select-box

#### 语言：angularjs

#### 功能： 
搜索多选下拉框

#### 参数：
##### options             <类型：obj>    双向绑定的数据
    属性：title           <类型：string> 标题
    属性：list            <类型：array>  
    属性：attrName        <类型：string> 要显示的属性名

#### 返回值：
      options.selectedValues  <类型：array> 长度为三对象数组[{},{},{}]


#### 用法：
##### html：
```html
    <multiple-select-box options="options1"></multiple-select-box>
```

##### js:
```javascript 
    $scope.options1 = {
      title: '选择项目',
      list:[{name:'哈哈哈哈'},{name:'遂宁市'},{name:'是实打实的'},{name:'试试'},{name:'试试1'},{name:'试试2'},{name:'少时诵诗书'}],
      attrName:'name'
    };
```
#### 效果图
![](/1.png "效果图")