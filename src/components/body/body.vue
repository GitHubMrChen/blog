<template>
  <div class="mdui-container">
    <div class="item-list">
      <div v-for="(blog, index) in blogs" @click="showBlog(blog, $event)" :key="index" class="item">
        <div class="avatar" style="background-image: url('https://www.mdui.org/upload/avatar/95/5f/d785eaa8320fd14a5f0c9e62dbb1a879_m.png');"></div>
        <div class="content">
          <div class="title">{{blog.title}}</div>
          <div class="meta"><div class="username">{{blog.author}}</div>
            <div class="answer_time" :title="blog.newstime">发表于 {{blog.newstime}}</div>
          </div>
        </div>
        <div class="more"><div class="answer_count">{{blog.commontNum}}</div></div>
      </div>
    </div>
    <blog :blog="selectBlog" ref="blog"></blog>
  </div>
</template>

<script type="text/ecmascript-6">
import blog from '../blog/blog'
export default {
  data() {
    return {
      blogs: [{'title': 'Java学习心得之Springboot', 'author': 'Dminic', 'newstime': '2018-07-15', 'commontNum': 1},
        {'title': 'Java学习心得之SpringData', 'author': 'Dminic', 'newstime': '2018-07-16', 'commontNum': 2},
        {'title': 'Java学习心得之SpringCloud', 'author': 'Dminic', 'newstime': '2018-07-17', 'commontNum': 3},
        {'title': 'Java学习心得之SpringSecu', 'author': 'Dminic', 'newstime': '2018-07-18', 'commontNum': 4},
        {'title': 'Java学习心得之Springboot', 'author': 'Dminic', 'newstime': '2018-07-19', 'commontNum': 5},
        {'title': 'Java学习心得之Springboot', 'author': 'Dminic', 'newstime': '2018-07-20', 'commontNum': 6},
        {'title': 'Java学习心得之Springboot', 'author': 'Dminic', 'newstime': '2018-07-21', 'commontNum': 7},
        {'title': 'Java学习心得之Springboot', 'author': 'Dminic', 'newstime': '2018-07-22', 'commontNum': 8},
        {'title': 'Java学习心得之Springboot', 'author': 'Dminic', 'newstime': '2018-07-23', 'commontNum': 9},
        {'title': 'Java学习心得之Springboot', 'author': 'Dminic', 'newstime': '2018-07-24', 'commontNum': 10}],
      selectBlog: {}
    }
  },
  methods: {
    showBlog(blog, event) {
      this.selectBlog = blog
      this.$refs.blog.show()
    }
  },
  components: {
    blog
  }
}
</script>
<style lang="stylus" rel="stylesheet/stylus">
.mdui-container
  max-width: 1100px
  padding: 4px 0 8px 0
  // padding-top: 4px
  // padding-bottom: 8px
  -webkit-transform: translateY(0px, 0px)
  transform: translateY(0px, 0px)
  @media (max-width: 1023px)
    .mdui-container
      padding-top: 16px
  @media (max-width: 599px)
    .mdui-container
      padding-top: 8px
      width: 100%
      padding-left: 0
      padding-right: 0
  .item-list
    .item
      position: relative
      display: -webkit-box
      display: -ms-flexbox
      display: flex
      padding: 16px 22px
      border-bottom: 1px solid rgba(0, 0, 0, 0.08)
      background-color: #fff
      -webkit-box-shadow: 0 3px 1px -2px rgba(0, 0, 0, 0.2), 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 1px 5px 0 rgba(0, 0, 0, 0.12)
      box-shadow: 0 3px 1px -2px rgba(0, 0, 0, 0.2), 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 1px 5px 0 rgba(0, 0, 0, 0.12)
      -webkit-transition: background-color 0.3s cubic-bezier(0.4, 0, 0.2, 1)
      transition: background-color 0.3s cubic-bezier(0.4, 0, 0.2, 1)
      cursor: pointer
      text-decoration: none
      &.item:active
        background-color: #eee
      &.item.last-visit:before
        content: ' '
        width: 2px
        height: 100%
        position: absolute
        left: 0
        top: 0
        background-color: #3f51b5
      &.item .avatar
        width: 32px
        min-width: 32px
        height: 32px
        border-radius: 50%
        background-size: 32px 32px
        background-repeat: no-repeat
        background-position: center
        margin-right: 22px
      &.item .content
        -webkit-box-flex: 1
        -ms-flex-positive: 1
        flex-grow: 1
        overflow: hidden
      &.item .title
        color: rgba(0, 0, 0, 0.87)
        font-size: 16px
        height: 32px
        line-height: 32px
        overflow: hidden
        text-overflow: ellipsis
        white-space: nowrap
      &.item .meta
        margin-top: 12px
        display: -webkit-box
        display: -ms-flexbox
        display: flex
        line-height: 16px
        font-size: 13px
        color: rgba(0, 0, 0, 0.45)
      &.item .username
        margin-right: 6px
      &.item .more
        width: 60px
        min-width: 60px
        text-align: right
      &.item .answer_count
        line-height: 16px
        color: #fff
        background-color: #aab0c6
        padding: 0 10px
        margin: 8px 0
        border-radius: 12px
        font-weight: 700
        display: inline-block
    @media (max-width: 599px)
      .item
        padding: 12px 16px
      .item .avatar
        margin-right: 16px
      .item .title
        font-size: 15px
      .item .meta
        margin-top: 8px
      .item .more
        position: absolute
        right: 16px
        bottom: 12px
      .item .answer_count
        margin: 0
        font-weight: 500
        padding: 0 8px
</style>
