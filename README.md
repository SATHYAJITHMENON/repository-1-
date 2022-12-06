# repository-1-
form page
this form page is created to fill a ideal car option 
<!DOCTYPE html>
<html>
  <style>
    body {
      background-image: url('https://wallpaperaccess.com/full/239663.jpg');
      background-repeat: no-repeat;
      background-size: cover;
      color: aliceblue;
      width: 98%;
    }
    .a {
      align-items: center;
      font-family: 'Times New Roman', Times, serif;
      font-size: xx-large;
      text-align: center;
      padding-top: 30px;
      color: black;
    }
    .b {
      font-family: 'Times New Roman', Times, serif;
      font-size: large;
      color: aliceblue;
      padding-left: 300px;
      padding-top: 80px;
    }
    .c {
      font-family: 'Times New Roman', Times, serif;
      text-align: right;
      font-size: large;
      color: aliceblue;
      padding-right: 300px;
      padding-top: 0px;
      position: relative;
      top: -50px;
      left: 10px;
    }
    .d {
      font-family: 'Times New Roman', Times, serif;
      text-align: center;
      font-size: x-large;
      color: aliceblue;
      padding: left 50px;
    }
    .e {
      font-family: 'Times New Roman', Times, serif;
      text-align: center;
      font-size: x-large;
      color: aliceblue;
      padding-top: 100px;
    }
    .f {
      font-family: 'Times New Roman', Times, serif;
      text-align: center;
      font-size: xx-large;
      color: aliceblue;
      padding-top: 112px;
      size: 50px;
    }
    h1 {
      font-family: 'Times New Roman', Times, serif;
      text-align: center;
    }
  </style>
  <body>
    <h1>LETS FIND YOUR IDEAL CAR</h1>
    <div class="a">
      <label for="PICK UP LOCATION">PICK YOUR LOCATION</label><br />
      <select name="LOCATIONS" id="STATES">
        <option value="KERALA">KERALA</option>
        <option value="DELHI">DELHI</option>
        <option value="PUNJAB">PUNJAB</option>
        <option value="UP">UP</option>
      </select>
    </div>
    <div class="b">
      <label for="PICK UP DATE">PICK UP DATE</label><br />
      <input type="date" id="PICK UP DATE" name="PICK UP DATE" /><br />
    </div>
    <div class="c">
      <label for="DROP OFF DATE">DROP OFF DATE</label><br />
      <input type="date" id="DROP OF DATE" name="DROP OF DATE" />
    </div>
    <div class="d">
      <label for="PURPOSE OF RENTAL">PURPOSE OF RENTAL:</label>
      <input type="radio" id="BUSSINESS" name="PURPOSE" value="BUSSINESS" />
      <label for="BUSSINESS">BUSSINESS</label>
      <input type="radio" id="LEISURE" name="PURPOSE" value="LEISURE" />
      <label for="LEISURE">LEISURE</label>
    </div>
    <div class="e">
      <label for="TIMING">TIMING</label><br />
      <input type="time" id="TIMING" name="TIMING" />
    </div>
    <div class="f">
      <input type="submit" value="SUBMIT" />
    </div>
  </body>
</html>
