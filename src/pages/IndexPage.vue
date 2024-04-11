<template>
  <div>
    <div class="banner">
      <div class="header container">
        <div>
          <img height="22px" src="../assets/logo.png" />
        </div>
        <div>
          <div class="menu-list">
            <p>채용 <img src="../assets/Vector.png" /></p>
            <p>해외 개발자 활용 서비스</p>
          </div>
        </div>
        <div class="last-header-cal">
          <button class="btn-primary">문의하기</button>
        </div>
      </div>

      <div class="banner-body container">
        <div>
          <div class="text-with-flash-msg">
            <p class="flash-msg">FadeIn after title and subtitle shown</p>
            <!-- (delay 300ms) -->
            <div>
              <div class="box-arrow arrow-bottom">풀타임, 파트타임</div>
            </div>
          </div>

          <div class="text-with-flash-msg">
            <p class="flash-msg">FadeInUp(duration 500ms)</p>
            <h2 class="banner-bold-text">
              최고의 실력을 가진<br />
              외국인 인재를 찾고 계신가요?
            </h2>
          </div>
          <div class="text-with-flash-msg">
            <p class="flash-msg">FadeInUp(500ms)</p>
            <p class="text-flash-msg">
              법률 및 인사관리 부담없이 <br />
              1주일 이내에 원격으로 채용해보세요.
            </p>
          </div>
          <div class="text-with-flash-msg for-3-sec">
            <p
              class="text-flash-msg"
              style="
                border-bottom: 1px solid #ffffffe8;
                width: max-content;
                font-weight: 600;
                margin-top: 25px;
              "
            >
              개발자가 필요하신가요?
            </p>
          </div>
          <div class="text-with-flash-msg for-3-sec">
            <div class="flash-msg">fade in 3 at once(500ms)</div>
            <div class="text-flash-msg grid-msg">
              <div>
                <div class="hr" />
                <h5>평균 월 120만원</h5>
                <p>임금을 해당 국가를 기준<br />으로 계산합니다.</p>
              </div>
              <div>
                <div class="hr" />
                <h5>최대 3회 인력교체</h5>
                <p>막상 채용해보니 맞지 않<br />아도 걱정하지 마세요.</p>
              </div>
              <div>
                <div class="hr" />
                <h5>평균 3일, 최대 10일</h5>
                <p>
                  급하게 사람이 필요한 경<br />우에도 빠른 채용이 가능<br />합니다.
                </p>
              </div>
            </div>
          </div>
        </div>

        <div>
          <div class="text-with-flash-msg right-till">
            <p class="flash-msg">
              FadeIn after title and subtitle shown(delay 300ms)
            </p>
            <div>
              <div class="box-arrow arrow-bottom">
                <img src="../assets/icn_dollard.png" height="25px" /> 월 100만원
              </div>
            </div>
          </div>

          <swiper
            :slides-per-view="3"
            :space-between="50"
            @swiper="onSwiper"
            @slideChange="onSlideChange"
            style="max-width: 550px !important"
          >
            <swiper-slide>
              <div class="slide-card">
                <div class="slide-card-img">
                  <img class="profil-img" src="../assets/Ellipse.png" />
                  <img class="flag-img" src="../assets/icn_flag.png" />
                </div>
                <h4>Abhishek Gupta</h4>
                <p>마케팅 <b>· 2y+</b></p>
                <br />
                <div class="badge-in-card">마케팅 콘텐츠 제작</div>
                <div class="badge-in-card">인스타그램 관리</div>
                <div class="doble-badge-in-card">
                  <div class="badge-in-card">트위터 관리</div>
                  <div class="badge-in-card">블로그 글 작성</div>
                </div>
              </div>
            </swiper-slide>

            <!-- <swiper-slide>
              <div class="slide-card">
                <div class="slide-card-img">
                  <img class="profil-img" src="../assets/Ellipse.png" />
                  <img class="flag-img" src="../assets/icn_flag.png" />
                </div>
                <h4>Abhishek Gupta</h4>
                <p>마케팅 <b>· 2y+</b></p>
                <br />
                <div class="badge-in-card">마케팅 콘텐츠 제작</div>
                <div class="badge-in-card">인스타그램 관리</div>
                <div class="doble-badge-in-card">
                  <div class="badge-in-card">트위터 관리</div>
                  <div class="badge-in-card">블로그 글 작성</div>
                </div>
              </div>
            </swiper-slide> -->

            <!-- <swiper-slide>
              <div class="slide-card">
                <div class="slide-card-img">
                  <img class="profil-img" src="../assets/Ellipse.png" />
                  <img class="flag-img" src="../assets/icn_flag.png" />
                </div>
                <h4>Abhishek Gupta</h4>
                <p>마케팅 <b>· 2y+</b></p>
                <br />
                <div class="badge-in-card">마케팅 콘텐츠 제작</div>
                <div class="badge-in-card">인스타그램 관리</div>
                <div class="doble-badge-in-card">
                  <div class="badge-in-card">트위터 관리</div>
                  <div class="badge-in-card">블로그 글 작성</div>
                </div>
              </div>
            </swiper-slide> -->
          </swiper>
        </div>
      </div>

      <div class="banner-footer">
        <div class="left-slide-text" style="margin-left: 10px">
          <p>fadeIn(500ms)</p>
          <p style="width: max-content">
            Slides to the left by one every 5 seconds
          </p>
        </div>

        <div class="min-card-icn-text">
          <img src="../assets/icn_desk.png" />
          <p>해외 마케팅</p>
        </div>

        <div class="min-card-icn-text">
          <img src="../assets/icn_img.png" />
          <p>퍼블리셔</p>
        </div>

        <div class="min-card-icn-text">
          <img src="../assets/icn_box.png" />
          <p>캐드원(제도사)</p>
        </div>

        <div class="min-card-icn-text">
          <img src="../assets/icn_star.png" />
          <p>해외 세일즈</p>
        </div>

        <div class="min-card-icn-text">
          <img src="../assets/icn_call.png" />
          <p>해외 CS</p>
        </div>

        <div class="min-card-icn-text">
          <img src="../assets/icn_desk.png" />
          <p>해외 마케팅</p>
        </div>

        <div class="min-card-icn-text">
          <img src="../assets/icn_img.png" />
          <p>퍼블리셔</p>
        </div>
      </div>
    </div>

    <div class="home-body container">
      <div>
        <img src="../assets/logo-color.png" height="34px" />
        <p style="font-size: 15px; font-weight: 600; margin: 20px 0 15px 0">
          우리는 국가의 장벽을 넘어 최고의 인재를 <br />매칭해드립니다.
        </p>
        <b>010-0000-0000</b><br />
        <b>aaaaa@naver.com</b>

        <div class="text-two-side">
          <div>
            <p>상호명</p>
            <p>하이퍼하이어</p>
            <b>Hyperhire India Private Limited</b>
          </div>
          <div>
            <p>대표 CEO</p>
            <p>김주현</p>
            <b>Juhyun Kim</b>
          </div>
        </div>
      </div>
      <div class="for-body-card-list">
        <div class="body-card-list">
          <div class="body-card">
            <img height="40px" src="../assets/icn_code.png" />
            <p>해외 개발자 원격 채용</p>
            <span
              >바로가기
              <img height="20px" src="../assets/Arrow-Right-Square.png"
            /></span>
          </div>

          <div class="body-card">
            <img height="40px" src="../assets/icn_user.png" />
            <p>외국인 원격 채용 (비개발)</p>
            <span
              >바로가기
              <img height="20px" src="../assets/Arrow-Right-Square.png"
            /></span>
          </div>

          <div class="body-card">
            <img height="40px" src="../assets/icn_kor.png" />
            <p>한국어 가능 외국인 채용</p>
            <span
              >바로가기
              <img height="20px" src="../assets/Arrow-Right-Square.png"
            /></span>
          </div>

          <div class="body-card">
            <img height="40px" src="../assets/icn_setting.png" />
            <p>해외 개발자 활용 서비스</p>
            <span
              >바로가기
              <img height="20px" src="../assets/Arrow-Right-Square.png"
            /></span>
          </div>
        </div>
        <div class="body-detail">
          <div>
            <p>사업자등록번호 CIN</p>
            <p>427-86-01187</p>
            <p>U74110DL2016PTC290812</p>
          </div>
          <div>
            <p>주소 ADDRESS</p>
            <p>서울특별시 강남대로 479, 지하 1층 238호</p>
            <p>
              D-138, Street number 11, Jagjeet Nagar, North East Delhi, New
              Delhi, <br />
              110053 India
            </p>
          </div>
        </div>
      </div>

      <div
        style="
          margin-top: 20px;
          font-weight: 800;
          font-size: 14px;
          color: #555555;
        "
      >
        ⓒ 2023 Hyperhire
      </div>
    </div>
  </div>
</template>

<script>
import { Swiper, SwiperSlide } from "swiper/vue";
import "swiper/css";
export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    const onSwiper = (swiper) => {
      console.log(swiper);
    };
    const onSlideChange = () => {
      console.log("slide change");
    };
    return {
      onSwiper,
      onSlideChange,
    };
  },
};
</script>
