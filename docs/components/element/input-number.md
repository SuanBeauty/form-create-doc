### InputNumber 数字输入框

#### maker 快速生成
```js
$formCreate.maker.number('排序','sort',0)
```

#### json 规则
```json
{
        type: "InputNumber",
        field: "price",
        title: "价格",
        value: 1,
        props: {
            precision:2
        },
}
```

#### 参数说明

参考:[Element_InputNumber](http://element-cn.eleme.io/#/zh-CN/component/input-number)



##### 规则 rule

| 字段名 | 说明 | 字段类型 | 默认值 |
| :--- | :--- | :--- | :--- |
| type | 元素类型 | String | - |
| field | 字段名称 | String | - |
| title | 字段别名 | String | - |
| value | 字段值 | String,Number | - |
| props | 元素配置 | Object | - |
| event | 元素事件 | Object | - |
| validate | 验证规则 | Array | - |

##### 元素配置 props

| 参数              | 说明                   | 类型    | 可选值       | 默认值    |
| ----------------- | ---------------------- | ------- | ------------ | --------- |
| min               | 设置计数器允许的最小值 | number  | —            | -Infinity |
| max               | 设置计数器允许的最大值 | number  | —            | Infinity  |
| step              | 计数器步长             | number  | —            | 1         |
| precision         | 数值精度               | number  | —            | —         |
| size              | 计数器尺寸             | string  | large, small | —         |
| disabled          | 是否禁用计数器         | boolean | —            | false     |
| controls          | 是否使用控制按钮       | boolean | —            | true      |
| controlsPosition | 控制按钮位置           | string  | right        | -         |
| name              | 原生属性               | string  | —            | —         |
| label             | 输入框关联的label文字  | string  | —            | —         |
| placeholder       | 输入框默认 placeholder | string  | -            | -         |



##### 事件扩展 event

| 事件名称 | 说明                        | 回调参数       |
| -------- | --------------------------- | -------------- |
| change   | 绑定值被改变时触发          | 最后变更的值   |
| blur     | 在组件 Input 失去焦点时触发 | (event: Event) |
| focus    | 在组件 Input 获得焦点时触发 | (event: Event) |



