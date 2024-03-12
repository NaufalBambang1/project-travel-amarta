<template>
  <div>
    <div class="bg-main-image">
      <!-- Navbar -->
      <section id="navbar" class="navbar-dqa pt-2 pb-2 pl-4 pr-4" style="z-index: 10000;">
        <div class="container-dqa d-flex justify-space-between">
          <div>
            <img src="../assets/logobrand.png" width="75" height="35">
          </div>
          <div class="hide-on-mobile align-self-center">
            <ul class="d-flex ga-5">
              <li><a href="#about" class="fs-20 text--white cursor-pointer">About</a></li>
              <li><a href="#service" class="fs-20 text--white cursor-pointer">Our Service</a></li>
              <li><a href="#gallery" class="fs-20 text--white cursor-pointer">Gallery</a></li>
              <li><a href="#testimony" class="fs-20 text--white cursor-pointer">Testimony</a></li>
              <li><a href="#form" class="fs-20 text--white cursor-pointer">Form</a></li>
            </ul>
          </div>
          <div class="show-on-mobile">
            <div class="border-2px-white br-5px pr-1 pl-1 cursor-pointer" id="toggleBar">
              <i class="fa-solid fa-bars text--white"></i>
            </div>
          </div>
        </div>
      </section>
      <section id="navbar-mobile" class="show-on-mobile position-fixed w-100 bg-color-maincolor transition-06s border-t-md" style="z-index: 10000; top:62px; display:none;">
        <ul class="d-flex-col ga-5">
          <li class="ml-4 pt-2"><a href="#about" class="fs-20 text--white cursor-pointer">About</a></li>
          <li class="ml-4"><a href="#service" class="fs-20 text--white cursor-pointer">Our Service</a></li>
          <li class="ml-4"><a href="#gallery" class="fs-20 text--white cursor-pointer">Gallery</a></li>
          <li class="ml-4"><a href="#testimony" class="fs-20 text--white cursor-pointer">Testimony</a></li>
          <li class="ml-4 pb-2"><a href="#form" class="fs-20 text--white cursor-pointer">Form</a></li>
        </ul>
      </section>
      <!-- Home -->
      <section id="home" class="pt-16 pb-16 pl-2 pr-2" >
        <div class="container-dqa d-flex mb-16 " style="margin-top:250px;">
          <div class="grid-box-2 ">
            <v-col class="d-flex-col justify-center text--white"  v-motion-slide-left>
              <div class="pb-2">
                <span class="fs-16">WE WILL PROVIDE SOLUTIONS TO YOUR PROBLEMS</span>
              </div>
              <div class="pb-2">
                <span class="fs-48">Creative Digital Agency Company</span>
              </div>
              <div>
                <span class="fs-16">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut elit tellus, luctus nec ullamcorper mattis, pulvinar dapibus leo.</span>
              </div>
  
            </v-col>
          </div>
        </div>
      </section>
    </div>

    <!-- About -->
    <section id="about" class="pt-16 pb-16 pl-2 pr-2">
      <div class="container-dqa d-flex mt-16 pb-16">
        <div class="grid-box-2 ">
          <v-col class="text-align-center">
            <img class="img-fluid" src="../assets/about.png" height="800" width="500">
          </v-col>
          <v-col class="d-flex-col justify-center">
            <div class="pb-2">
              <span class="fs-16">WHAT WE CAN DO FOR YOU?</span>
            </div>
            <div class="pb-2">
              <span class="fs-48">About Us</span>
            </div>
            <div>
              <span class="fs-16">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut elit tellus, luctus nec ullamcorper mattis, pulvinar dapibus leo.</span>
            </div>
          </v-col>
        </div>
      </div>
    </section>

    <!--Service  -->
    <section id="service" class="pt-16 pb-16 bg-color-maincolor" >
      <div class="container-dqa d-flex-col">
        <div class="align-self-center">
          <span class="fs-48 text--white">Our Services</span>
        </div>
        <div class="text-align-center">
          <span class="fs-16 text--white">Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</span>
        </div>
        <div class="grid-box-3 pt-4" >
          <div class="border bg-white br-5px pa-5 cursor-pointer service-dqa">
            <div class="d-flex-col ga-3 align-items-center">
              <i class="fa-solid fa-crown fs-22"></i>
              <span class="fs-16">VIP TRAVEL PLANNING</span>
            </div>
            <div>
              <span class="fs-11">Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</span>
            </div>
          </div>
          <div class="border bg-white br-5px pa-5 cursor-pointer service-dqa">
            <div class="d-flex-col ga-3 align-items-center">
              <i class="fa-solid fa-people-group fs-22"></i>
              <span class="fs-16">GROUP TRAVEL</span>
            </div>
            <div>
              <span class="fs-11">Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</span>
            </div>
          </div>
          <div class="border bg-white br-5px pa-5 cursor-pointer service-dqa">
            <div class="d-flex-col ga-3 align-items-center">
              <i class="fa-solid fa-city fs-22"></i>
              <span class="fs-16">CORPORATE TRAVEL</span>
            </div>
            <div>
              <span class="fs-11">Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</span>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Gallery -->
    <section id="gallery" class="pt-16 pb-16">
      <div class="container-dqa">
        <div class="d-flex-col">
          <div class="align-self-center">
            <span class="fs-48 ">Gallery</span>
          </div>
          <div class="text-align-center">
            <span class="fs-16 ">Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</span>
          </div>
          <swiper
            :effect="'coverflow'"
            :grabCursor="true"
            :centeredSlides="true"
            :slidesPerView="'auto'"
            :coverflowEffect="{
              rotate: 20,
              stretch: 0,
              depth: 100,
              modifier: 1,
              slideShadows: true,
            }"
            :modules="modules"
            class="mySwiper"
            :initialSlide="initialSlide"
          >
            <swiper-slide>
              <img src="https://swiperjs.com/demos/images/nature-1.jpg" />
            </swiper-slide>
            <swiper-slide>
              <img src="https://swiperjs.com/demos/images/nature-2.jpg" />
            </swiper-slide>
            <swiper-slide>
              <img src="https://swiperjs.com/demos/images/nature-3.jpg" />
            </swiper-slide>
            <swiper-slide>
              <img src="https://swiperjs.com/demos/images/nature-4.jpg" />
            </swiper-slide>
            <swiper-slide>
              <img src="https://swiperjs.com/demos/images/nature-5.jpg" />
            </swiper-slide>
            <swiper-slide>
              <img src="https://swiperjs.com/demos/images/nature-6.jpg" />
            </swiper-slide>
            <swiper-slide>
              <img src="https://swiperjs.com/demos/images/nature-7.jpg" />
            </swiper-slide>
            <swiper-slide>
              <img src="https://swiperjs.com/demos/images/nature-8.jpg" />
            </swiper-slide>
          </swiper>
        </div>
      </div>
    </section>

    <!-- Testimony -->
    <section id="testimony" class="pt-16 pb-16">
      <div class="container-dqa">
        <swiper
          :slidesPerView="1"
          :spaceBetween="30"
          :loop="true"
          :pagination="{
            clickable: true,
          }"
          :navigation="true"
          :modules="modules"
          class="mySwiper"
        >
          <swiper-slide>
            <div class="d-flex-col align-items-center pl-16 pr-16">
              <div>
                <span class="fs-30 fw-500">What Travels Says</span>
              </div>
              <div class="d-flex text-align-center">
                <span>" Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."</span>
              </div>
              <div class="d-flex-col pt-2">
                <div>
                  <img src="../assets/testimony-1.png" width="100" height="113" style="border-radius: 50%;">
                </div>
                <div class="fs-20 align-self-center">Hamirza</div>
              </div>
            </div>
          </swiper-slide>
          <swiper-slide>
            <div class="d-flex-col align-items-center pl-16 pr-16">
              <div>
                <span class="fs-30 fw-500">What Travels Says</span>
              </div>
              <div class="d-flex text-align-center">
                <span>" Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."</span>
              </div>
              <div class="d-flex-col pt-2">
                <div>
                  <img src="../assets/testimony-2.png" width="100" height="113" style="border-radius: 50%;">
                </div>
                <div class="fs-20 align-self-center">Steven</div>
              </div>
            </div>
          </swiper-slide>
          <swiper-slide>
            <div class="d-flex-col align-items-center pl-16 pr-16">
              <div>
                <span class="fs-30 fw-500">What Travels Says</span>
              </div>
              <div class="d-flex text-align-center">
                <span>" Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."</span>
              </div>
              <div class="d-flex-col pt-2">
                <div>
                  <img src="../assets/testimony-3.png" width="100" height="113" style="border-radius: 50%;">
                </div>
                <div class="fs-20 align-self-center">Kevin</div>
              </div>
            </div>
          </swiper-slide>
        </swiper>
      </div>
    </section>

    <!-- Footer -->
    <div class="bg-navy-blue">
      <section class="pa-4">
        <div class="container-dqa">
          <div class="grid-box-3">
            <div class="d-flex-col">
              <div>
                <span class="fs-13 text--white fw-400">I am text block. Click edit button to change this text. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut elit tellus, luctus nec ullamcorper matti pibus leo.</span>
              </div>
            </div>
            <div>
              
            </div>
          </div>
        </div>
      </section>
    </div>
  </div>
</template>

<script>
import { Swiper, SwiperSlide } from 'swiper/vue';
import 'swiper/css';
import 'swiper/css/effect-coverflow';
import 'swiper/css/pagination';
import 'swiper/css/navigation';
import '../assets/root.css';
import { EffectCoverflow, Pagination,Navigation } from 'swiper/modules';

export default {
  name: 'HelloWorld',
  components: {
    Swiper,
    SwiperSlide,
  },
  data(){
    return{
      initialSlide: 4,
    }
  },
  setup() {
    return {
      modules: [EffectCoverflow, Pagination, Navigation],
    };
  },
  mounted(){
    var navbar = this.$el.querySelector("#navbar");
    var navbarMobile = this.$el.querySelector("#navbar-mobile");
    var toggleBars = this.$el.querySelector("#toggleBar")

    window.addEventListener("scroll", function(){
      navbar.classList.toggle("sticky-navbar",window.scrollY > 0)
      navbarMobile.classList.toggle("sticky-navbar",window.scrollY > 0)
      
    })
   
    toggleBars.addEventListener("click", function(){
      navbarMobile.style.display =(navbarMobile.style.display === 'none' || navbarMobile.style.display === '') ? 'block' : 'none';
    })

    var navbarMobileLinks = navbarMobile.querySelectorAll('li');
    navbarMobileLinks.forEach(function (link) {
      link.addEventListener('click', function () {
    
        navbarMobile.style.display = 'none';
      });
    });
  }
}

  

</script>