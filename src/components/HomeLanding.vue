<template>
  <body>
    <section id="home"> 
      <div class="landing">
        <nav class="navbar navbar-expand-lg">
          <div class="container-fluid">
            <a href="#" class="navbar-brand"><img src="https://i.postimg.cc/25NW2htS/transparent.png" style="height:10vh" alt=""></a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavDropdown">
              <ul class="navbar-nav gap-3">
                <li class="nav-item active">
                  <a href="/" class="nav-link text-light"><span>HOME</span></a>
                </li>
                <li class="nav-item">
                  <a href="#about" class="nav-link text-light">ABOUT</a>
                </li>
                <li class="nav-item">
                  <a href="#" class="nav-link text-light">SHOP</a>
                </li>
                <li class="nav-item">
                  <a href="#" class="nav-link text-light">ADMIN</a>
                </li>
                <li class="nav-item">
                  <a href="#contact" class="nav-link text-light">CONTACT</a>
                </li>
              </ul>
              <ul class="user">
                <li><button><a href="/login">LOGIN</a></button></li>
                <li><button><a href="/register">SIGN UP</a></button></li>
              </ul>
            </div>
          </div>
        </nav>
        <div class="content">
          <div class="container-land">
            <img src="https://i.postimg.cc/YCL1y5mx/design2.jpg" alt="LandingPage" style="width:100%;height:88vh">
            <div class="content">
              <img src="https://i.postimg.cc/25NW2htS/transparent.png" style="height:20vh" alt="">
              <p>Active 8 supports our local fitness enthusiasts by outfitting them in creatively designed fitness apparel.</p>
              <button class="learn"><a href="#about">Learn More</a></button>
            </div>
          </div>
        </div>
        </div>
    </section>
  
  </body>
</template>

<script>
export default {
  name: 'HomeLanding',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.navbar-nav {
  font-size: x-large;
  text-align: center;
}

.navbar-nav {
  align-items: center;
  justify-content: center;
  margin: auto;
}

.nav-link:hover {
  background: rgb(224, 215, 161);
  color: black;
  text-decoration: underline 3px;
}

.user {
  display: flex;
  gap: 5px;
}

.user a {
  text-decoration: none;
  color: black;
  font-weight: bold;
}

.user li {
  list-style: none;
}

.user button {
  background-color: rgb(255, 200, 99);
  color: black;
  border-radius: 70px;
  padding: 10px;
  font-size: medium;
}

span {
  text-decoration: underline;
  color: rgb(255, 200, 99);
}

.landing {
  padding: 0;
  width: 100%;
  background:black;
  height: auto;
  overflow: hidden;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
 
}

.col {
  padding-top: 5rem;
}
.col h2 {
  color: white;
}

.container-land {
  position: relative;
  width: 100%;
  margin: 0 auto; 
}

.container-land .content {
  position: absolute; 
  bottom: 0; 
  background: rgb(0, 0, 0); 
  background: rgba(0, 0, 0, 0.5); 
  color: #f1f1f1; 
  width: 100%; 
  padding: 20px; 
}
content {
  height: 70vh;
}

p {
  font-size: 30px;
}

.learn {
  border: none;
  padding: 10px;
  background: rgb(255, 200, 99);
  color: black;
  text-decoration: none;
}

.learn button:hover {
  background: transparent;
  color: white;
  border: 2px solid white;
}

.learn a {
  text-decoration: none;
  color: black;
}
</style>
