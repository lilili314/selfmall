<template>
    <div class="tab-bar-item">
      <div class="item-icon"><slot name="icon"></slot></div>
      <div class="item-active-icon"><slot name="active-icon"></slot></div>
      <div class="item-text"><slot name="text"></slot></div>
    </div>
</template>

<script>
export default {
  name: 'tabBarItem',
}
</script>

<style>

</style>