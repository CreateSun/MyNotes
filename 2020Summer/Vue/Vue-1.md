# Vue-1

## 子组件调用父组件函数

```
// 子组件
<template>
	<button v-bind:子组件的操作="$emit('自定义事件名称')">
	
	</button>
</template>

// 父组件
<component
	v-on:自定义时事件名称="function(){}"
>
	
</component>
```

