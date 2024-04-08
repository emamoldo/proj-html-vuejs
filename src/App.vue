<script>
</script>

<template>
  <!-- FontAwesome Cdn -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"
    integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA=="
    crossorigin="anonymous" referrerpolicy="no-referrer" />

  <!-- Header Section -->
  <!-- REMEMBER: Add the < /> for the Header, the Main and the Footer -->
  <div class="header">
    <img class="logo" src="/src/assets/img/logo.png" alt="">

    <div class="utilities">
      <a href="#">Home</a>
      <a href="#">Apple</a>
      <a href="#">Microsoft</a>
      <a href="#">Android</a>
      <a href="#">Forums</a>
      <a href="#">Contact Us</a>
      <button class="header_btn" type="button">Join Us</button>
      <i class="fa-solid fa-magnifying-glass"></i>
    </div>
  </div>

  <!-- Main 1st Section -->
  <div class="main">
    <div class="main_container">
      <div class="main_text">
        <h2>Tech Forum!</h2>
        <p>Discuss all the latest technology news and trands</p>
        <button class="get_sign" type="button">GET AVADA NOW! ></button>
      </div>
    </div>
  </div>

  <div id="main_container">
    <div id="main_text">
      <h4>AVADA FORUM IS THE PLACE TO BE</h4>
      <p id="title_text">In quis lectus leo elementum faucibus in depibus dictum. Nulla molestie tortor nec lectus
        venenatis, sed blandit dui finibus, dolor at, bibendum purus. Donec vehicula nec tortor ac finibus.</p>
    </div>
  </div>

  <!-- Main 2nd Section -->
  <div class="latest_news">
    <p id="eget">PHASELLUS EGET METUS</p>
    <strong id="latest_title">All the latest news</strong>

    <div class="card">
      <div class="first">
        <img class="first_img" src="/src/assets/img/post_feat_img_25-320x202.jpg" alt="">
        <strong class="img_title">Morbi vitae dui euismod vulputate sollicitudin</strong>
        <p class="date_comments">October 11th, 2015 | <strong>2 Comments</strong></p>
        <p class="img_text">Donec finibus sit amet orci eger ultricies. Praesent posuere ante ut erat fringilla,
          vestibulum placerat metus mattis. Aenean dictum vitae nisl</p>
      </div>

      <div class="second">
        <img class="second_img" src="/src/assets/img/post_feat_img_24-320x202.jpg" alt="">
        <strong class="img_title">Vivamus pellenteque, felis quis varius</strong>
        <p class="date_comments">October 11th, 2015 | Comments Off</p>
        <p class="img_text">Donec finibus sit amet orci eger ultricies. Praesent posuere ante ut erat fringilla,
          vestibulum placerat metus mattis. Aenean dictum vitae nisl</p>
      </div>

      <div class="third">
        <img class="third" src="/src/assets/img/post_feat_img_23-320x202.jpg" alt="">
        <strong class="img_title">Donec ornare pretium eget scelisque justo</strong>
        <p class="date_comments">October 11th, 2015 | Comments Off</p>
        <p class="img_text">Donec finibus sit amet orci eger ultricies. Praesent posuere ante ut erat fringilla,
          vestibulum placerat metus mattis. Aenean dictum vitae nisl</p>
      </div>
    </div>

    <!-- Featured Article Section -->
    <div class="featured_article">
      <div class="featured_text">
        <p>FEATURED ARTICLE</p>
        <strong>Cras malesuada et orci eget pharetra</strong>
        <p>In quis lectus sed leo elementum facibus in dapibus dictum. Nullamolestie tortor nec lectus venenatis, sed
          blandit dui, dolor at bibendum sadips ets ipsums dolores ficilis uns leo lectus.</p>
        <button class="read_more" type="button">READ MORE ></button>
      </div>
    </div>

    <div class="card_container">
      <div class="card">
        <div class="first">
          <img class="first_img" src="/src/assets/img/post_feat_img_22-320x202.jpg" alt="">
          <strong class="img_title">Morbi vitae dui euismod vulputate sollicitudin</strong>
          <p class="date_comments">October 11th, 2015 | Comments Off</p>
          <p class="img_text">Donec finibus sit amet orci eger ultricies. Praesent posuere ante ut erat fringilla,
            vestibulum placerat metus mattis. Aenean dictum vitae nisl</p>
        </div>

        <div class="second">
          <img class="second_img" src="/src/assets/img/post_feat_img_21-320x202.jpg" alt="">
          <strong class="img_title">Morbi vitae dui euismod vulputate sollicitudin</strong>
          <p class="date_comments">October 11th, 2015 | Comments Off</p>
          <p class="img_text">Donec finibus sit amet orci eger ultricies. Praesent posuere ante ut erat fringilla,
            vestibulum placerat metus mattis. Aenean dictum vitae nisl</p>
        </div>

        <div class="third">
          <img class="third_img" src="/src/assets/img/post_feat_img_20-320x202.jpg" alt="">
          <strong class="img_title">Morbi vitae dui euismod vulputate sollicitudin</strong>
          <p class="date_comments">October 11th, 2015 | Comments Off</p>
          <p class="img_text">Donec finibus sit amet orci eger ultricies. Praesent posuere ante ut erat fringilla,
            vestibulum placerat metus mattis. Aenean dictum vitae nisl</p>
        </div>
      </div>
    </div>

  </div>

  <!-- Reviewed Section -->
  <div class="reviewed">
    <div class="reviewed_product">
      <div class="reviewed_text">
        <p>REVIEWED PRODUCT</p>
        <strong>Mauris viverra atisan ipsum eget felis prims efficitur varius</strong>
        <p>In quis lectus sed leo elementum facibus in dapibus dictum. Nullamolestie tortor nec lectus venenatis, sed
          blandit dui, dolor at bibendum sadips ets ipsums dolores ficilis uns leo lectus.</p>
        <button class="read_more" type="button">READ MORE ></button>
      </div>

    </div>

    <!-- Tutorial Section -->
    <div class="tutorial">
      <strong>Tutorials & Guides</strong>
      <hr>

      <div class="little_cards">
        <img src="/src/assets/img/post_feat_img_23-177x142.jpg" alt="">
        <div class="cards_text">
          <strong>Donec ornare pretium eget scelique justo</strong>
          <p class="date_comments">October 11th, 2015 | Comments Off</p>
        </div>
      </div>

      <div class="little_cards">
        <img src="/src/assets/img/post_feat_img_22-177x142.jpg" alt="">
        <div class="cards_text">
          <strong>Donec ornare pretium eget scelique justo</strong>
          <p class="date_comments">October 11th, 2015 | Comments Off</p>
        </div>
      </div>

      <div class="little_cards">
        <img src="/src/assets/img/post_feat_img_20-177x142.jpg" alt="">
        <div class="cards_text">
          <strong>Donec ornare pretium eget scelique justo</strong>
          <p class="date_comments">October 11th, 2015 | Comments Off</p>
        </div>
      </div>
    </div>
  </div>

  <!-- Blog Section -->
  <div class="blog">
    <a href="#">READ OUR BLOG <i class="fa-solid fa-arrow-right"></i></a>
  </div>

  <!-- Main 3rd Part -->
  <div class="forum">
    <p id="eget">PHASELLUS EGET METUS</p>
    <strong>Forum Sections</strong>

    <div class="sections">
      <div class="first_sections">
        <div class="sections_card">
          <i class="fa-solid fa-file-lines"></i>
          <strong>News & Community</strong>
        </div>

        <div class="sections_card">
          <i class="fa-brands fa-apple"></i>
          <strong>Apple Forum</strong>
        </div>

        <div class="sections_card">
          <i class="fa-brands fa-windows"></i>
          <strong>Microsoft Forum</strong>
        </div>

        <div class="sections_card">
          <i class="fa-brands fa-android"></i>
          <strong>Android Forum</strong>
        </div>
      </div>

      <div class="second_sections">
        <div class="sections_card">
          <i class="fa-solid fa-mug-saucer"></i>
          <strong>General Discussion</strong>
        </div>

        <div class="sections_card">
          <i class="fa-solid fa-cubes"></i>
          <strong>Apps & Software</strong>
        </div>

        <div class="sections_card">
          <i class="fa-solid fa-laptop"></i>
          <strong>Gadgets & Stuff</strong>
        </div>

        <div class="sections_card">
          <i class="fa-solid fa-wrench"></i>
          <strong>Tutorials & Guides</strong>
        </div>
      </div>
    </div>
  </div>

  <!-- Forum Section -->
  <div class="blog_forum">
    <a href="#">READ OUR FORUM <i class="fa-solid fa-arrow-right"></i></a>
  </div>

  <!-- Footer Section -->
  <div class="footer">
    <div class="footer_text">
      <strong>Hey! Join to our Community</strong>
      <p>Nulla molestie tortor nec lectus venenatis, sed blandit dui finibus. Curabitur feugiat volputate parus ipsum
        dolores ficilis uns etra.</p>
      <button class="get_sign" type="button">SIGN UP ></button>
    </div>
  </div>

  <!-- Newsletter Section -->
  <div class="newsletter">
    <p>Subscribe to uor Newsletter</p>
    <div class="newsletter_utilities">
      <input type="text" placeholder="Insert your email*">
      <button type="button">SEND</button>
    </div>
  </div>

  <!-- About Section -->
  <div class="about">
    <div class="container">
      <div class="about_section">
        <strong>AVADA TECH FORUM</strong>
        <p>Sed semper, nisl id feugiat eleifend, erat est digssin felis, quis auctor elit enim nec ante. Cras et nibh
          risus. Pellentesque non mi sit amet mi intermentum.</p>
      </div>

      <div class="about_section">
        <strong>POPULAR TOPICS</strong>
        <p><i class="fa-solid fa-angle-right"></i> Nam a dolor volutpat massa auctor semper </p>
        <p><i class="fa-solid fa-angle-right"></i> Sed eusmod nusc urna fermentum arcu dapibus fringilla. </p>
        <p><i class="fa-solid fa-angle-right"></i> Cras lacinia tellus id mauris finibus iacus molestie </p>
        <p><i class="fa-solid fa-angle-right"></i> Curabitur a scelerisque ligula</p>
      </div>

      <div class="about_section">
        <strong>RECENT TOPICS</strong>
        <p><i class="fa-solid fa-angle-right"></i> Cras lacinia tellus id mauris finibus iacus molestie </p>
        <p><i class="fa-solid fa-angle-right"></i> Proin at ligula sagittis vestibulum nusu vitae </p>
        <p><i class="fa-solid fa-angle-right"></i> Sed nec metus at est tincidont elementum </p>
        <p><i class="fa-solid fa-angle-right"></i> Nulla egestas nulla eu nulla suscipit molestie</p>
      </div>

      <div class="about_section">
        <strong>LATEST REPLIES</strong>
        <p><i class="fa-solid fa-angle-right"></i> Cras lacinia tellus id mauris finibus iacus molestie </p>
        <p><i class="fa-solid fa-angle-right"></i> Cras lacinia tellus id mauris finibus iacus molestie </p>
        <p><i class="fa-solid fa-angle-right"></i> Nulla egestas nulla eu nulla suscipit molestie </p>
        <p><i class="fa-solid fa-angle-right"></i> Mauris ac nibh quis eros sagittis lacinia a et dui</p>
      </div>
    </div>
  </div>
  <br>
  <hr>

  <!-- Copyright Section -->
  <div class="copy">
    <p><i class="fa-regular fa-copyright"></i> Copyright 2012 - 2020 | Avada Theme by <strong>Theme Fusion</strong> |
      All Rights Reserved | Powered by <strong>WordPress</strong></p>
    <div class="icons">
      <i class="fa-brands fa-facebook-f"></i>
      <i class="fa-brands fa-twitter"></i>
      <i class="fa-brands fa-instagram"></i>
      <i class="fa-brands fa-youtube"></i>
    </div>
  </div>
</template>

<style>
/* Color Palette */
* {
  margin: 0;
  padding: 0;
}

:root {
  --bool-bg-header: #28AFC3;
  --bool-bg-main-container: #FFFFFF;
  --bool-text-btn: #191919;
  --bool-forum-card: #FF8D61;
  --bool-text-primary: #F2F2F2;
  --bool-darker: #707070;
  --bool-first-section-title: #565656;
  --bool-first-section-text: #a3a3a3;
  --bool-white: #FFFFFF;
}

/* Header Section */
.header {
  background-color: var(--bool-bg-header);
  align-items: center;
  display: flex;
  justify-content: space-around;
  padding: 1rem;

  .utilities {
    display: flex;
    color: var(--bool-white);
    gap: 2rem;
    align-items: center;

    a {
      text-decoration: none;
      color: var(--bool-white);
    }

    .header_btn {
      background-color: var(--bool-text-btn);
      color: var(--bool-white);
      border: none;
      padding: 0.5rem;
    }
  }
}

/* Main 1st Section */
.main {
  background-image: url("../src/assets/img/home_slider_bg.jpg");
  height: 870px;

  .main_container {
    padding: 15rem;
    color: var(--bool-white);

    .main_text {
      gap: 2rem;
      display: flex;
      flex-direction: column;

      h2 {
        font-size: 100px;
      }

    }
  }
}

.get_sign {
  width: 150px;
  padding: 0.5rem;
  background-color: var(--bool-bg-header);
  color: var(--bool-white);
  border: none;
}

#main_container {
  height: 250px;
  background-color: var(--bool-text-primary);

  #main_text {
    padding: 5rem;
    text-align: center;
    align-items: center;
    display: flex;
    flex-direction: column;
    gap: 1.5rem;

    h4 {
      color: var(--bool-first-section-title);
    }

    #title_text {
      color: var(--bool-first-section-text);
      width: 380px;
    }

  }
}

/* Main 2nd Section */
.latest_news {
  padding: 3rem;
  text-align: center;
  align-items: center;
  display: flex;
  flex-direction: column;
  gap: 1.5rem;

  #latest_title {
    font-size: 30px;
    border-bottom: 3px solid orange;
  }

  .card_container {
    padding-top: 2rem;
  }

  .card {
    width: 1700px;
    display: flex;
    justify-content: center;
    gap: 2rem;
    padding-bottom: 2rem;

    .first,
    .second,
    .third {
      /* padding-top: 2rem; */
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      gap: 0.5rem;

      .img_text {
        text-align: left;
        width: 320px;
        color: var(--bool-first-section-text);
      }
    }

  }
}

#eget {
  /* color: var(--bool-first-section-title); */
  color: black;
  font-size: 13px;
}


.date_comments {
  color: var(--bool-first-section-text);

  strong {
    color: black;
  }
}

/* Featured Article Section */
.featured_article {
  background-image: url("../src/assets/img/featured_article_1_bg.jpg");
  background-size: 100%;
  max-width: 1025px;
  height: 500px;

  .featured_text {
    display: flex;
    align-items: flex-start;
    flex-direction: column;
    gap: 1.5rem;
    padding: 13rem 5rem;

    strong {
      color: var(--bool-white);
      font-size: 25px;
    }

  }
}

p {
  color: white;
  text-align: left;
}

.read_more {
  background-color: var(--bool-text-btn);
  color: var(--bool-white);
  border: none;
  padding: 1rem;
}

/* Reviewed Section */
.reviewed {
  display: flex;
  gap: 3rem;
}

.reviewed_product {
  background-image: url("../src/assets/img/featured_article_2_bg.jpg");
  background-size: 100%;
  width: 600px;
  height: 400px;
  margin-left: 26rem;

  .reviewed_text {
    display: flex;
    align-items: flex-start;
    flex-direction: column;
    gap: 1.5rem;
    padding: 6rem 5rem;

    strong {
      color: var(--bool-white);
      font-size: 25px;
    }
  }
}

/* Tutorial Section */
.tutorial {

  display: flex;
  flex-direction: column;
  gap: 1rem;

  .little_cards {
    display: flex;
    gap: 1rem;

    img {
      height: 100px;
    }

    .cards_text {
      display: flex;
      flex-direction: column;
      gap: 0.5rem;

      strong {
        width: 180px;
      }
    }
  }
}

/* Blog Section */
.blog {
  display: flex;
  align-items: center;
  margin-top: 5rem;
  height: 75px;
  justify-content: center;
  text-align: center;
  background-color: black;

  a {
    text-decoration: none;
    color: var(--bool-white);
  }
}

/* 3rd Main Section */
.forum {
  background-color: var(--bool-text-primary);
  padding: 3rem;
  text-align: center;
  align-items: center;
  display: flex;
  flex-direction: column;
  gap: 1.5rem;

  strong {
    border-bottom: 3px solid orange;
  }
}


.first_sections,
.second_sections {
  gap: 2rem;
  display: flex;
  margin-bottom: 2rem;

  .sections_card {
    height: 120px;
    width: 150px;
    border-top: 2px solid #28AFC3;
    background-color: var(--bool-white);
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 1rem;

    i {
      /* color: var(--bool-white); */
      font-size: 25px;
      border: 1px solid orange;
      border-radius: 50%;
    }

    strong {
      border: none;
    }
  }
}

/* Forum Section */
.blog_forum {
  display: flex;
  align-items: center;
  height: 75px;
  justify-content: center;
  text-align: center;
  background-color: black;

  a {
    text-decoration: none;
    color: var(--bool-white);
  }
}

/* Footer Section */
.footer {
  background-image: url("../src/assets/img/join_now_cta_bg.jpg");
  background-size: 100%;
  height: 550px;

  .footer_text {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding-top: 10rem;
    gap: 2rem;

    strong {
      color: var(--bool-white);
      font-size: 35px;
      width: 250px;
      text-align: center;
    }

    p {
      width: 550px;
      text-align: center;
    }
  }
}

/* Newsletter Section */
.newsletter {
  background-color: var(--bool-text-primary);
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 1rem;
  height: 150px;

  p {
    margin-top: 2rem;
    color: black;
    font-size: 20px;
  }

  .newsletter_utilities {
    display: flex;
    gap: 1rem;

    input {
      height: 25px;
      width: 400px;
    }

    button {
      width: 150px;
      padding: 0.5rem;
      background-color: black;
      color: var(--bool-white);
      border: none;
    }

  }


}

/* About Section */
.about {
  .container {
    margin-top: 5rem;
    margin-left: 24rem;
    display: flex;
    justify-content: space-between;
    width: 1100px;

    .about_section {
      display: flex;
      flex-direction: column;
      gap: 1rem;
      width: 250px;
      padding-bottom: 2rem;

      p {
        color: black;
        padding: 0.5rem 0;
        border-bottom: 1px solid var(--bool-darker);
      }
    }
  }
}

/* Copyright Section */
.copy {
  margin-top: 2rem;
  margin-left: 15rem;
  margin-right: 15rem;
  display: flex;
  justify-content: space-between;
  margin-bottom: 2rem;

  .icons {
    display: flex;
    gap: 2rem;
  }

  p {
    color: black;
  }
}
</style>