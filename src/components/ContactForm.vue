<template>
 <body>
    <section id="contact">
        <h2>Get in contact with us</h2>
        <div class="container text-center">
            <div class="row">
              <div class="col-sm-6">
                <img src="https://i.postimg.cc/13vwVPb9/transparent.png" class="img-fluid" style="width:100%;" alt="contact">
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
    background-image: linear-gradient( rgba(0, 0, 0, 0.7),black);
}

h2 {
    text-align: center;
    padding: 20px;
    font-family: 'Poppins', sans-serif;
    color: rgb(224, 215, 161);
    font-size: 40px;
}

label {
    font-family: 'Poppins', sans-serif;
    color: rgb(224, 215, 161);
    font-weight: bold;
    font-size: 20px;
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

  img {
    margin-top: 80px;
  }
  
</style>