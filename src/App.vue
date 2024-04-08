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
      <p>Home</p>
      <p>Apple</p>
      <p>Microsoft</p>
      <p>Android</p>
      <p>Forums</p>
      <p>Contact Us</p>
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
      <p id="title_text">In quis lectus leo elementum faucibus in depibus dictum. Nulla molestie tortor nec lectus venenatis, sed blandit dui finibus, dolor at, bibendum purus. Donec vehicula nec tortor ac finibus.</p>
    </div>
  </div>

  <!-- Main 2nd Section -->
  <div class="latest_news">
    <p id="eget">PHASELLUS EGET METUS</p>
    <strong id="latest_title">All the latest news</strong>
    <hr>

    <div class="card">
      <div class="first">
        <img class="first_img" src="/src/assets/img/post_feat_img_25-320x202.jpg" alt="">
        <strong class="img_title">Morbi vitae dui euismod vulputate sollicitudin</strong>
        <p class="date_comments">October 11th, 2015 | <strong>2 Comments</strong></p>
        <p class="img_text">Donec finibus sit amet orci eger ultricies. Praesent posuere ante ut erat fringilla, vestibulum placerat metus mattis. Aenean dictum vitae nisl</p>
      </div>

      <div class="second">
        <img class="second_img" src="/src/assets/img/post_feat_img_24-320x202.jpg" alt="">
        <strong class="img_title">Morbi vitae dui euismod vulputate sollicitudin</strong>
        <p class="date_comments">October 11th, 2015 | Comments Off</p>
        <p class="img_text">Donec finibus sit amet orci eger ultricies. Praesent posuere ante ut erat fringilla, vestibulum placerat metus mattis. Aenean dictum vitae nisl</p>
      </div>

      <div class="third">
        <img class="third" src="/src/assets/img/post_feat_img_23-320x202.jpg" alt="">
        <strong class="img_title">Morbi vitae dui euismod vulputate sollicitudin</strong>
        <p class="date_comments">October 11th, 2015 | Comments Off</p>
        <p class="img_text">Donec finibus sit amet orci eger ultricies. Praesent posuere ante ut erat fringilla, vestibulum placerat metus mattis. Aenean dictum vitae nisl</p>
      </div>
    </div>

    <div class="featured_article">
      <div class="featured_text">
        <p>FEATURED ARTICLE</p>
        <strong>Cras malesuada et orci eget pharetra</strong>
        <p>In quis lectus sed leo elementum facibus in dapibus dictum. Nullamolestie tortor nec lectus venenatis, sed blandit dui, dolor at bibendum sadips ets ipsums dolores ficilis uns leo lectus.</p>
        <button class="read_more" type="button">READ MORE ></button>
      </div>
    </div>

    <div class="second_card">
      <div class="card">
          <div class="first">
            <img class="first_img" src="/src/assets/img/post_feat_img_22-320x202.jpg" alt="">
            <strong class="img_title">Morbi vitae dui euismod vulputate sollicitudin</strong>
            <p class="date_comments">October 11th, 2015 | Comments Off</p>
            <p class="img_text">Donec finibus sit amet orci eger ultricies. Praesent posuere ante ut erat fringilla, vestibulum placerat metus mattis. Aenean dictum vitae nisl</p>
          </div>
    
          <div class="second">
            <img class="second_img" src="/src/assets/img/post_feat_img_21-320x202.jpg" alt="">
            <strong class="img_title">Morbi vitae dui euismod vulputate sollicitudin</strong>
            <p class="date_comments">October 11th, 2015 | Comments Off</p>
            <p class="img_text">Donec finibus sit amet orci eger ultricies. Praesent posuere ante ut erat fringilla, vestibulum placerat metus mattis. Aenean dictum vitae nisl</p>
          </div>
    
          <div class="third">
            <img class="third" src="/src/assets/img/post_feat_img_20-320x202.jpg" alt="">
            <strong class="img_title">Morbi vitae dui euismod vulputate sollicitudin</strong>
            <p class="date_comments">October 11th, 2015 | Comments Off</p>
            <p class="img_text">Donec finibus sit amet orci eger ultricies. Praesent posuere ante ut erat fringilla, vestibulum placerat metus mattis. Aenean dictum vitae nisl</p>
          </div>
        </div>
    </div>

  </div>


</template>

<style>
/* Color Palette */
*{
  margin: 0;
  padding: 0;
}
:root{
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
.header{
  background-color: var(--bool-bg-header);
  align-items: center;
  display: flex;
  justify-content: space-around;
  padding: 1rem;
  
  .utilities{
      display: flex;
      color: var(--bool-white);
      gap: 2rem;
      align-items: center;

      .header_btn{
        background-color: var(--bool-text-btn);
        color: var(--bool-white);
        border: none;
        padding: 0.5rem;
      }
    }
}

/* Main 1st Section */
.main{
  background-image: url("../src/assets/img/home_slider_bg.jpg");
  height: 870px;

  .main_container{
    padding: 15rem;
    color: var(--bool-white);

    .main_text{
      gap: 2rem;
      display: flex;
      flex-direction: column;

      h2{
       font-size: 100px; 
      }

      .get_sign{
        width: 150px;
        padding: 0.5rem;
        background-color: var(--bool-bg-header);
        color: var(--bool-white);
        border: none;
      }
    }
  }
}

#main_container{
  height: 250px;
  background-color: var(--bool-text-primary);

  #main_text{
    padding: 5rem;
    text-align: center;
    align-items: center;
    display: flex;
    flex-direction: column;
    gap: 1.5rem;

    h4{
      color: var(--bool-first-section-title);
    }

    #title_text{
      color: var(--bool-first-section-text);
      width: 380px;
    }
    
  }
}

/* Main 2nd Section */
.latest_news{
  padding: 5rem;
  text-align: center;
  align-items: center;
  display: flex;
  flex-direction: column;
  gap: 1rem;

  #eget{
    color: var(--bool-first-section-title);
    font-size: 13px;
  }

  #latest_title{
    font-size: 30px;
  }

  hr{
    color: orange;
    width: 50px;
  }

  .card{
    width: 1700px;
    display: flex;
    justify-content: center;
    gap: 2rem;

    .first, .second, .third{
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      gap: 0.5rem;
  
      .date_comments{
        color: var(--bool-first-section-text);
        strong{
          color: black;
        }
      }

      .img_text{
        text-align: left;
        width: 320px;
        color: var(--bool-first-section-text);
      }
    }

  }
}

.featured_article{
  background-image: url("../src/assets/img/featured_article_1_bg.jpg");
  background-size: 100%;
  max-width: 1025px;
  height: 500px;

  .featured_text{
    display: flex;
    align-items: flex-start;
    flex-direction: column;
    gap: 1.5rem;
    padding: 13rem 5rem; 

    p{
      color: white;
      text-align: left;
    }
  
    strong{
      color: var(--bool-white);
      font-size: 25px;
    }
  
    .read_more{
      background-color: var(--bool-text-btn);
      color: var(--bool-white);
      border: none;
      padding: 1rem;
    }
  }
}

.second_card{
  margin: 3rem;
}
</style>
