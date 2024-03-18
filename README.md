<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Param Saha Day 04 </title>
    <link rel="icon" href="favicon.ico">
    <style>
        .styled {
  border: 0;
  line-height: 2.5;
  padding: 0 20px;
  font-size: 1rem;
  text-align: center;
  color: #fff;
  text-shadow: 1px 1px 1px #000;
  border-radius: 10px;
  background-color: rgb(220 0 0 / 100%);
  background-image: linear-gradient(
    to top left,
    rgb(0 0 0 / 20%),
    rgb(0 0 0 / 20%) 30%,
    rgb(0 0 0 / 0%)
  );
  box-shadow:
    inset 2px 2px 3px rgb(255 255 255 / 60%),
    inset -2px -2px 3px rgb(0 0 0 / 60%);
}

.styled:hover {
  background-color: rgb(255 0 0 / 100%);
}

.styled:active {
  box-shadow:
    inset -2px -2px 3px rgb(255 255 255 / 60%),
    inset 2px 2px 3px rgb(0 0 0 / 60%);
}

    </style>
</head>
<body>
    <h1 style="color: rgb(250, 100, 0);">Sign Up</h1>
    <form action="" method="get" class="form-example">
        <div class="form-example" >
          <label for="name">Enter your First Name: </label><br>
          <input type="text" name="name" id="name" required />
        </div>
        <div class="form-example">
          <label for="name">Enter your Last Name: </label><br>
          <input type="name" name="name" id="name" required />
        </div>
        <div class="form-example">
          <label for="number">Enter your Phone Number: </label><br>
          <input type="number" name="number" id="numbers" required />
        </div>
        <div>
            <label for="start">Date of Birth:</label><br>

        <input type="date" id="start" name="trip-start" value="2024-01-01" min="1920-01-01" max="2024-01-01" /> 
        
        </div>
        <div class="form-example">
          <label for="email">Enter your Email Address: </label><br>
          <input type="email" name="email" id="email" required />
        </div>
        <div>
            <label for="pass">Password (8 characters minimum):</label><br>
            <input type="password" id="pass" name="password" minlength="8" required/>
          </div>
        <div class="form-example">
            <label for="url">Enter your facebook URL:</label><br>
            <input type="url" name="url" id="url" placeholder="https://example.com" pattern="https://.*" size="30" required />
        </div>
        <div>
            <label for="avatar">Choose a profile picture:</label><br>

        <input type="file" id="avatar" name="avatar" accept="image/png, image/jpeg" />
        </div><br>
        <fieldset>
            <legend>By signing up you agree to our terms and conditions.:</legend>
          
            <div>
              <input type="radio" id="Yes" name="drone" value="Yes" checked />
              <label for="Yes">Yes</label>
            </div>
          
            <div>
              <input type="radio" id="No" name="drone" value="No" />
              <label for="No">No</label>
            </div>
          </fieldset><br>

          <div>
            <input class="styled" type="submit" value="Submit"/>
        </div>
          
        

</body>
</html>
