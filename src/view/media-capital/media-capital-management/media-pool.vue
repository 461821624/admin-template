<template>
  <div id="media_pool">
    <div><Icon :type="icon" :size="size" :color="color"></Icon>新建专辑</div>

  </div>
</template>
<script>
export default {
  name: 'media-pool',
  props: {
    collapsed: Boolean,
    icon: {
      type: String,
      default: 'navicon-round'
    },
    size: {
      type: Number,
      default: 26
    },
    color:{
      type: String,
      default: '#5c6b77'
    }
  },
  data () {
    return {
      val: ''
    }
  }
}
</script>
