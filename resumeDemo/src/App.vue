<template>
  <div id="app" class="px-2 pt-1 pb-4 bg-secondary">
    <header class="d-md-flex justify-content-between align-items-center mb-5 text-white bg-info rounded px-2 py-4">
      <div class="user-info d-flex align-items-center justify-content-between">
        <a class="logo">
          <img src="./assets/logo.png" class="img-fluid">
        </a>
        <div class="d-flex flex-column justify-content-around">
          <h6 class="mb-0 font-weight-bold">A <code>Vue</code> front-end developer</h6>
          <small class="font-weight-light">work with Vue Vuex VueRouter</small>
        </div>
        <i class="seperator d-md-block d-none"></i>
        <h5 class="m-0 font-weight-normal name">黄永昌</h5>
      </div>
      <a href="http://github.com/hyc127" class="font-weight-bold d-block text-center text-muted font-italic mt-3 mt-md-0">
        <svg class="icon-bigger" aria-hidden="true">
          <use xlink:href="#icon-github"></use>
        </svg>
        <kbd>www.github.com/hyc127</kbd>
      </a>
    </header>

    <main class="d-md-flex bg-dark rounded text-white py-3">
      <aside class="col-12 col-md-6 d-flex flex-column">
        <h6 class="text-warning pb-2 custom-border">基本信息/Basic info</h6>
        <section class="mb-2">
          <ul>
            <li>
              <svg class="icon" aria-hidden="true">
                <use xlink:href="#icon-accountcopy"></use>
              </svg>
              <span class="info-detail">男/30(1988)</span>
            </li>
            <li>
              <svg class="icon" aria-hidden="true">
                <use xlink:href="#icon-icon010"></use>
              </svg>
              <span class="info-detail">成都市 金牛区</span>
            </li>
            <li>
              <svg class="icon" aria-hidden="true">
                <use xlink:href="#icon-school"></use>
              </svg>
              <span class="info-detail">四川农业大学/计算机专业/本科</span>
            </li>
            <li>
              <svg class="icon" aria-hidden="true">
                <use xlink:href="#icon-phonenew"></use>
              </svg>
              <span class="info-detail">15184323832</span>
            </li>
            <li>
              <svg class="icon" aria-hidden="true">
                <use xlink:href="#icon-mail"></use>
              </svg>
              <span class="info-detail">236596214@qq.com</span>
            </li>
            <li>
              <svg class="icon" aria-hidden="true">
                <use xlink:href="#icon-xinlang"></use>
              </svg>
              <span class="info-detail">https://blog.csdn.com</span>
            </li>
          </ul>
        </section>
        <h6 class="text-warning pb-2 custom-border">
          <svg class="icon-bigger" aria-hidden="true">
            <use xlink:href="#icon-skill"></use>
          </svg>
          我的技能/My Specials</h6>
        <section class="mb-2">
          <ul class="d-flex flex-row" style="overflow-x:hidden">
            <li class="col-3 text-center">
              <img src="./assets/b.png" class="img-fluid" >
              <small class="font-weight-bold">Bootstrap</small>
            </li>
            <li class="col-3 text-center">
              <img src="./assets/logo.png" class="img-fluid" >
              <small class="font-weight-bold">Vue.js</small>
            </li>
            <li class="col-3 text-center">
              <img src="./assets/webpack.png" class="img-fluid">
              <small class="font-weight-bold">Webpack</small>
            </li>
            <li class="col-3 text-center">
              <img src="./assets/es6.png" class="img-fluid" >
              <small class="font-weight-bold">ES6</small>
            </li>
            <li class="col-3 text-center">
              <img src="./assets/b.png" class="img-fluid" >
              <small class="font-weight-bold">CSS3</small>
            </li>
          </ul>
        </section>

        <h6 class="text-warning pb-2 custom-border">
          <svg class="icon-bigger" aria-hidden="true">
            <use xlink:href="#icon-skill"></use>
          </svg>
          应用工具/Software Skills</h6>
        <section class="mb-2">
          <ul>
            <li class="d-flex flex-row align-items-center mb-2">
              <div class="col-3">
                <svg class="icon-bigger w-100" aria-hidden="true">
                  <use xlink:href="#icon-file_type_vscode"></use>
                </svg>
              </div>
              <div class="col-9">
                <p class="m-0">VsCode</p>
                <div class="progress">
                  <div class="progress-bar" role="progressbar" style="width: 80%" aria-valuenow="80" aria-valuemin="0" aria-valuemax="100"></div>
                </div>
              </div>
            </li>

            <li class="d-flex flex-row align-items-center mb-2">
              <div class="col-3">
                <svg class="icon-bigger w-100" aria-hidden="true">
                  <use xlink:href="#icon-Chrome"></use>
                </svg>
              </div>
              <div class="col-9">
                <p class="m-0">Chrome</p>
                <div class="progress">
                  <div class="progress-bar" role="progressbar" style="width: 50%" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100"></div>
                </div>
              </div>
            </li>

            <li class="d-flex flex-row align-items-center mb-2">
              <div class="col-3">
                <svg class="icon-bigger w-100" aria-hidden="true">
                  <use xlink:href="#icon-git"></use>
                </svg>
              </div>
              <div class="col-9">
                <p class="m-0">git</p>
                <div class="progress">
                  <div class="progress-bar" role="progressbar" style="width: 40%" aria-valuenow="40" aria-valuemin="0" aria-valuemax="100"></div>
                </div>
              </div>
            </li>
          </ul>
        </section>

        <h6 class="text-warning pb-2 custom-border">关于我/About Me</h6>
        <section class="mb-2">
        <p class="text-muted">在此期间参与了一个教育产品包括学生端、老师端、微信家长端以及学校管理员管理后台几个系统的前端方便的工作。微信家长端是基于vue.js制作，其他部分是基于angular和bootstrap利用gulp等一系列nodejs构建完成。与之前的听说通类似。如果之前的产品是淘宝模式，那么这个产品就是京东模式。同样包括学生端，老师端和微信家长端以及管理后台。除此之外，我们还利用ionic基于前端技术制作老师移动端分别打包成了android和ios应用。</p>
        </section>
      </aside>
      <aside class="col-12 col-md-6 d-flex flex-column">
        <h6 class="text-dark pb-2 custom-border">工作经验/Work Exprience</h6>
        <section>
          <div class="d-flex flex-row">
            <div class="display-2 col-2">1</div>

            <div class="col-10 d-flex flex-column justify-content-center mb-3">
              <div class="d-flex align-items-center justify-content-between border-bottom border-info pb-2">
                <small class="font-weight-bold">
                  <svg class="icon-bigger" aria-hidden="true">
                    <use xlink:href="#icon-conpany"></use>
                  </svg>
                  成都中科网络科技有限公司</small>
                <small>[2012.09-2015.12]</small>
              </div>
              <small class="text-muted mt-2">工作属性:实习 技术部规模:5人 职务:前端工程师</small>
            </div>
          </div>

          <div class="d-flex flex-row">
            <div class="col-2 display-3 text-center">|</div>
            <small class="pb-3 col-10">简介：该公司是一家创业公司，我在该公司实习，主要内容负责前端静态页面搭建，根据UI设计师提供的设计稿做出相应的网页，主要技术栈为jqeury & ajax</small>
          </div>
        </section>

        <section>
          <div class="d-flex flex-row">
            <div class="display-2 col-2">2</div>

            <div class="col-10 d-flex flex-column justify-content-center mb-3">
              <div class="d-flex align-items-center justify-content-between border-bottom border-info pb-2">
                <small class="font-weight-bold">
                  <svg class="icon-bigger" aria-hidden="true">
                    <use xlink:href="#icon-conpany"></use>
                  </svg>
                  成都中科网络科技有限公司</small>
                <small>[2012.09-2015.12]</small>
              </div>
              <small class="text-muted mt-2">工作属性:实习 技术部规模:5人 职务:前端工程师</small>
            </div>
          </div>

          <div class="d-flex flex-row">
            <div class="col-2 display-3 text-center">|</div>
            <small class="pb-3 col-10">简介：该公司是一家创业公司，我在该公司实习，主要内容负责前端静态页面搭建，根据UI设计师提供的设计稿做出相应的网页，主要技术栈为jqeury & ajax</small>
          </div>
        </section>

        <section>
          <div class="d-flex flex-row">
            <div class="display-2 col-2">3</div>

            <div class="col-10 d-flex flex-column justify-content-center mb-3">
              <div class="d-flex align-items-center justify-content-between border-bottom border-info pb-2">
                <small class="font-weight-bold">
                  <svg class="icon-bigger" aria-hidden="true">
                    <use xlink:href="#icon-conpany"></use>
                  </svg>
                  成都中科网络科技有限公司</small>
                <small>[2012.09-2015.12]</small>
              </div>
              <small class="text-muted mt-2">工作属性:实习 技术部规模:5人 职务:前端工程师</small>
            </div>
          </div>

          <div class="d-flex flex-row align-items-center">
            <div class="col-2 display-3 text-center">|</div>
            <small class="pb-3 col-10">简介：该公司是一家创业公司，我在该公司实习，主要内容负责前端静态页面搭建，根据UI设计师提供的设计稿做出相应的网页，主要技术栈为jqeury & ajax</small>
          </div>
        </section>

        <section class="mt-md-5 mt-2">
          <h6 class="text-warning pb-2 custom-border">兴趣爱好/hobies</h6>
          <ul class="d-flex flex-row" style="overflow-x:hidden">
            <li class="col-3 text-center">
              <svg class="hobby" aria-hidden="true">
                <use xlink:href="#icon-film"></use>
              </svg>
              <small class="font-weight-bold">电影</small>
            </li>
            <li class="col-3 text-center">
              <svg class="hobby" aria-hidden="true">
                <use xlink:href="#icon-CombinedShape"></use>
              </svg>
              <small class="font-weight-bold">音乐</small>
            </li>
            <li class="col-3 text-center">
              <svg class="hobby" aria-hidden="true">
                <use xlink:href="#icon-book"></use>
              </svg>
              <small class="font-weight-bold">阅读</small>
            </li>
            <li class="col-3 text-center">
              <svg class="hobby" aria-hidden="true">
                <use xlink:href="#icon-badaxilietubiao01"></use>
              </svg>
              <small class="font-weight-bold">运动</small>
            </li>
          </ul>
        </section>

        <section>
          <h6 class="text-warning pb-2 custom-border">作品地址&联系方式/Works&Contact</h6>
          <div class="d-flex flex-wrap">

            <div class="col-12 col-md-6 d-flex align-items-center mb-2 mb-md-3">
              <div class="img-container col-3">
                <img src="./assets/b.png" class="img-fluid">
              </div>
              <a href="">http://www.baidu.com</a>
            </div>

            <div class="col-12 col-md-6 d-flex align-items-center mb-2 mb-md-3">
              <div class="img-container col-3">
                <img src="./assets/b.png" class="img-fluid">
              </div>
              <a href="">http://www.qq.com</a>
            </div>

            <div class="col-12 col-md-6 d-flex align-items-center mb-2 mb-md-3">
              <div class="img-container col-3">
                <img src="./assets/b.png" class="img-fluid">
              </div>
              <a href="">http://www.baidu.com</a>
            </div>

            <div class="col-12 col-md-6 d-flex align-items-center mb-2 mb-md-3">
              <div class="img-container col-3">
                <img src="./assets/b.png" class="img-fluid">
              </div>
              <a href="">http://www.qq.com</a>
            </div>

            <div class="col-12 col-md-6 d-flex align-items-center mb-2 mb-md-3">
              <div class="img-container col-3">
                <img src="./assets/b.png" class="img-fluid">
              </div>
              <a href="">http://www.baidu.com</a>
            </div>

          </div>
        </section>
      </aside>
    </main>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

.logo {
  display: block;
  width: 3rem;
  height: 3rem;
}

.name {
  text-shadow: 0 1px 1px #2c3e50;
}

.seperator {
  display: block;
  height: 2rem;
  border: .5px solid dimgray;
  margin: 0 1rem 0 1rem;
}

.custom-border {
  border-bottom: 1px dotted #2c3e50
}

.info-detail {
  font-size: .5rem;
  font-weight: 500;
}

li {
  list-style: none;
}

ul {
  padding: 0;
}

.custom-img {
  height: auto;
}

.icon {
       width: 1em; height: 1em;
       vertical-align: -0.15em;
       fill: #fff;
       overflow: hidden;
    }

.icon-bigger {
  width: 2em; height: 2em;
  vertical-align: -0.6em;
  fill: #fff;
  overflow: hidden;
}

.hobby {
  max-width: 100%;
  fill: #fff;
  height: 40px;
}


</style>
