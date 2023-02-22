<template>
 <body>
    <section id="contact">
        <h2>Get in contact with us</h2>
        <div class="container text-center">
            <div class="row">
              <div class="col-sm-6">
                <img src="https://i.postimg.cc/13vwVPb9/transparent.png" style="width:100%;" alt="contact">
                <ul>
                    <li><a href=""><i class="fa-solid fa-location-dot text-light"></i></a></li>
                    <li><a href=""><i class="fa-solid fa-phone text-light"></i></a></li>
                    <li><a href=""><i class="fa-brands fa-instagram text-light"></i></a></li>
                </ul>
              </div>
              <div class="col-sm-6">
                <form action="https://formspree.io/f/mbjbywlp" method="post">
                    <label for="name">Name</label>
                    <input type="text" id="name" name="name" required placeholder="Enter your name">
                    <label for="Surname">Surname</label>
                    <input type="text" id="surname" name="surname" required placeholder="Enter your surname">
                    <label for="email">Your Email address</label>
                    <input type="text" id="email" name="email" required placeholder="Enter your email">
                    <label for="lname">Your Contact Number </label>
                    <input type="text" id="number" name="number" required placeholder="Enter your number">
                    <label for="subject">Subject</label>
                    <textarea id="subject" name="subject" placeholder="Write something.." style="height:100px"></textarea>
                    <center><input type="submit" value="Submit"></center>
                  </form>
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

#contact {
    background: black;
    border: 2px solid rgb(224, 215, 161);

}

h2 {
    text-align: center;
    padding: 20px;
    font-family: 'Poppins', sans-serif;
    color: rgb(224, 215, 161);
    font-size: 40px;
}

label {
    color: white;
  }

  input[type=text], select, textarea {
    width: 100%;
    padding: 12px;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
    margin-top: 6px;
    margin-bottom: 16px;
    resize: vertical;
  }

  input[type=submit] {
    background-color: rgb(224, 215, 161);
    color: black;
    padding: 12px 20px;
    border: 1px solid white;
    cursor: pointer;
  }

  input[type=submit]:hover {
    background-color: transparent;
    color: white;
    border: 1px solid white;
  }

  ul {
    display: flex;
    font-size: 25px;
    gap: 3rem;
    padding: 70px;
  }

  ul li {
    list-style: none;
  }
  
</style>