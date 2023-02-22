<template lang="">
 <body>
    <section id="about">
        <div class="container-about">
            <div class="row align-items-start">
              <div class="col-sm-6 text-align-center" style="padding-top: 150px;">
                <h1>Our mission is to provide fitness clothes that inspire both men and women to look their best.</h1>
                <center><button>About Us</button></center>
              </div>
              <div class="col-lg-6">
                <h2><img src="https://i.postimg.cc/13vwVPb9/transparent.png" style="height:7rem" alt=""> provides all types of fitness outfit and equipment. They include:</h2>
                <div class="container">
                    <div class="row align-items-start">
                      <div class="col-sm-4">
                        <h4>Tops</h4>
                        <p>Our fitness tops are meticulously designed to provide comfort and versatility, allowing you to adorn them for both high and low impact workouts</p>
                      </div>
                      <div class="col-sm-4">
                        <h4>Bottoms</h4>
                        <p>Our bottoms collection features some, simple, stylish, and functional bottoms. From shorts to joggers sweatpants, you won't miss something that works for you</p>
                      </div>
                      <div class="col-sm-4">
                        <h4>Accessories</h4>
                        <p>Our accessories varies from all categories from cups, bags, gym equipment.</p>
                      </div>
                    </div>
                    <button><a href="#dproducts">See Our Offering</a></button>
                  </div>
              </div>
            </div>
          </div>        
        </section>
        <section id="team">
          <h1>About Our Team</h1>
          <div class="container-team text-center">
            <div class="row align-items-end">
              <div class="col-sm-6">
                <div class="card">
                    <img src="https://i.postimg.cc/Gt87rd3h/team.jpg" alt="John" style="width:100%">
                    <h3>Cassidy Lawrence</h3>
                    <p class="title">Backend Developer / Co-Founder</p>
                    <p>Life Choices Academy</p>
                    <div style="font-size: 30px; gap:5rem;">
                      <a href="#" target="_blank"><i class="fa-brands fa-github text-light" style="padding:10px;"></i></a>
                      <a href="#" target="_blank"><i class="fa-brands fa-linkedin text-light" style="padding:10px;"></i></a>  
                    </div>
                    <p><button>Get in touch <i class="fa-sharp fa-solid fa-hand-point-up"></i></button></p>
                  </div>
              </div>
              <div class="col-sm-6">
                <div class="card">
                  <img src="https://i.postimg.cc/Gt87rd3h/team.jpg" alt="John" style="width:100%">
                  <h3>Meezaan Davids</h3>
                  <p class="title">Frontend Developer / Co-Founder</p>
                  <p>Life Choices Academy</p>
                  <div style="font-size: 30px; gap:5rem; background">
                    <a href="#" target="_blank"><i class="fa-brands fa-github text-light" style="padding:10px;"></i></a> 
                    <a href="#" target="_blank"><i class="fa-brands fa-linkedin text-light" style="padding:10px;"></i></a>  
                  </div>
                  <p><button>Get in touch <i class="fa-sharp fa-solid fa-hand-point-up"></i></button></p>
                </div>
              </div>
            </div>
          </div>
        </section>
 </body>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    #about {
        height: 100%;
        background-image: linear-gradient( rgba(0, 0, 0, 0.7), black);
        padding: 50px;
    }

    #team {
      background: black;
    }
    .container-about {
        padding-bottom: 50px;
    }

    .container-team {
        width: 100%;
        padding: 0;
    }

    h1 {
        text-align: center;
        font-family: 'Poppins', sans-serif;
        color: rgb(224, 215, 161);
        font-weight: bold;
    }

    h2 {
        text-align: center;
        padding: 20px;
        font-family: 'Poppins', sans-serif;
        color: rgb(224, 215, 161);
        font-size: 20px;
    }

    h3 {
      padding-top: 20px;
      color: rgb(224, 215, 161);
    }

    h4 {
        font-size: 30px;
        color: beige;
    }

    p {
        color: rgb(224, 215, 161);
    }

    button {
        text-align: center;
        border: none;
        padding: 10px;
        background: rgb(224, 215, 161);
        color: black;
        font-family: 'Poppins', sans-serif;
        font-weight: bold;
    }

    button:hover {
        background: transparent;
        color: white;
        border: 1px solid white;
    }

    button a {
      text-decoration: none;
    }

    .card {
        box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
        max-width: 300px;
        margin: auto;
        text-align: center;
        font-family: arial;
        background: black;
        padding: 20px;
      }

      i {
        height:20px
      }
    
</style>