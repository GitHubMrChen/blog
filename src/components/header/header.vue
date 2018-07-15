<template>
  <div>
    <header class="mdui-appbar mdui-appbar-fixed">
      <div class="mdui-toolbar mdui-color-theme">
        <span class="mdui-btn mdui-btn-icon mdui-ripple mdui-ripple-white" mdui-drawer="{target: '#main-drawer', swipe: true}"><i class="mdui-icon material-icons">menu</i></span>
        <a href="javascript:void(0);" class="mdui-typo-title">博客</a>
        <div class="mdui-toolbar-spacer"></div>
      </div>
    </header>
  </div>
</template>

<script type="text/ecmascript-6">
export default {
  data() {
    return {}
  }
}
</script>
<style lang="stylus" rel="stylesheet/stylus">
.mdui-toolbar
  background: -webkit-linear-gradient(rgb(53, 65, 64), rgb(15, 25, 15))
  background: -o-linear-gradient(rgb(53, 65, 64), rgb(15, 25, 15))
  background: -moz-linear-gradient(rgb(53, 65, 64), rgb(15, 25, 15))
  background: linear-gradient(rgb(53, 65, 64), rgb(15, 25, 15))
  .material-icons, .mdui-typo-title
    color: rgb(252, 228, 182)
    // background: linear-gradient(rgb(252, 228, 182), rgb(166, 146, 110))
    // -webkit-background-clip: text
    // color: transparent
</style>
