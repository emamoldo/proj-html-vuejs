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
      <h3>AVADA FORUM IS THE PLACE TO BE</h3>
      <p id="title_text">In quis lectus leo elementum faucibus in depibus dictum. Nulla molestie tortor nec lectus venenatis, sed blandit dui finibus, dolor at, bibendum purus. Donec vehicula nec tortor ac finibus.</p>
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
  height: 200px;
  background-color: var(--bool-text-primary);

  #main_text{
    padding: 5rem;
    text-align: center;
    display: flex;
    flex-direction: column;
    gap: 1.5rem;

    h3{
      color: var(--bool-first-section-title);
    }

    #title_text{
      color: var(--bool-first-section-text);
      text-wrap: balance;
    }
    
  }
}
</style>
