## height100% 在chrome中会自动计算，父盒子高度减去站位的兄弟元素的高度，但在firefox中不会，所以将height:100%改成 height: calc(100% - 某个高度)

## 关于overflow: scroll;会导致padding-bottom失效，解决方法是使用after微元素取代padding-bottom 
`.after:after{
    content: "";
    display: block;
    height: 100px;
    width: 100%;
}`