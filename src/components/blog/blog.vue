<template>
  <transition name="move">
    <div v-show="showFlag" class="blog" ref="blog">
      <div class="blog-content">
        <h2 class="rich_media_title" id="activity-name" style="font-weight:400;font-size:22px;color:#333333;font-family:-apple-system-font, BlinkMacSystemFont, &quot;background-color:#FFFFFF;">
          昔日最有前途的 Java 最终还是败给了晚辈 Python
        </h2>
        <div id="meta_content" class="rich_media_meta_list" style="margin:0px 0px 22px;padding:0px;font-size:0px;color:#333333;font-family:-apple-system-font, BlinkMacSystemFont, &quot;background-color:#FFFFFF;">
          <span id="copyright_logo" class="rich_media_meta rich_media_meta_text meta_tag_text" style="vertical-align:middle;font-size:15px;color:rgba(0, 0, 0, 0.3);">原创：</span>&nbsp;<span class="rich_media_meta rich_media_meta_text" style="vertical-align:middle;font-size:15px;color:rgba(0, 0, 0, 0.3);"><span id="js_author_name" class="rich_media_meta_link" style="color:#576B95;">屠敏</span></span>&nbsp;<span class="rich_media_meta rich_media_meta_nickname" id="profileBt" style="vertical-align:middle;font-size:15px;"><a id="js_name">CSDN</a></span>&nbsp;<span id="publish_time" class="rich_media_meta rich_media_meta_text" style="vertical-align:middle;font-size:15px;color:rgba(0, 0, 0, 0.3);">1周前</span>
        </div>
        <div class="rich_media_content " id="js_content" style="margin:0px;padding:0px;color:#333333;font-size:17px;text-align:justify;font-family:-apple-system-font, BlinkMacSystemFont, &quot;background-color:#FFFFFF;">
          <p style="text-align:center;">
            <img class=" __bg_gif" src="https://mmbiz.qpic.cn/mmbiz_gif/Pn4Sm0RsAujHRSdcX3IznHduusnhVrSgibxlHEaKkBO8A7UcDdDzAnMIA2ZLfuoUKKJrwSA8HPTejcSLotzprZw/640?wx_fmt=gif&amp;tp=webp&amp;wxfrom=5&amp;wx_lazy=1"/>
          </p>
          <blockquote>
            <p>
              <span style="font-size:15px;color:#888888;">近日，打开科技新闻，映入眼前的是，阿里推全球首家人工智能服饰店、百度发布专门用于 AI 大规模运算的芯片“<a href="http://mp.weixin.qq.com/s?__biz=MjM5MjAwODM4MA==&amp;mid=2650700200&amp;idx=1&amp;sn=81a035be4850ba7cb62cdf8252ce1a08&amp;chksm=bea6087b89d1816d1883da84607a76827fc3ec8c0248a333e04f235efb6202b93e375fa28d43&amp;scene=21#wechat_redirect" target="_blank">昆仑</a>”、祭出<a href="http://mp.weixin.qq.com/s?__biz=MjM5MjAwODM4MA==&amp;mid=2650700270&amp;idx=1&amp;sn=bc0fb06899571a9e8257eae4cb9eeb57&amp;chksm=bea6083d89d1812b66f26106f697bc964af32965f8f186c4efadf614630ed5b843df6e792187&amp;scene=21#wechat_redirect" target="_blank">智能小程序</a>、小米发布<a href="http://mp.weixin.qq.com/s?__biz=MjM5MjAwODM4MA==&amp;mid=2650699851&amp;idx=1&amp;sn=9f410e4cf1668239544350cb3c3bb85c&amp;chksm=bea6099889d1808e33cd13d091e94808c2b7090cc90f0074cf722131e3293c9132fdde519f3e&amp;scene=21#wechat_redirect" target="_blank">移动端深度学习框架 MACE</a>......再观国外，</span><span style="color:#888888;font-size:15px;">人工智能算法发现科技巨头普遍违反欧盟隐私新规、Facebook 收购英国人工智能企业&nbsp;Bloomsbury AI、&nbsp;DeepMind 游戏 AI 又有新突破......</span>
            </p>
            <p>
              <span style="color:#888888;font-size:15px;">种种迹象表明自去年燃烧起的人工智能这把火如今似乎烧的更旺了，同时跟着它一起火的还有一门叫 Python 的编程语言。</span>
            </p>
          </blockquote>
          <p>
            <span style="color:#3F3F3F;font-size:15px;">PYPL 发布了 &nbsp;7 月份最新的编程语言排行榜，从中可见，Python 依旧是增长最快的编程语言，涨幅 5.5%，其实在今年的 5 月份，Python 就已经首超了 Java 占据榜首之位。反观如今的 Java 流行度日渐下降，本月降幅 0.5 个百分点。随着时间的推移，Python 与 Java 二者似乎渐行渐远。</span>
          </p>
          <p style="text-align:center;">
            <span style="color:#3F3F3F;font-size:15px;"><img class="" src="https://mmbiz.qpic.cn/mmbiz_png/Pn4Sm0RsAujoT7PBFdRsTdYZUMf1lZCHic8wcGlpTO5Rt7rtRmm11xQric9iaYLD3FvULxND4DcbWQmpQYnaekvag/640?wx_fmt=png&amp;tp=webp&amp;wxfrom=5&amp;wx_lazy=1"/></span>
          </p>
          <p>
            <span style="color:#3F3F3F;font-size:15px;">Python 和 Java 走势：</span>
          </p>
          <p style="text-align:center;">
            <img class="" src="https://mmbiz.qpic.cn/mmbiz_png/Pn4Sm0RsAujoT7PBFdRsTdYZUMf1lZCHlRvwwjaBfxl5m0Mu1g4LRCib9ocF27oKRId0nFFNKX5SjV0AgJibJ7xA/640?wx_fmt=png&amp;tp=webp&amp;wxfrom=5&amp;wx_lazy=1"/>
          </p>
          <p>
            <span style="color:#3F3F3F;font-size:15px;">其次，第三名 JavaScript 和第四名 PHP 也稍有变动。曾经两者指数比较接近，但是近年来 PHP 下滑地厉害，过去五年中，PHP 整体下降了 6.7%，而本月就下降了 1.5%，世界上最好的编程语言还是 PHP 吗？</span>
          </p>
          <p>
            <span style="color:#3F3F3F;font-size:15px;">想当年，PHP&nbsp;凭借其简单上手而成为 Web 开发最常用的语言，如今市场份额逐渐下滑，和互联网整体的大环境不无关系。一方面，前文所述的 Python 崛起，必然要瓜分一些编程语言的流量，另一方面曾经 Web 时代的兴起到单一的移动互联网退潮、以及企业对于业务逻辑架构扩展，必用其他更高性能的语言取而代之，至此，PHP 有所减少也可以理解。</span>
          </p>
          <p>
            <span style="color:#3F3F3F;font-size:15px;">PHP 和 JavaScript 走势：</span>
          </p>
          <p>
            <span style="color:#3F3F3F;font-size:15px;"><img class="" src="https://mmbiz.qpic.cn/mmbiz_png/Pn4Sm0RsAujoT7PBFdRsTdYZUMf1lZCH4YGJgZXyU74P6HSN7iaNVGplVajlibKYtribKCA5HvohrYMx18exM3Bzg/640?wx_fmt=png&amp;tp=webp&amp;wxfrom=5&amp;wx_lazy=1"/></span>
          </p>
          <p>
            <span style="color:#3F3F3F;font-size:15px;">Top 10 编程语言走势：</span>
          </p>
          <p style="text-align:center;">
            <span style="color:#3F3F3F;font-size:15px;"><img class="img_loading" src="data:image/gif;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVQImWNgYGBgAAAABQABh6FO1AAAAABJRU5ErkJggg=="/></span>
          </p>
          <blockquote>
            <p>
              <span style="font-size:15px;color:#888888;">需要注意的是，PYPL 指数原始数据基于 Google trends ，根据编程语言在 Google 上的搜索频率（次数）来评估语言的流行度，仅是流行度的参考指标之一。</span>
            </p>
          </blockquote>
          <p>
            <span style="color:#3F3F3F;font-size:15px;"></span>
          </p>
          <p style="text-align:center;">
            <img class="" src="data:image/gif;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVQImWNgYGBgAAAABQABh6FO1AAAAABJRU5ErkJggg=="/>
          </p>
          <p style="text-align:center;">
            <span style="font-size:18px;"><strong><span style="color:#3F3F3F;">写在最后</span></strong></span>
          </p>
          <p>
            <span style="color:#3F3F3F;font-size:15px;"></span>
          </p>
          <p>
            <span style="color:#3F3F3F;font-size:15px;">其实很多 Java 可以做的事情 Python 也可以完成，但目前就国内而言，企业级的应用仍以 Java 为主，而 Python 还是多用于数据分析、网络爬虫、Web 应用开发、云计算、自动化运维等领域。究其原因，不少网友表示：</span>
          </p>
          <ul class="list-paddingleft-2">
            <li>
              <p>
                <span style="color:#3F3F3F;font-size:15px;">Java 已经耕耘市场多年，企业级应用早已建成，后期也耗费了诸多开发者的心血、想要改成 Python 也不大现实，相较而言，</span><span style="color:#3F3F3F;font-size:15px;">Python 还是比较小众化了；</span>
              </p>
            </li>
            <li>
              <p>
                <span style="color:#3F3F3F;font-size:15px;">执行速度是企业级应用的命脉，同一行为，Java 比 Python 的运行速度更快；</span>
              </p>
            </li>
            <li>
              <p>
                <span style="color:#3F3F3F;font-size:15px;">和 Python 相比，Java 更适合作为一种底层的实现语言。</span>
              </p>
            </li>
          </ul>
          <p>
            <span style="color:#3F3F3F;font-size:15px;">对此，你怎么看呢？欢迎下方留言分享你的想法。</span>
          </p>
        </div>
      </div>
      <button @click="hide" class="mdui-fab mdui-fab-fixed mdui-color-theme-accent mdui-ripple"><i class="mdui-icon material-icons">arrow_back</i></button>
    </div>
  </transition>
</template>

<script type="text/ecmascript-6">
import BScroll from 'better-scroll'
export default {
  props: {
    blog: {
      type: Object,
      default() {
        return {}
      }
    }
  },
  data() {
    return {
      showFlag: false
    }
  },
  methods: {
    show() {
      this.showFlag = true
      this.$nextTick(() => {
        if (!this.scroll) {
          this.scroll = new BScroll(this.$refs.blog, {
            click: true
          })
        } else {
          this.scroll.refresh()
        }
      })
    },
    hide() {
      this.showFlag = false
    }
  }
}
</script>
<style lang="stylus" rel="stylesheet/stylus">
.move-enter-active, .move-leave-active
  transition: all .3s linear
  transform: translate3d(0, 0, 0)
.move-enter, .move-leave-to
  transform: translate3d(100%, 0, 0)
.blog
  position: fixed
  // padding: 8px 5px
  left: 0
  top: 56px
  bottom: 0
  z-index: 30
  width: 100%
  // overflow: auto
  background: #fff
  .blog-content
    position: relative
    width: auto
    padding: 16px 8px
    img
      width: 100%
  button
    background-color: #fff!important
</style>
