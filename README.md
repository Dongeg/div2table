# div2table
div模拟表格

```css
// 数据列表带标题，参见schoolList.ejs
.data-list {
  background-color: @white;
  overflow: hidden;
  .list-title {
    overflow: hidden;
    background-color: @bg-gary3;
    font-weight: bold;
  }
  .list-row a:hover {
    color: @bg-blue;
  }
  .cell {
    float: left;
    padding-left: 20px;
    height: 50px;
    line-height: 50px;
    text-overflow:ellipsis;
    overflow:hidden;
    white-space:nowrap;
  }
}



// div高仿表格 参见xszz.ejs
.div-table-row{
  overflow: hidden;
  width: 100%;
  margin: -1px;
  border-left: 1px solid @bg-gary1;
}

.div-table-cell{
  float: left;
  border-top: 1px solid @bg-gary1;
  border-right: 1px solid @bg-gary1;
  border-bottom: 1px solid @bg-gary1;
}
.no-border {
  border: none !important;
}
.have-border {
  border: 1px solid @bg-gary1;
}
.border-left {
  border-left:1px solid @bg-gary1 ;
}

```
