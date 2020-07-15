<template>
  <div>
    <header class="lHeader">
      <div>
        <div class="lContainer-wide pNav-container">
          <nav class="pNav">
            <div class="pNav_sp">
              <a href="/" class="pNav-logo">
                <img src="~/assets/img/logo.svg" alt="" class="pNav_logo_img">
              </a>
              <button class="pNav_menu_trigger"></button>
            </div>
            <div class="pNav_inner"></div>
          </nav>
        </div>
      </div>
    </header>
    <nuxt />
    <footer class="lFooter">
      <div class="pFooter">
        <a href="/story" class="pFooter_who jsHover">
          <div class="pFooter_who_bg jsParallax_target is-in-viewed">
            <div class="pFooter_who_bg_inner uImg_fit">
              <img src="~/assets/img/footer_background_01.jpg" alt />
            </div>
          </div>
        </a>
        <div class="pFooter_info uBg_gradation">
          <div class="pFooter_info_inner">
            <p class="pFooter_info_title">導入のご検討・ご相談はこちらから</p>
            <ul class="pFooter_info_li">
              <li class="pFooter_info_li_i">
                <a href="/" class="pFooter_info_link jsHover">
                  <div class="pFooter_info_panel">
                    <div class="pFooter_info_panel_container">
                      <div class="pFooter_info_panel_inner">
                        <div class="pFooter_info_img_block">
                          <span class="pFooter_info_img -dl">
                            <svg xmlns="http://www.w3.org/2000/svg" height="24" viewBox="0 0 24 24" width="24">
                            <path d="M0 0h24v24H0z" fill="none"/>
                            <path d="M6 2c-1.1 0-1.99.9-1.99 2L4 20c0 1.1.89 2 1.99 2H18c1.1 0 2-.9 2-2V8l-6-6H6zm7 7V3.5L18.5 9H13z"/>
                            </svg>
                          </span>
                        </div>
                      </div>
                      <p class="pFooter_info_li_label">
                        <span class="pFooter_info_li_label_inner jsSplit">DOWNLOAD</span>
                      </p>
                    </div>
                  </div>
                  <p class="pFooter_info_li_title">資料ダウンロード</p>
                  <p class="pFooter_info_li_content">
                    導入を検討されている方のために
                    <br class="pc">PDF資料をご用意しています
                  </p>
                </a>
              </li>
              <li class="pFooter_info_li_i">
                <a href="/" class="pFooter_info_link jsHover">
                  <div class="pFooter_info_panel">
                    <div class="pFooter_info_panel_container">
                      <div class="pFooter_info_panel_inner">
                        <div class="pFooter_info_img_block">
                          <span class="pFooter_info_img -dl">
                            <svg xmlns="http://www.w3.org/2000/svg" height="24" viewBox="0 0 24 24" width="24">
                            <path d="M0 0h24v24H0z" fill="none"/>
                            <path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/>
                            </svg>
                          </span>
                        </div>
                      </div>
                      <p class="pFooter_info_li_label">
                        <span class="pFooter_info_li_label_inner jsSplit">MAILFORM</span>
                      </p>
                    </div>
                  </div>
                  <p class="pFooter_info_li_title">
                    お問い合わせ・
                    <br />導入のご相談
                  </p>
                  <p class="pFooter_info_li_content">
                    お見積もりなど詳しいご相談は
                    <br class="pc">お問い合わせフォームをご活用ください
                  </p>
                </a>
              </li>
              <li class="pFooter_info_li_i">
                <a href="/" class="pFooter_info_link jsHover">
                  <div class="pFooter_info_panel">
                    <div class="pFooter_info_panel_container">
                      <div class="pFooter_info_panel_inner">
                        <div class="pFooter_info_img_block">
                          <span class="pFooter_info_img -dl">
                            <svg xmlns="http://www.w3.org/2000/svg" height="24" viewBox="0 0 24 24" width="24">
                            <path d="M0 0h24v24H0z" fill="none"/>
                            <path d="M20.01 15.38c-1.23 0-2.42-.2-3.53-.56-.35-.12-.74-.03-1.01.24l-1.57 1.97c-2.83-1.35-5.48-3.9-6.89-6.83l1.95-1.66c.27-.28.35-.67.24-1.02-.37-1.11-.56-2.3-.56-3.53 0-.54-.45-.99-.99-.99H4.19C3.65 3 3 3.24 3 3.99 3 13.28 10.73 21 20.01 21c.71 0 .99-.63.99-1.18v-3.45c0-.54-.45-.99-.99-.99z"/>
                            </svg>
                          </span>
                        </div>
                      </div>
                      <p class="pFooter_info_li_label">
                        <span class="pFooter_info_li_label_inner jsSplit">TELL</span>
                      </p>
                    </div>
                  </div>
                  <p class="pFooter_info_li_title">050-1744-4461</p>
                  <p class="pFooter_info_li_content">
                    月~金 10:00~17:00
                    <br />(年末年始・祝日を除く)
                  </p>
                </a>
              </li>
            </ul>
          </div>
        </div>
        <div class="pFooter_main">
          <div class="lContainer-middle pFooter_nav_container">
            <nav class="pFooter_nav">
              <div class="pFooter_nav_left">
                <div>
                  <a href="/" class="pFooter_nav_logo">
                    <img src="~/assets/img/logo.svg" alt="" class="pNav_footer_logo_img">
                  </a>
                  <a href="/" class="pFooter_nav_recruit jsHover">
                    <p class="pFooter_nav_recruit_inner">
                      <span class="pFooter_nav_recruit_text jsSplit">一緒に働きませんか？</span>
                    </p>
                    <div class="pFooter_nav_recruit_bg"></div>
                  </a>
                </div>
              </div>
              <div class="pFooter_nav_right">
                <ul class="pFooter_nav_li">
                  <li class="pFooter_nav_li_i">
                    <a href="/" class="pFooter_nav_text jsHover">特徴</a>
                    <ul class="pFooter_nav_li-sub">
                      <li class="pFooter_nav_li-sub_i">
                        <a href="/" class="pFooter_nav_text-sub jsHover">PLATFORM APP</a>
                      </li>
                      <li class="pFooter_nav_li-sub_i">
                        <a href="/" class="pFooter_nav_text-sub jsHover">PLATFORM KIOSK</a>
                      </li>
                      <li class="pFooter_nav_li-sub_i">
                        <a href="/" class="pFooter_nav_text-sub jsHover">PLATFORM DATA</a>
                      </li>
                    </ul>
                  </li>
                  <li class="pFooter_nav_li_i">
                    <a href="/" class="pFooter_nav_text jsHover">機能</a>
                    <ul class="pFooter_nav_li-sub">
                      <li class="pFooter_nav_li-sub_i">
                        <a href="/" class="pFooter_nav_text-sub jsHover">注文を資産に変えるための機能</a>
                      </li>
                    </ul>
                  </li>
                  <li class="pFooter_nav_li_i">
                    <a href="/story" class="pFooter_nav_text jsHover">ストーリー</a>

                    <ul class="pFooter_nav_li-sub">
                      <li class="pFooter_nav_li-sub_i">
                        <a href="/story" class="pFooter_nav_text-sub jsHover">私たちだからできる事</a>
                      </li>
                    </ul>
                  </li>
                  <li class="pFooter_nav_li_i">
                    <a href="/" class="pFooter_nav_text jsHover">事例</a>

                    <ul class="pFooter_nav_li-sub">
                      <li class="pFooter_nav_li-sub_i">
                        <a href="/" class="pFooter_nav_text-sub jsHover">利用企業と導入事例</a>
                      </li>
                    </ul>
                  </li>
                  <li class="pFooter_nav_li_i">
                    <a href="/" class="pFooter_nav_text jsHover">運用支援</a>

                    <ul class="pFooter_nav_li-sub">
                      <li class="pFooter_nav_li-sub_i">
                        <a href="/" class="pFooter_nav_text-sub jsHover">飲食店に特化した支援</a>
                      </li>
                    </ul>
                  </li>
                  <li class="pFooter_nav_li_i">
                    <a href="/" class="pFooter_nav_text jsHover">価格</a>

                    <ul class="pFooter_nav_li-sub">
                      <li class="pFooter_nav_li-sub_i">
                        <a href="/" class="pFooter_nav_text-sub jsHover">PLATFORMの価格</a>
                      </li>
                    </ul>
                  </li>
                  <li class="pFooter_nav_li_i">
                    <a href="/" class="pFooter_nav_text jsHover">イベント・セミナー</a>

                    <ul class="pFooter_nav_li-sub">
                      <li class="pFooter_nav_li-sub_i">
                        <a href="/" class="pFooter_nav_text-sub jsHover">セミナー日程のご案内</a>
                      </li>
                    </ul>
                  </li>
                </ul>
                <div class="pFooter_nav_btn_container">
                  <a href="/" class="cBtn -gray jsHover pFooter_nav_btn">
                    <span class="cBtn_inner">
                      <span class="cBtn_text">
                        <span class="pFooter_nav_btn_inner jsSplit">資料ダウンロード</span>
                      </span>
                    </span>
                  </a>
                  <a href="/" class="cBtn -yellow jsHover pFooter_nav_btn" data-v-560c5cfc>
                    <span class="cBtn_inner" data-v-560c5cfc>
                      <span class="cBtn_text">
                        <span class="pFooter_nav_btn_inner jsSplit">お問い合わせ</span>
                      </span>
                    </span>
                  </a>
                </div>
              </div>
            </nav>
            <div class="pFooter_foot">
              <ul class="pFooter_foot_li">
                <li class="pFooter_foot_li_i">
                  <a href="/" class="pFooter_foot_li_text jsHover">運営会社</a>
                </li>
                <li class="pFooter_foot_li_i">
                  <a href="/" class="pFooter_foot_li_text jsHover">採用情報</a>
                </li>
                <li class="pFooter_foot_li_i">
                  <a href="/" class="pFooter_foot_li_text jsHover">個人情報の取り扱いについて</a>
                </li>
              </ul>
              <p class="pFooter_foot_copy">
                <a href="/">Kachiri, inc.</a>
              </p>
            </div>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {};
</script>

<style>
header {
  overflow: hidden;
}
.lHeader {
  position: fixed;
  height: 60px;
  width: 100%;
  background-color: white;
  z-index: 100;
  top: 0;
  left: 0;
}
.pNav_sp {
  position: relative;
  height: 60px;
  display: flex;
  align-items: center;
  justify-content: center;
}
.pNav_logo_img {
  width: 146px;
  height: 17px;
}
.pFooter_nav_recruit_text {
  font-size: 15px;
  font-weight: 700;
}
.pNav_menu_trigger {
  position: absolute;
  display: block;
  width: 55px;
  height: 100%;
  top: 0px;
  right: 0px;
  border: none;
  background-color: white;
}
.lFooter {
  position: relative;
  z-index: 50;
}
.pFooter_who {
  align-items: center;
  height: 284px;
  max-height: auto;
  padding-bottom: 0px;
  width: 100%;
  overflow: hidden;
  background-color: #1a1a1a;
  position: relative;
  display: flex;
  justify-content: center;
}
.pFooter_who_bg {
  background-image: url();
  position: absolute;
  top: 0px;
  height: 100%;
  width: 100%;
}
.uImg_fit {
  position: absolute;
  object-fit: cover;
  font-family: "object-fit: cover";
  width: 100%;
  height: 100%;
}
.pFooter_info {
  position: relative;
  background-color: #f5bf1e;
  overflow: hidden;
}
.pFooter_info_inner {
  padding: 35px 45px;
  position: relative;
  z-index: 10;
}
.pFooter_info_title {
  margin-bottom: 30px;
  font-size: 17px;
  font-weight: 700;
  text-align: center;
}
.pFooter_info_li {
  display: block;
  text-align: center;
  width: 100%;
  margin: 0px auto;
}
.pFooter_info_li_i {
  margin-bottom: 15px;
  position: relative;
  width: 100%;
  text-align: left;
}
.pFooter_info_link {
  display: block;
  padding: 40px 35px 20px;
  background-color: #fff;
  border-radius: 4px;
  color: #010101;
}
.pFooter_info_panel {
  position: absolute;
  top: 0px;
  left: 0px;
  width: 100%;
  height: 100%;
}
.pFooter_info_panel_container {
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  width: 100%;
  padding-top: 5px;
  margin-bottom: 30px;
  font-weight: 700;
}
.pFooter_info_li_label {
  font-size: 10px;
  position: absolute;
  top: 22px;
  left: 35px;
}
.pFooter_info_li_title {
  font-weight: 700;
  font-size: 15px;
  position: relative;
  width: 122.5px;
  margin-bottom: 10px;
}
.pFooter_info_li_content {
  position: relative;
  font-size: 13px;
  line-height: 1.53;
}
.pFooter_main {
  padding: 0px 0px 30px;
  background-color: #f5f7f8;
}
.pFooter_nav_container {
  width: 100%;
}
.lContainer-middle {
  width: 100%;
  margin-right: auto;
  margin-left: auto;
}
.pFooter_nav {
  position: relative;
  padding-bottom: 215px;
  display: flex;
}
.pNav_footer_logo_img {
  width: 184px;
  height: 22px;
}
.pFooter_nav_recruit {
  position: relative;
  display: block;
  margin-top: 25px;
}
.pFooter_nav_recruit_inner {
  display: inline-block;
  position: relative;
  padding: 15px;
  margin-top: -2px;
  line-height: 1;
  font-size: 0;
  z-index: 10;
  margin-bottom: 0;
  color: #010101;
}
.pFooter_nav_recruit_bg {
  position: absolute;
  border: 2px solid #1a1a1a;
  width: 100%;
  height: 100%;
  left: 0;
  border-radius: 4px;
}
.pFooter_nav_recruit_bg,.pFooter_nav_recruit_inner {
  top: -2px;
}
.pFooter_nav_left {
  display: flex;
  position: absolute;
  align-items: center;
  justify-content: center;
  width: 100%;
  height: 215px;
  bottom: 0;
}
.pFooter_nav_right {
  display: block;
  width: 100%;
}
.pFooter_nav_li {
  width: 100%;
  columns: auto;
  margin-bottom: 50px;
  line-height: 1;
}
.pFooter_nav_li_i {
  padding-right: 0px;
  padding-bottom: 0px;
}
.pFooter_nav_text {
  color: #010101;
  display: block;
  margin: 0px;
  white-space: normal;
  border-bottom: 1px solid rgba(26, 26, 26, 0.1);
  padding: 12px 15px;
  background-color: #fff;
  position: relative;
  font-size: 16px;
  font-weight: 700;
}
.pFooter_nav_li-sub {
  margin-bottom: 0px;
}
.pFooter_nav_text-sub {
  color: #010101;
  position: relative;
  padding: 15px 10px 15px 40px;
  display: block;
  margin: 0px;
  white-space: normal;
  border-bottom: 1px solid rgba(26, 26, 26, 0.1);
  font-size: 14px;
  font-weight: 700;
}
.cBtn_inner {
  position: relative;
  display: flex;
  width: 100%;
  align-items: center;
  justify-content: center;
}
.cBtn_inner[data-v-560c5cfc] {
  background-color: #f5bf1e;
  color: #010101;
}
.pFooter_nav_btn {
  margin-bottom: 10px;
}
.pFooter_nav_btn_container {
  text-align: center;
}
.pFooter_foot {
  border-top: 2px solid #010101;
  display: block;
  margin: 0 auto;
}
.pFooter_foot_li {
  margin-left: 0;
  display: flex;
  margin-top: -1px;
  padding-top: 20px;
}
.pFooter_foot_li_text {
  color: #010101;
  font-size: 10px;
  font-weight: 600;
  padding: 0.75rem;
}
.pFooter_foot_copy {
  margin-top: 10px;
  margin-bottom: 0;
  text-align: center;
  font-size: 10px;
  font-weight: 700;
  color: #010101;
}
@media screen and (min-width: 767px) {
  .lHeader {
    background-color: transparent;
  }
  .pNav_menu_trigger {
    background-color: transparent;
  }
  .lFooter {
    position: relative;
    z-index: 50;
    display: block;
  }
  .pFooter_info {
    position: relative;
  }
  .pFooter_info_inner {
    padding: 6rem 0 4rem;
    position: relative;
    z-index: 10;
  }
  .pFooter_info_li {
    display: flex;
    justify-content: space-between;
    text-align: center;
    width: 100%;
    max-width: 50rem;
    margin: 0px auto;
  }
  .pFooter_info_li_i {
    position: relative;
    width: 32%;
  }
  .pFooter_info_panel_container {
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    width: 100%;
    height: 14rem;
    padding-top: .5rem;
    margin-bottom: 3rem;
    background-color: #fff;
    font-size: 1.6rem;
    font-weight: 700;
    letter-spacing: 0;
    border-radius: 4px;
    overflow: hidden;
  }
  .pNav_footer_logo_img {
  width: 115px;
  height: 13.75px;
}
.pFooter_nav_recruit {
  position: relative;
  display: block;
  margin-top: 25px;
}
.pFooter_nav_recruit_inner {
  display: inline-block;
  position: relative;
  padding: 15px;
  margin-top: -2px;
  line-height: 1;
  font-size: 0;
  z-index: 10;
  margin-bottom: 0;
  color: #010101;
}
.pFooter_nav_recruit_bg {
  position: absolute;
  border: 2px solid #1a1a1a;
  width: 30%;
  height: 100%;
  left: 0;
  border-radius: 4px;
}
.pFooter_nav_recruit_bg,.pFooter_nav_recruit_inner {
  top: -2px;
}
  .pFooter_main {
    padding: 9rem 0 6rem;
  }
  
  .lContainer-middle {
    width: 85vw;
    margin-left: auto;
    margin-right: auto;
  }
  .pFooter_nav {
    position: relative;
    display: flex;
    justify-content: space-between;
    padding-bottom: 4rem;
  }
  .pFooter_nav_left {
    top: 0;
    left: 0;
    display: block;
  }
  .pFooter_nav_right {
    display: flex;
    bottom: 0;
    right: 0;
  }
  .pFooter_nav_li {
    width: 60rem;
    column-count: 2;
    line-height: 1rem;
    display: block;
    list-style-type: disc;
    margin-block-start: 1em;
    margin-block-end: 1em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
    padding-inline-start: 40px;
  }
  .pFooter_nav_li_i {
    break-inside: avoid-column;
    padding-bottom: 2.5rem;
    padding-right: 1em;
    list-style: none;
  }
  .pFooter_who {
    display: none;
  }
.pFooter_foot {
    display: flex;
    justify-content: space-between;
    padding-top: 3rem;
    border-top: 2px solid #1a1a1a;
  }
  .pFooter_foot_li {
    display: flex;
    margin-top: -1rem;
    margin-left: -1rem;
  }
  .pFooter_foot_li_text {
    position: relative;
    display: inline-block;
    padding: 1rem;
    
  }
  .pFooter_nav_text {
    background-color: #f5f7f8;
    display: inline-block;
    padding: 1rem;
    margin: 0 0 0 -1rem;
    white-space: normal;
    font-size: 10px;
    border-bottom: none;
  }
  .pFooter_nav_text-sub {
    display: inline-block;
    position: relative;
    padding: 1rem calc(1rem + 5px) 1rem 1.5rem;
    margin: 1rem 0 0 .5rem;
    white-space: nowrap;
    overflow: hidden;
    font-size: 10px;
    border-bottom: none;
  }
}

</style>