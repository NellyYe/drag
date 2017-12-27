# drag
拖拽组件


## main.js注册组件

1、使用方法 v-drag

```
以饿了么组件为例
<el-dialog
      title="选择列表"
      :visible.sync="showFlag"
      @close="closeDialog"
      v-drag
    >
```
