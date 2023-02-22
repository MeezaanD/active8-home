<template>
 <body>
    <section id="dproducts">
        <h2>Shop now with our latest releases</h2>
        <h4>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Commodi quod corrupti amet deserunt voluptates praesentium possimus. Incidunt cupiditate excepturi, quo deserunt eius totam mollitia odit reiciendis maiores vel alias velit.</h4>
        <div class="row row-cols-1 row-cols-md-3 g-4 p-5">
            <div class="col">
              <div class="card h-75">
                <img src="https://i.postimg.cc/qqFWhKs8/men.jpg" class="card-img-top h-75" alt="...">
                <div class="card-body">
                  <h5>Latest Men Clothing</h5>
                  <center><button><a href="">Shop Now</a></button></center>
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card h-75">
                <img src="https://i.postimg.cc/y6RGvDyr/women.jpg" class="card-img-top h-75" alt="...">
                <div class="card-body">
                  <h5>Latest Women Clothing</h5>
                  <center><button><a href="">Shop Now</a></button></center>
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card h-75">
                <img src="https://i.postimg.cc/50s2rPJb/bag.jpg" class="card-img-top h-75" alt="...">
                <div class="card-body">
                  <h5>Latest Accessories</h5>
                  <center><button><a href="">Shop Now</a></button></center>
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
    #dproducts {
        background-image: linear-gradient( black,rgba(0, 0, 0, 0.7));
    }

    button {
        text-align: center;
        border: none;
        margin-top: 30px;
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

    .container {
        margin-top: 20px;
    }

    h2 {
        text-align: center;
        font-family: 'Poppins', sans-serif;
        color: rgb(224, 215, 161);
        font-size: 50px;
        padding: 30px;
    }

    h4 {
        text-align: center;
        font-family: 'Poppins', sans-serif;
        color: rgb(224, 215, 161);
    }

    h5 {
        text-align: center;
        font-family: 'Poppins', sans-serif;
        color: rgb(224, 215, 161);
        font-size: 30px;
    }

    .card {
        background: transparent;
        box-shadow: 0 20px 30px rgba(0,0,0,0.2);
        backdrop-filter: blur(10px);
        height: auto;
        border-radius: 0;
    }
    

</style>