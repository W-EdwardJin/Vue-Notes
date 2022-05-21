<template>
  <!-- 组件的结构, Vue 设计的标签，相当于 html -->  
  <div class="demo">
    <h2>学习 {{ name }}</h2>
  </div>
</template>

<script>
// 组件交互相关的代码（数据、方法等等，相当于 js）
export default {
  // 这个完整 export 应该是 export default Vue.extend({...}) 在引用处创建 VueComponent 实例对象，但是 Vue 会自动帮你调用（如果直接写成对象形式）
  name: 'School',
  data() {
    return {
      name: 'Vue'
    }
  },
  methods: {

  }
}
</script>


<style scoped>
/* 组件的样式，如果没有，可以直接删掉*/
.demo {
  background-color: #00ff00;
}
</style>
