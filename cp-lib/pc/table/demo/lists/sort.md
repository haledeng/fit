# 表格排序

`fields` 属性设置为 `sort:true` 的列属性可以点击排序

`onSort` 回调在排序发生前触发,返回值是此时查询参数,第一个参数是当前点击的列 `key` 值,第二个参数是排序类型 `asc` `desc`