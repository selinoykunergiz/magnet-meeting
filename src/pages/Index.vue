<template>
  <Layout>
    <!-- Learn how to use images here: https://gridsome.org/docs/images -->
    <!--  
    <g-image alt="Example image" src="../img/favicon.png" width="135" />

    <h1>Hello, world!</h1>

    <p>
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Pariatur excepturi labore tempore expedita, et iste tenetur suscipit explicabo! Dolores, aperiam non officia eos quod asperiores
    </p>

    <p class="home-links">
      <a href="https://gridsome.org/docs/" target="_blank" rel="noopener">Gridsome Docs</a>
      <a href="https://github.com/gridsome/gridsome" target="_blank" rel="noopener">GitHub</a>
    </p>
    -->

    <div class="all-project">
      <div class="all-project-sections">

        <div class="section-navbar">

          <div class="header">
            <div class="header-logo">
              <img src="../img/logo.png" />
            </div>
              <p>Takeda Q12020 Earnings Call</p>
          </div>

          <div class="btn-header">
            <div>
              <button>Go Live</button>
            </div>
          </div>

          <div class="groups"> 
            <div>
              <button><img src="../img/group1.png" /></button>
            </div>
            <div>
              <button><img src="../img/group2.png" /></button>
            </div>
            <div>
              <button><img src="../img/group3.png" /></button>
            </div>
            <div>
              <button><img src="../img/group4.png" /></button>
            </div>
          </div>

          <div class="line">
            <div>
              <button><img src="../img/line.png" /></button>
            </div>
          </div>

        </div>

         <div class="section-strides">
           <img src="../img/home-img.png" />
        </div>

        <div class="section-footer">
          <div class="footer-img">
            <img src="../img/home-woman.png" />
            <img src="../img/home-man.png" />
            <img src="../img/home-man1.png" />
          </div>
          <div class="footer-social">
            <div>
              <ul class="social-list">
                <li>
                  <button><img src="../img/info.png" /><p>Settings</p></button>
                  
                </li>
                <li>
                  <button><img src="../img/vector.png" /><p class="mute">Mute</p></button>
                </li>
                <li>
                  <button><img src="../img/videocam.png" /><p>Stop Video</p></button>
                </li>
                <li>
                  <button class="active-green"><img src="../img/tv.png" /><p class="active-green">Share Screen</p></button>
                  
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
      <div class="all-project-section-two">
          <div class="section-chat">
           <ul class="chat-list">
             <li class="lists"><button>Chat</button></li>
             <li class="lists active"><button>People</button></li>
             <li class="lists"><button>Speakers</button></li>
           </ul>
          </div>

          <div class="section-attendies">
            <ul>
              <li><button class="active">Attendies</button></li>
              <li><button>Presenters</button></li>
            </ul>
          </div>

          <div class="section-people">
            <ul class="list-people">
              <li>
                <div class="general-list-people">

                  <div class="green"><p>CA</p></div>

                  <div class="name-content"><p>Cem Evren Ateş (Host)</p></div>

                  <div class="general-end">
                    <div class="info"><img src="../img/info.png" /></div>
                    <div class="videocam"><img src="../img/videocam.png" /></div>
                    <div class="more"><p>More</p><img src="../img/ok.svg" /></div>
                  </div>

                </div>
              </li>

               <li>
                <div class="general-list-people">

                  <div class="lilac"><p>SU</p></div>

                  <div class="name-content"><p>Serbay Üresin</p></div>

                  <div class="general-end">
                    <div class="info"><img src="../img/info.png" /></div>
                    <div class="videocam"><img src="../img/videocam.png" /></div>
                    <div class="more"><p>More</p><img src="../img/ok.svg" /></div>
                  </div>

                </div>
              </li>

               <li>
                <div class="general-list-people">

                  <div class="blue"><p>CA</p></div>

                  <div class="name-content"><p>Can Ateş</p></div>

                  <div class="general-end">
                    <div class="info"><img src="../img/info.png" /></div>
                    <div class="videocam"><img src="../img/videocam.png" /></div>
                    <div class="more"><p>More</p><img src="../img/ok.svg" /></div>
                  </div>

                </div>
              </li>

               <li>
                <div class="general-list-people">

                  <div class="pink"><p>EB</p></div>

                  <div class="name-content"><p>Emel Bakırtaş</p></div>

                  <div class="general-end">
                    <div class="info"><img src="../img/info.png" /></div>
                    <div class="videocam"><img src="../img/videocam.png" /></div>
                    <div class="more"><p>More</p><img src="../img/ok.svg" /></div>
                  </div>

                </div>
              </li>

               <li>
                <div class="general-list-people">

                  <div class="yellow"><p>SA</p></div>

                  <div class="name-content"><p>Şebnem Atasayar</p></div>

                  <div class="general-end">
                    <div class="info"><img src="../img/info.png" /></div>
                    <div class="videocam"><img src="../img/videocam.png" /></div>
                    <div class="more"><p>More</p><img src="../img/ok.svg" /></div>
                  </div>

                </div>
              </li>

            </ul>
          </div>

      </div>
    </div>

  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Hello, world!",
  },
};
</script>

<style>
/* .home-links a {
  margin-right: 1rem;
} */

.general-list-people, .general-end, .general-end .more{
  display: flex;
}

@font-face {
    font-family: 'HelveticaNeue';
    src: url('../font/HelveticaNeueMedium.woff2') format('woff2'),
        url('../font/HelveticaNeueMedium.woff') format('woff');
    font-weight: 500;
    font-style: normal;
    font-display: swap;
} 


html{
  height: 100%;
  font-size: 14px;
  font-family: 'HelveticaNeue';

}

body{
  background: #222222;
  margin: 0;
}

.all-project {
  width: 100%;
}

.header{
  display: flex;
  width: 70%;
}

.header p {
  color: white;
  line-height: 24px;
  padding: 0;
  margin: 0;
  display: flex;
  align-items: center;
  margin-left: 1%;
}

.header-logo img{
  width: 80px;
  height: 29px;
}

.header-logo {
  height: 45px;
  background: white;
  display: flex;
  align-items: center;
  border-radius: 5px;
}

.section-navbar {
  width: 100%;
  padding-top: 20px;
  display: flex;
  justify-content: space-between;
}

.btn-header button {
  background: #35DB9F;
  color: white;
  border: 1px solid #35DB9F;
  padding: 5px 13px;
  border-radius: 5px;
}

.btn-header {
  width: 10%;
  text-align: center;
  align-self: center;
}
.section-strides {
  margin-top: 12px;
}

.section-strides img {
  width: 100%;
  border-radius: 5px;
}

.footer-img img {
  border-radius: 5px;
  margin-right: 5px;
}

.social-list {
  display: flex;
  width: 100%;
  list-style: none;
  justify-content: center;
  padding: 0;
  align-items: center;
}

.footer-social {
  padding: 1px 10px;
  width: 30%;
  background: rgba(255, 255, 255, 0.1);
  border-radius: 56px;
  margin: 0 auto;
  margin-top: 17px;
}

.footer-social ul li button, .chat-list .lists button, .groups div button {
  border: none;
  background: transparent;
}

.footer-social ul li p {
 font-size: 12px;
 margin: 0;
 text-align: center;
 color: white;
}

.footer-social ul li {
 margin-right: 20px;
}

.footer-img{
  text-align: center;
}

.all-project-sections{
  width: 72%;
}

.all-project-section-two{
  width: 28%;
  background: rgba(255, 255, 255, 0.08);
}

.all-project{
  display: flex;
}

.lists button{
  color: #FFFFFF;
  line-height: 24px;
  padding: 8px 35px;
}

.chat-list .active button{
 color:#559CFF;
 border-bottom: 2px solid #559CFF;
}

.section-attendies .active {
  background: #0065F2;
}

.chat-list, 
.section-attendies ul {
  display: flex;
  list-style: none;
  padding: 0;
}

.section-attendies ul{
  justify-content: center;
}

.section-attendies ul li button{
  color: white;
  padding: 8px 24px;
  line-height: 14px;
  background: transparent;
  border: 1px solid rgba(255, 255, 255, 0.2);
}

.section-attendies ul li:first-child button{
  border-radius: 4px 0px 0px 4px;
}
.section-attendies ul li:last-child button{
  border-radius: 0 4px 4px 0;
}

.list-people{
  list-style: none;
}

.list-people li{
  width: 100%;
}

.general-list-people .green, .lilac ,.blue, .pink, .yellow{
  width: 10%;
  height: 10%;
  background: #76FFDE;
  border-radius: 50%;
  color: rgba(255, 255, 255, 0.8);
}

.general-list-people .green p, .general-list-people .lilac p , .general-list-people .blue p , .general-list-people .pink p ,.general-list-people .yellow p{
  font-size: 14.4px;
  line-height: 19px;
  text-align: center;
}

.general-list-people .name-content{
  width: 35%; 
  margin-left: 8px;
}
.general-list-people .name-content p {
  line-height: 24px;
  color: #FFFFFF;
}

.general-list-people .general-end{
  width: 55%;
  justify-content: center;
  align-items: center;
}

.videocam , .info {
  margin-right: 8px;
}

.more p {
  color: white;
  font-size: 12px;
  line-height: 24px;
  margin-right: 3px;
}

.info img {
  width: 24px;
  height: 24px;
}

.videocam img{
  width: 20px;
  height: 20px;
} 

.general-list-people .lilac {
  background: rgba(195, 118, 255, 0.5);
}

.general-list-people .blue {
  background: rgba(0, 101, 242, 0.5);
}

.general-list-people .pink {
  background: rgba(255, 118, 118, 0.5);
}

.general-list-people .yellow {
  background: rgba(255, 249, 95, 0.5);
}

.general-list-people {
  margin-bottom: 10px;
}

.groups {
  width: 20%;
  display: flex;
  background: rgba(255, 255, 255, 0.1);
  border-radius: 5px;
  justify-content: center;
  padding: 13px 2px;
  margin-right: 19px;
}

.groups div img {
  margin-right: 6px;
}

.line {
  align-self: center;
}

.line div button {
  border: none;
  background: rgba(255, 255, 255, 0.1);
  padding: 15px 15px;
  border-radius: 5px;
  margin-right: 5px;
}

.social-list .mute {
  padding-top: 5px;
}

.social-list .active-green{
  color: #35DB9F;
}
</style>
