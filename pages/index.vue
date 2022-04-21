<template>
  <div>
    <nav id="Home" class="navbar navbar-expand-lg navbar-light py-2 fixed-top">
      <a class="navbar-brand" href="#">LOGO</a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav">
          <li class="nav-item active">
            <a class="nav-link link-mause"  v-scroll-to="'#Home'">Home </a>
          </li>
          <li class="nav-item active">
            <a class="nav-link link-mause" v-scroll-to="'#About'">About</a>
          </li>
          <li class="nav-item active">
            <a class="nav-link link-mause" v-scroll-to="'#Services'"> Services</a>
          </li>
          <li class="nav-item active">
            <a class="nav-link link-mause" v-scroll-to="'#Works'">Works</a>
          </li>
          <li class="nav-item active">
            <a class="nav-link link-mause" v-scroll-to="'#Contact'">Contact</a>
          </li>
        </ul>
      </div>
    </nav>

    <main>
      <img
        class="imge"
        src="~assets/image/dylan-gillis-KdeqA3aTnBY-unsplash.jpeg"
        alt=""
        srcset=""
      />
      <div class="over">
        <div class="text-hover">
          <p>We Provide the best Features</p>
          <p>To build your brand</p>
        </div>
      </div>
    </main>

    <div class="container">
      <ul class="ul-container">
        <li class="li-container">
          <div>
            <img
              class="icon-li"
              src="~assets/image/icons/web-development.png"
              alt=""
              srcset=""
            />
          </div>
          <h5 class="h5h">Best Design Service</h5>
          <div class="li-txt">
            It is a long established fact that a reader will be distracted by
            the readable content
          </div>
          <a href="#"><samp class="icon-li fa fa-arrow-right"></samp></a>
        </li>
        <li class="li-container">
          <div>
            <img
              class="icon-li"
              src="~assets/image/icons/globe-grid.png"
              alt=""
              srcset=""
            />
          </div>
          <h5 class="h5h">Optimised Code</h5>
          <div class="li-txt">
            It is a long established fact that a reader will be distracted by
            the readable content
          </div>
          <a href="#"><samp class="icon-li fa fa-arrow-right"></samp></a>
        </li>
        <li class="li-container">
          <div>
            <img
              class="icon-li"
              src="~assets/image/icons/download.png"
              alt=""
              srcset=""
            />
          </div>
          <h5 class="h5h">Lifetime Free Support</h5>
          <div class="li-txt">
            It is a long established fact that a reader will be distracted by
            the readable content
          </div>
          <a href="#"><samp class="icon-li fa fa-arrow-right"></samp></a>
        </li>
      </ul>
    </div>

    <div class="tudo">
      <div id="About" class="baixo">
        <div class="txt-imge">
          <div class="about">About us</div>

          <h6 class="h6h">Who we are & what we did before.</h6>
          <div class="h-txt">
            It is a long established fact that a reader will be distracted by
            the readable content of a page when looking at its layout. The point
            of using Lorem Ipsum is that it has a more-or-less normal
            distribution of letters, as opposed to using 'Content here, content
            here', making it look.
            <ul class="ul-baixo">
              <li>Vitae dicta sunt explicabo nemo enim ipsay voluptatem</li>
              <li>
                It is a long established fact that a reader will be distracted
              </li>
              <li>By the readable content of a page when</li>
              <li>
                The point of using Lorem Ipsum is that it has a more-or-less
              </li>
            </ul>
            <div class="img-baixo">
              <a class="a-img-baixo" @click="someMethod()">View Details</a>
            </div>
          </div>
        </div>
        <img class="img-txt" src="~assets/image/about.png" alt="" srcset="" />
      </div>

      <div class="red-box">
        <div>
          <h6 class="h-red-box">Lets Start Together & Create a new thing</h6>
          <p>
            Lorem Ipsum is simply dummy text of the printing and typesetting
            industry.
          </p>
        </div>

        <div class="reb-box-bo">
          <a class="reb-box-a" href="#">View Details</a>
        </div>
      </div>

      <div id="Services" class="tittle-ul">
        <p class="p-tittle">Services</p>
        <h5 class="h5-tittle">What we serve to our clients</h5>
      </div>

      <ul class="ul-master">
        <ul class="ul-tre">
          <li class="li-tre">
            <div>
              <img
                class="icon-li icon-2"
                src="~assets/image/icons/briefcase.png"
                alt=""
                srcset=""
              />
            </div>
            <h5 class="h5h li-2">Best Design Service</h5>
            <div class="li-txt li-2">
              It is a long established fact that a reader will be distracted by
              the readable content
            </div>
            <a href="#"><samp class="li-2 icon-li fa fa-arrow-right"></samp></a>
          </li>
          <li class="li-tre">
            <div>
              <img
                class="icon-li icon-2"
                src="~assets/image/icons/file-folder.png"
                alt=""
                srcset=""
              />
            </div>
            <h5 class="h5h li-2">Best Design Service</h5>
            <div class="li-txt li-2">
              It is a long established fact that a reader will be distracted by
              the readable content
            </div>
            <a href="#"><samp class="li-2 icon-li fa fa-arrow-right"></samp></a>
          </li>
          <li class="li-tre">
            <div>
              <img
                class="icon-li icon-2"
                src="~assets/image/icons/office-desk.png"
                alt=""
                srcset=""
              />
            </div>
            <h5 class="h5h li-2">Best Design Service</h5>
            <div class="li-txt li-2">
              It is a long established fact that a reader will be distracted by
              the readable content
            </div>
            <a href="#"><samp class="li-2 icon-li fa fa-arrow-right"></samp></a>
          </li>
        </ul>
        <ul class="ul-tre">
          <li class="li-tre">
            <div>
              <img
                class="icon-li icon-2"
                src="~assets/image/icons/team.png"
                alt=""
                srcset=""
              />
            </div>
            <h5 class="h5h li-2">Best Design Service</h5>
            <div class="li-txt li-2">
              It is a long established fact that a reader will be distracted by
              the readable content
            </div>
            <a href="#"><samp class="li-2 icon-li fa fa-arrow-right"></samp></a>
          </li>
          <li class="li-tre">
            <div>
              <img
                class="icon-li icon-2"
                src="~assets/image/icons/united.png"
                alt=""
                srcset=""
              />
            </div>
            <h5 class="h5h li-2">Best Design Service</h5>
            <div class="li-txt li-2">
              It is a long established fact that a reader will be distracted by
              the readable content
            </div>
            <a href="#"><samp class="li-2 icon-li fa fa-arrow-right"></samp></a>
          </li>
          <li class="li-tre">
            <div>
              <img
                class="icon-li icon-2"
                src="~assets/image/icons/wrench.png"
                alt=""
                srcset=""
              />
            </div>
            <h5 class="h5h li-2">Best Design Service</h5>
            <div class="li-txt li-2">
              It is a long established fact that a reader will be distracted by
              the readable content
            </div>
            <a href="#"><samp class="li-2 icon-li fa fa-arrow-right"></samp></a>
          </li>
        </ul>
      </ul>

      <div class="tittle-ul ul-tt-2">
        <p class="p-tittle">Portfolio</p>
        <h5 class="h5-tittle">Our previous works</h5>
      </div>

      <div class="ul-anima">
        <div class="a-ul">
          <p class="a-nimate" @click="all()">ALL_CATEGORIES</p>
          <p class="a-nimate" @click="WORDPRESS()">WORDPRESS</p>
          <p class="a-nimate" @click="SEO()">SEO</p>
          <p class="a-nimate" @click="HTML()">HTML</p>
        </div>

        <div class="tr-contei">
          <ul class="t-ul">
            <transition
              mode="out-in"
              enter-active-class="animate__animated animate__fadeInDown"
              leave-active-class="animate__animated animate__fadeOutDown"
            >
              <li v-if="li1" class="tr-li">
                <img
                  class="tr-li-img"
                  src="~assets/image/transations/portfolio-1.png"
                  alt=""
                  srcset=""
                />
              </li>
            </transition>

            <transition
              mode="out-in"
              enter-active-class="animate__animated animate__fadeIn"
              leave-active-class="animate__animated animate__fadeOut"
            >
              <li v-if="li2" class="tr-li">
                <img
                  class="tr-li-img"
                  src="~assets/image/transations/portfolio-2.png"
                  alt=""
                  srcset=""
                />
              </li>
            </transition>
            <transition
              mode="out-in"
              enter-active-class="animate__animated animate__fadeInRight"
              leave-active-class="animate__animated animate__fadeOutRight"
            >
              <li v-if="li3" class="tr-li">
                <img
                  class="tr-li-img"
                  src="~assets/image/transations/portfolio-3.png"
                  alt=""
                  srcset=""
                />
              </li>
            </transition>
          </ul>

          <ul class="t-ul">
            <transition
              mode="out-in"
              enter-active-class="animate__animated animate__rotateInDownLeft"
              leave-active-class="animate__animated animate__rotateOutDownLeft"
            >
              <li v-if="li4" class="tr-li">
                <img
                  class="tr-li-img"
                  src="~assets/image/transations/portfolio-4.png"
                  alt=""
                  srcset=""
                />
              </li>
            </transition>
            <transition
              mode="out-in"
              enter-active-class="animate__animated animate__slideInUp"
              leave-active-class="animate__animated animate__slideOutDown"
            >
              <li v-if="li5" class="tr-li">
                <img
                  class="tr-li-img"
                  src="~assets/image/transations/portfolio-5.png"
                  alt=""
                  srcset=""
                />
              </li>
            </transition>
            <transition
              mode="out-in"
              enter-active-class="animate__animated animate__bounceInRight"
              leave-active-class="animate__animated animate__bounceOutRight"
            >
              <li v-if="li6" class="tr-li">
                <img
                  class="tr-li-img"
                  src="~assets/image/transations/portfolio-6.png"
                  alt=""
                  srcset=""
                />
              </li>
            </transition>
          </ul>
        </div>
      </div>
    </div>
    <div class="num-blue" id="Contact">
      <div class="num-blue-box">
        <p class="p-blue-box"><b>Perfect Solutions Free </b>online</p>
        <p class="p-margin-1">consultation</p>

        <p class="txt-num">
          Is a long established fact that a reader will be distracted by the
          readable content of a page when looking at its
        </p>
        <p class="p-margin-2 txt-num">
          layout. The point of using Lorem Ipsum is tha
        </p>

        <p class="blue-num">+91 2333 524-8798</p>
      </div>
    </div>

    <div class="tudo" id="Works">
      <div class="tittle-ul">
        <p class="p-tittle rece-tittle">Recent posts</p>
        <h5 class="h5-tittle">Our previous works</h5>
      </div>

      <ul class="ul-tree-s">
        <li class="li-tree-s">
          <img
            class="img-ul-tree"
            src="~assets/image/post-1.jpeg"
            alt=""
            srcset=""
          />

          <div class="txt-flu">
            <h6>
              <a class="a-flu-tree" href=""
                >Startup Marketing Solution for Business Owner.</a
              >
            </h6>
            <p class="txt-mim-flu">
              is simply dummy text of the printing and type tting industry.
              Lorem Ipsum has been.
            </p>

            <div class="flu-tree">
              <div class="tm-master">
                <p class="t-m-2">Eva Rakim</p>
                <p class="t-m-1">SEO Manager</p>
              </div>

              <div class="data-tree">
                <p>23 Des</p>
                <p class="data-2">2019</p>
              </div>
            </div>
          </div>
        </li>

        <li class="li-tree-s li-te-m2">
          <img
            class="img-ul-tree"
            src="~assets/image/post-2.jpeg"
            alt=""
            srcset=""
          />

          <div class="txt-flu">
            <h6>
              <a class="a-flu-tree" href=""
                >How to start a Business with no money</a
              >
            </h6>
            <p class="txt-mim-flu">
              is simply dummy text of the printing and type tting industry.
              Lorem Ipsum has been.
            </p>

            <div class="flu-tree">
              <div class="tm-master">
                <p class="t-m-2">Mark Jacobs</p>
                <p class="t-m-1">Web Desinger</p>
              </div>

              <div class="data-tree">
                <p>05 Jun</p>
                <p class="data-2">2019</p>
              </div>
            </div>
          </div>
        </li>

        <li class="li-tree-s li-mi">
          <img
            class="img-ul-tree"
            src="~assets/image/post-3.jpeg"
            alt=""
            srcset=""
          />
          <div class="txt-flu">
            <h6>
              <a class="a-flu-tree" href=""
                >How to earn money online by selling courses</a
              >
            </h6>
            <p class="txt-mim-flu">
              is simply dummy text of the printing and type tting industry.
              Lorem Ipsum has been.
            </p>

            <div class="flu-tree">
              <div class="tm-master">
                <p class="t-m-2">Alex Jhonson</p>
                <p class="t-m-1">Business Developer</p>
              </div>

              <div class="data-tree">
                <p>12 Jan</p>
                <p class="data-2">2019</p>
              </div>
            </div>
          </div>
        </li>
      </ul>
    </div>
    <Footer />
  </div>
</template>

<script>
export default {
  data() {
    return {
      //
      li1: true,
      li2: true,
      li3: true,
      li4: true,
      li5: true,
      li6: true,
    };
  },
  methods: {
    //
    all() {
      (this.li1 = true),
        (this.li2 = true),
        (this.li3 = true),
        (this.li4 = true),
        (this.li5 = true),
        (this.li6 = true);
    },
    WORDPRESS() {
      (this.li1 = false),
        (this.li2 = true),
        (this.li3 = false),
        (this.li4 = true),
        (this.li5 = false),
        (this.li6 = true);
    },
    SEO() {
      (this.li1 = true),
        (this.li2 = false),
        (this.li3 = false),
        (this.li4 = true),
        (this.li5 = true),
        (this.li6 = false);
    },
    HTML() {
      (this.li1 = true),
        (this.li2 = false),
        (this.li3 = true),
        (this.li4 = false),
        (this.li5 = true),
        (this.li6 = false);
    },
  },
};
</script>

<style scoped>
@import "~assets/style/img_menu.css";
@import "~/assets/style/menu.css";
</style>
