<!DOCTYPE html>
<html>
    <header>
        <title>Ram HomePage</title>
    </header>
    <body>
        <h1>An Arrange come Love story</h1>
        <hr noshade="" color="Blue" size="3">
        <img src="IMG.jpg" alt="Picture" style="float:right;width: 750px;height: 500px;">
        <p>Journey from 2020</p>
        <ul>
            <li>First seen - <em>9th Feb 2020</em></li>
            <li>Birthday visit - <em>11th Feb 2020</em></li>
        </ul> 
        <a href="https://www.yoursaibaba.com/" target="_blank">Your's favourite first page - Click here</a><br>
        <a href="Page2.html">Lifetime Message - Click here</a><br>
        <a href="Page3.html">Today's Message - Click here</a><br>
        <a href="https://www.youtube.com/watch?v=DScFlfN9vDk" target="_blank">Song Dedicated to you - Click here</a>
        <!--
            <img src="IMG_4610.jpg" alt="Picture" 
        style="width: 750px;height: 500px;">
        --> 
        <hr align="left" width="25%" color="black">
        <h3>Contact US</h3>
        <form>
            <label for="Name">Your name:</label>
            <input id="Name" type="text" name="Name"><br>
            <label for="email">Email:</label>
            <input id="email" type="email" name="email"><br>
            <label for="Phone">Phone:</label>
            <input id="Phone" type="tel" name="Phone"><br>
            <label for="Message">Your Message:</label>
            <textarea id="Message" name="Message"></textarea><br>
            <input type="submit" name="">
            <input type="reset">
        </form>
        <label for="favcolor">Favourite color</label>
        <select id="favcolor" name="favcolor">
            <option value="colorRed">Red</option>
            <option value="colorBlue">Blue</option>
            <option valule="colorGreen">Green</option>
        </select>
        <fieldset>
            <legend>How do you commute to office daily?</legend>
            <input type="radio" id="bike" name="commute" value="bike"><label for="bike">Bike</label>
            <input type="radio" id="car" name="commute" value="car"><label for="car">Car</label>
            <input type="radio" id="Public" name="commute" value="public"><label for="public">Public Transport</label>

        </fieldset>
        <fieldset>
            <legend>Favourite Food?</legend>
            <input type="checkbox" id="idly" name="Food" value="idly"><label for="idly">Idly</label>
            <input type="checkbox" id="dosa" name="Food" value="dosa"><label for="dosa">Dosa</label>
            <input type="checkbox" id="vada" name="Food" value="vada"><label for="vada">Vada</label>
        </fieldset>
    </body>
</html>
