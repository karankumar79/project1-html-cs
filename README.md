# project1-htmlcode
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Contact Form </title>
    <link rel="stylesheet" href="project1.css">
</head>
<body>

    <div class="container">
        <form>
            <h2> GET IN TOUCH </h2>
            <input type="text" id="name" placeholder="Enter Your Name" required>
            <input type="email" id="email" placeholder="Enter Your Email" required>
            <input type="phone" id="phone" placeholder="Enter Your Phone Number" required>
            <input type="text" id="coupon" placeholder="Enter Coupen Code" required>

            <textarea id="message" rows="4" placeholder="Write Something"></textarea>
            <button type="submit">Send</button>
        </form>
    </div>
    <!-- Contact form using HTML and CSS by raju_webdev -->
</body>
</html>

#project1 css
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap");
* {
  margin: 0px;
  padding: 0px;
  font-family: "Poppins", sans-serif;
}

.container {
  background-color:palegoldenrod;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 20px;
  height: 100vh;
}

form {
  background-color:blue;
  display: flex;
  flex-direction: column;
  padding: 2vw 4vw;
  width: 60%;
  max-width: 600px;
  border-radius: 10px;
}

form h2 {
  text-align: center;
  color: #e65b00;
  margin-bottom: 20px;
}

form input, textarea {
  border: 0;
  margin: 10px 0px;
  padding: 20px;
  outline: none;
  background: #f5f5f5;
  font-size: 16px;
  border-radius: 10px;
  resize: none;
}

form button {
  background: white;
  color: #e65b00;
  border: 1px solid #e65b00;
  padding: 15px;
  font-size: 1rem;
  outline: none;
  cursor: pointer;
  width: 100%;
  font-weight: bold;
  margin: 20px auto 0;
  border-radius: 30px;
  transition: all .5s ease-in;
}

form button:hover {
  border: 1px solid #e65b00;
  background: #e65b00;
  color: white;
}

