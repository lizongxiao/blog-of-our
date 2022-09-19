<template>
  <div>
    <Card
      title="请修改标题"
      :bordered="false"
      :headStyle="{ color: 'rgba(51, 51, 51, 0.85)' }"
      style="width: 100%"
    >
      <Button type="primary">按钮</Button>
    </Card>
  </div>
</template>
<script lang="ts">
import { defineComponent } from "vue";
import { Card, Button } from "ant-design-vue";
export default defineComponent({
  name: "AboutView",
  components: { Card, Button },
  setup() {
    return {};
  },
});
</script>
<style lang="less" scoped></style>
