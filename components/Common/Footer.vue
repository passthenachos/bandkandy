<template>
  <footer :class="`${!hideBGCOLOR ? 'sub-bg' : ''}`">
    <div class="container">
      <div class="row">
        <div class="col-lg-4">
          <div class="item md-mb50">
            <div class="title">
              <h5>Contact Us</h5>
            </div>
            <ul>
              <li>
                <span class="icon pe-7s-map-marker"></span>
                <div class="cont">
                  <h6>Officeal Address</h6>
                  <p>504 White St . Dawsonville, GA 30534 , New York</p>
                </div>
              </li>
              <li>
                <span class="icon pe-7s-mail"></span>
                <div class="cont">
                  <h6>Email Us</h6>
                  <p>support@gmail.com</p>
                </div>
              </li>
              <li>
                <span class="icon pe-7s-call"></span>
                <div class="cont">
                  <h6>Call Us</h6>
                  <p>+87986451666</p>
                </div>
              </li>
            </ul>
          </div>
        </div>
        <div class="col-lg-4">
          <div class="item md-mb50">
            <div class="title">
              <h5>Recent News</h5>
            </div>
            <ul>
              <li>
                <div class="img">
                  <a href="#">
                    <img src="/img/blog/1.jpg" alt="" />
                  </a>
                </div>
                <div class="sm-post">
                  <a href="#">
                    <p>
                      The Start-Up Ultimate Guide to Make Your WordPress
                      Journal.
                    </p>
                    <span class="date">14 sep 2023</span>
                  </a>
                </div>
              </li>
              <li>
                <div class="img">
                  <a href="#">
                    <img src="/img/blog/2.jpg" alt="" />
                  </a>
                </div>
                <div class="sm-post">
                  <a href="#">
                    <p>
                      The Start-Up Ultimate Guide to Make Your WordPress
                      Journal.
                    </p>
                    <span class="date">14 sep 2023</span>
                  </a>
                </div>
              </li>
              <li>
                <div class="subscribe">
                  <input type="text" placeholder="Type Your Email" />
                  <span class="subs pe-7s-paper-plane"></span>
                </div>
              </li>
            </ul>
          </div>
        </div>
        <div class="col-lg-4">
          <div class="item">
            <div class="logo">
              <img ref="lr" style="width: 140px;" src="https://firebasestorage.googleapis.com/v0/b/amber2641.appspot.com/o/Bandkandy%20LogoTransparency.png?alt=media&token=1f7e9f56-d410-482a-a883-e3785241e16e" alt="logo" />
            </div>
            <div class="social">
              <a href="#0">
                <i class="fab fa-facebook-f"></i>
              </a>
              <a href="#0">
                <i class="fab fa-twitter"></i>
              </a>
              <a href="#0">
                <i class="fab fa-instagram"></i>
              </a>
              <a href="#0">
                <i class="fab fa-youtube"></i>
              </a>
            </div>
            <div class="copy-right">
              <p>
                © 2023, BandKandy, LLC.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script setup>
const { hideBGCOLOR } = defineProps(['hideBGCOLOR']);
</script>