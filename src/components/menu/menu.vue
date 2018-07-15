<template>
  <div class="mdui-drawer" id="main-drawer">
    <div class="mdui-list" mdui-collapse="{accordion: true}" style="margin-bottom: 76px;">
      <div class="mdui-list-item mdui-ripple">
        <i class="mdui-list-item-icon mdui-icon material-icons mdui-text-color-orange-50">home</i>
        <div class="mdui-list-item-content">Home</div>
      </div>
      <div class="mdui-collapse-item ">
        <div class="mdui-collapse-item-header mdui-list-item mdui-ripple">
          <i class="mdui-list-item-icon mdui-icon material-icons mdui-text-color-orange-100">format_list_bulleted</i>
          <div class="mdui-list-item-content">分类文章一</div>
          <i class="mdui-collapse-item-arrow mdui-icon material-icons">keyboard_arrow_down</i>
        </div>
        <div class="mdui-collapse-item-body mdui-list">
          <a href="./download" class="mdui-list-item mdui-ripple ">安装</a>
          <a href="./compatibility" class="mdui-list-item mdui-ripple ">兼容性</a>
          <a href="./jq" class="mdui-list-item mdui-ripple ">JavaScript 工具库</a>
          <a href="./global" class="mdui-list-item mdui-ripple ">JavaScript 全局方法</a>
        </div>
      </div>
      <div class="mdui-collapse-item ">
        <div class="mdui-collapse-item-header mdui-list-item mdui-ripple">
          <i class="mdui-list-item-icon mdui-icon material-icons mdui-text-color-orange-300">format_list_bulleted</i>
          <div class="mdui-list-item-content">分类文章二</div>
          <i class="mdui-collapse-item-arrow mdui-icon material-icons">keyboard_arrow_down</i>
        </div>
        <div class="mdui-collapse-item-body mdui-list">
          <a href="./color" class="mdui-list-item mdui-ripple ">颜色与主题</a>
          <a href="./font" class="mdui-list-item mdui-ripple ">字体</a>
          <a href="./grid" class="mdui-list-item mdui-ripple ">网格布局</a>
          <a href="./typo" class="mdui-list-item mdui-ripple ">排版</a>
          <a href="./icon" class="mdui-list-item mdui-ripple ">图标</a>
          <a href="./media" class="mdui-list-item mdui-ripple ">媒体</a>
          <a href="./helper" class="mdui-list-item mdui-ripple ">辅助类</a>
          <a href="./shadow" class="mdui-list-item mdui-ripple ">阴影</a>
        </div>
      </div>
      <div class="mdui-collapse-item ">
        <div class="mdui-collapse-item-header mdui-list-item mdui-ripple">
          <i class="mdui-list-item-icon mdui-icon material-icons mdui-text-color-orange-500">format_list_bulleted</i>
          <div class="mdui-list-item-content">分类文章三</div>
          <i class="mdui-collapse-item-arrow mdui-icon material-icons">keyboard_arrow_down</i>
        </div>
        <div class="mdui-collapse-item-body mdui-list">
          <a href="./ripple" class="mdui-list-item mdui-ripple ">涟漪动画效果</a>
          <a href="./button" class="mdui-list-item mdui-ripple ">按钮</a>
          <a href="./fab" class="mdui-list-item mdui-ripple ">浮动操作按钮</a>
          <a href="./select" class="mdui-list-item mdui-ripple ">下拉选择</a>
          <a href="./divider" class="mdui-list-item mdui-ripple ">分隔线</a>
          <a href="./panel" class="mdui-list-item mdui-ripple ">可扩展面板</a>
          <a href="./textfield" class="mdui-list-item mdui-ripple ">文本框</a>
          <a href="./selection_control" class="mdui-list-item mdui-ripple ">选择控件</a>
          <a href="./slider" class="mdui-list-item mdui-ripple ">滑块</a>
          <a href="./list" class="mdui-list-item mdui-ripple ">列表</a>
          <a href="./list_control" class="mdui-list-item mdui-ripple ">列表控制</a>
          <a href="./grid_list" class="mdui-list-item mdui-ripple ">网格列表</a>
          <a href="./tab" class="mdui-list-item mdui-ripple ">Tab 选项卡</a>
          <a href="./toolbar" class="mdui-list-item mdui-ripple ">工具栏</a>
          <a href="./appbar" class="mdui-list-item mdui-ripple ">应用栏</a>
          <a href="./drawer" class="mdui-list-item mdui-ripple ">抽屉式导航</a>
          <a href="./bottom_nav" class="mdui-list-item mdui-ripple ">底部导航栏</a>
          <a href="./card" class="mdui-list-item mdui-ripple ">卡片</a>
          <a href="./chip" class="mdui-list-item mdui-ripple ">纸片</a>
          <a href="./tooltip" class="mdui-list-item mdui-ripple ">工具提示</a>
          <a href="./snackbar" class="mdui-list-item mdui-ripple ">Snackbar</a>
          <a href="./table" class="mdui-list-item mdui-ripple ">表格</a>
          <a href="./dialog" class="mdui-list-item mdui-ripple ">对话框</a>
          <a href="./menu" class="mdui-list-item mdui-ripple ">菜单</a>
          <a href="./progress" class="mdui-list-item mdui-ripple ">进度指示器</a>
        </div>
      </div>
      <div class="mdui-collapse-item">
        <div class="mdui-collapse-item-header mdui-list-item mdui-ripple">
          <i class="mdui-list-item-icon mdui-icon material-icons mdui-text-color-orange-700">format_list_bulleted</i>
          <div class="mdui-list-item-content">分类文章四</div>
          <i class="mdui-collapse-item-arrow mdui-icon material-icons">keyboard_arrow_down</i>
        </div>
        <div class="mdui-collapse-item-body mdui-list">
          <a href="./collapse" class="mdui-list-item mdui-ripple">Collapse</a>
          <a href="./headroom" class="mdui-list-item mdui-ripple ">Headroom</a>
        </div>
      </div>
      <div class="mdui-collapse-item ">
        <div class="mdui-collapse-item-header mdui-list-item mdui-ripple">
          <i class="mdui-list-item-icon mdui-icon material-icons mdui-text-color-orange-900">format_list_bulleted</i>
          <div class="mdui-list-item-content">分类文章五</div>
          <i class="mdui-collapse-item-arrow mdui-icon material-icons">keyboard_arrow_down</i>
        </div>
        <div class="mdui-collapse-item-body mdui-list">
          <a href="./material_icon" class="mdui-list-item mdui-ripple">Material 图标</a>
        </div>
      </div>
    </div>
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
.mdui-drawer
  margin-top: 56px
  background: -webkit-linear-gradient(rgb(18, 25, 21), rgb(108, 107, 95))
  background: -o-linear-gradient(rgb(18, 25, 21), rgb(108, 107, 95))
  background: -moz-linear-gradient(rgb(18, 25, 21), rgb(108, 107, 95))
  background: linear-gradient(rgb(18, 25, 21), rgb(108, 107, 95))
  .mdui-list-item
    color: rgb(252, 228, 182)
    .mdui-list-item-icon
      color: rgb(166, 146, 110)
    // background: linear-gradient(rgb(252, 228, 182), rgb(166, 146, 110))
    // -webkit-background-clip: text
    // color: transparent
  .mdui-collapse-item-arrow
    color: rgb(166, 146, 110)
    // background: linear-gradient(rgb(252, 228, 182), rgb(166, 146, 110))
    // -webkit-background-clip: text
    // color: transparent
.mdui-overlay-show
    top: 56px
</style>
