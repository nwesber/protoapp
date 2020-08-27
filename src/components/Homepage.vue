<template>
  <div>
    <header>
      <div class="nav">
        <a class="nav-item" href="#home"><img width="50" src="../assets/logo1.svg" /> Protoapp</a>
        <a class="nav-item" href="#home">Home</a>
      </div>
      <div class="banner">
        <h1 class="title">Protoapp</h1>
        <p class="sub-title">Our landing page template works on all devices, so you only have to set it up once, and get beautiful results forever.</p>
        <button class="banner-cta">Get Started</button>
      </div>
      <div class="app-banner">
        <div class="app-banner-body">
          <img src="../assets/badge.play-store.svg" />
          <img src="../assets/badge.app-store.svg" />
        </div>
      </div>
    </header>
    <div class="main">
      <div class="main-title">
        <h1>Meet Protoapp</h1>
        <p>The app lorem ipsum is common placeholder text used to demonstrate the graphic elements of a document or visual presentation.</p>
      </div>
      <div class="main-product">
          <div class="description text-right">
            <h2>Discover</h2>
            <p>Get information on using these guidelines whenever you are using therefore they have the same style and quality</p>
          </div>
          <div class="image text-left">
            <img src="../assets/product-search.svg" />
          </div>
      </div>
      <div class="main-product">
          <div class="image text-right">
            <img src="../assets/product-smartphone.svg" />
          </div>
          <div class="description text-left">
            <h2>Augmented</h2>
            <p>World salad often arouses curiosity due to its seemingly intelligent and tasteful play on words.</p>
          </div>
      </div>
      <div class="main-product">
          <div class="description text-right">
            <h2>Endless Possibilities</h2>
            <p>Management Systems shouldn't be a bore. Run out of words? heres some lorem ipsum: Lorem Ipsum dolor sit amet.</p>
          </div>
          <div class="image text-left">
            <img src="../assets/product-work.svg" />
          </div>
      </div>
    </div>
    <div class="main-app-bg">
      <div class="main-app-banner">
        <h1>Deep dive. Ready?</h1>
        <p>So are we. Unless. You're. Not. Word filler.</p>
        <img src="../assets/badge.play-store.svg" />
        <img src="../assets/badge.app-store.svg" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Homepage',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
  .text-right{
    text-align: right;
  }

  .text-left{
    text-align: left;;
  }
  
  header{
    background-image: url(../assets/bg-leaves.svg);
    background-position: right top;
    background-repeat: no-repeat;
  }

  .nav {
    background-color: transparent;
    padding-left: 15rem;
    padding-right: 15rem;
    padding-top: 1rem;
    display: flex;
    align-items: center;
  }

  .nav a {
    float: left;
    color:black;
    text-align: center;
    text-decoration: none;
    padding: 1rem 1rem 1rem 0;
  }

  .nav .nav-item{
    font-size: 23px;
    display: flex;
    align-items: center;
  }

  .nav .nav-item img{
    margin-right: 8px;
  }

  .banner{
    padding-left: 15rem;
    padding-right: 15rem;
    padding-top: 2rem;
    padding-bottom: 10rem;
    width: 35%;
  }

  .banner .title{
    font-size: 4rem;
    margin-bottom: 1rem;
    font-weight: 600;
  }

  .banner .sub-title{
    font-size: 28px;
    font-weight: 300;
  }

  .banner .banner-cta{
    background-color: var(--main-color);
    color: var(--white);
    border: none;
    padding: 14px 30px;
    font-size: 24px;
    border-radius: 9px;
  }

  .app-banner{
    padding-top: 10rem;
    padding-bottom: 6rem;
    padding-left: 15rem;
    padding-right: 15rem;
    background-image: url(../assets/bg-decals.svg);
    background-position: left top;
    background-repeat: no-repeat;
    margin-top: -170px;
    margin-left: -91px;
  }

  .app-banner .app-banner-body{
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    border-top: 1px solid #8080802b;
    border-bottom: 1px solid #8080802b;
    padding-top: 1rem;
    padding-bottom: 1rem;
    margin-left: 2.8rem;
  } 

  .app-banner .app-banner-body img{
    padding: 15px;
  }

  .main{
    padding-left: 15rem;
    padding-right: 15rem;
    padding-bottom: 5rem;
  }

  .main .main-title{
    text-align: center;
    padding-left: 10rem;
    padding-right: 10rem;
  }

  .main .main-title h1{
    font-size: 3rem;
    margin-bottom: 1rem;
    font-weight: 700;
  }

  .main .main-title p{
    font-size: 28px;
    font-weight: 300;
  }

  .main-product{
    padding-left: 10rem;
    padding-right: 10rem;
    display: flex;
    justify-content: center;
    padding-top: 2rem;
    padding-bottom: 2rem;
  }

  .main-product .description{
    padding-left: 1rem;
    padding-right: 1rem;
    width: 50%;
  }

  .main-product .description h2{
    font-size: 2.5rem;
    font-weight: 700;
    margin-bottom: 0;
  }

  .main-product .description p{
    font-size: 22px;
    font-weight: 300;
  }

  .main-product .image{
    padding-left: 1rem;
    padding-right: 1rem;
    width: 50%;
  }

  .main-product .image img{
    width: 60%;
  }

  .main-app-bg{
    background-image: url(../assets/bg-decals2.svg);
    background-position: right top;
    background-repeat: no-repeat;
  }

  .main-app-bg .main-app-banner{
    background-color: var(--main-color);
    padding: 8rem 8rem;
    mix-blend-mode: overlay;
    text-align: center;
    color: var(--white);
  }

  .main-app-bg .main-app-banner h1{
    font-weight: 700;
    font-size: 3rem;
    margin-bottom: 0;
  }

  .main-app-bg .main-app-banner p{
    font-size: 22px;
    font-weight: 300;
  }


  .main-app-bg .main-app-banner img{
    margin: 5px;
  }

  @media (max-width: 800px)
  {
    .nav{
      padding-left: 10px;
      padding-right: 0;
    }

    header{
      background-image: none;
    }

    .banner{
      width: 94%;
      padding-left: 10px;
      padding-right: 10px;
      padding-bottom: 4rem;
      text-align: center;
      padding-top: 1rem;
    }

    .banner .title{
      margin-top: 1rem;
    }

    .banner .sub-title{
      font-size: 22px;
      font-weight: 300;
    }

    .banner .banner-cta{
      padding: 12px 29px;
      font-size: 17px;
    }

    .app-banner{
      padding-left: 0;
      padding-right: 0;
      margin-top: -170px;
      margin-left: 0;
      background-image: none;
      padding-bottom: 1rem;
    }

    .app-banner .app-banner-body{
      margin-left: 0;
    } 

    .main{
      padding-left: 0;
      padding-right: 0;
    }

    .main .main-title{
      padding-left: 10px;
      padding-right: 10px;
    }

    .main .main-title h1{
      font-size: 2.5rem;
    }

    .main .main-title p{
      font-size: 23px;
    }

    .main-product{
      padding-left: 10px;
      padding-right: 10px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }

    .main-product .description{
      width: 90%;
      order: 1;
      text-align: center;
    }

    .main-product .image{
      width: 90%;
      text-align: center;
    }

    .main-app-bg{
      background-image: none;
    }

    .main-app-bg .main-app-banner{
      padding: 5rem 1rem;
    }
  }


</style>
