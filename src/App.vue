<script>
</script>

<template>
  <!-- FontAwesome Cdn -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"
    integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA=="
    crossorigin="anonymous" referrerpolicy="no-referrer" />


  <!-- Header Part -->
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
  --bool-bg: #F2F2F2;
  --bool-darker: #707070;
}

.header{
  background-color: var(--bool-bg-header);
  align-items: center;
  display: flex;
  justify-content: space-around;
  padding: 1rem;
  
  .utilities{
      display: flex;
      color: white;
      gap: 2rem;
      align-items: center;

      .header_btn{
        background-color: var(--bool-text-btn);
        color: white;
        border: none;
        padding: 0.5rem;
      }
    }
}

</style>
