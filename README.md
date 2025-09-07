# Master-Card-Form
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <style>
     body {
  font-family: Arial, sans-serif;
  background-color: #f0f0f0;
}

.container {
  background-color: #d1e379;
  width: 400px;
  margin: 40px auto;
  padding: 25px;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0,0,0,0.2);
}

form h2 {
  color: #333;
  margin-top: 20px;
}

label {
  display: block;
  margin-top: 10px;
  font-weight: bold;
}

</style>
  </head>
  <body>
    <form>
      <div class="container">
      <h2>Step 1: Your details</h2>
      <label>Name</label>
      <input type="text" placeholder="First and last name">

      <label>Email</label>
      <input type="email" placeholder="example@email.com">

      <label>Phone</label>
      <input type="tel" placeholder="+234xxxxxxxxxx">

      <h2>Step 2: Delivery address</h2>
      <label>Address</label>
      <textarea>message</textarea>

      <label>Post code</label>
      <input type="text">

      <label>Country</label>
      <input type="text">
      <h2>Step 3: Card details</h2>
      <label>Card type</label>
      <div class="card-type">
        <input type="radio" name="card"> VISA
        <input type="radio" name="card"> AmEx
        <input type="radio" name="card"> Mastercard
      </div>

       <label>Card number</label>
       <input type="text">

       <label>Security code</label>
       <input type="text">

       <label>Name on card</label>
       <input type="text" placeholder="Exact name on the card">

      <button type="submit">BUY IT!</button>
    </form>
  </body>
</html>
