<template>
 <div>
   <Card
    title='请修改标题'
    :bordered='false'
    :headStyle="{ color: 'rgba(51, 51, 51, 0.85)' }"
    style='width: 100%'
    >
   </Card>
 </div>
</template>
<script  lang="ts">
import { defineComponent } from 'vue';
import { Card } from 'ant-design-vue';
 export default defineComponent({
   name:'请输入名字',
   components: { Card },
  setup() {
   return {};
   },
  });
</script>
<style lang="less" scoped>
</style>
