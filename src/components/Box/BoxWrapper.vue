<template>
<div class="BoxWrapper">
  <slot />
</div>
</template>

<style lang="scss">
@import '@/assets/scss/variables.scss';
@import '@/assets/scss/mixins.scss';

.BoxWrapper {
  background: #fff;
  @include contentBox();
  margin: 10px auto 0 auto;
}
</style>

