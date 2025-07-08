# Interest Calculator 

This is a simple **Interest Calcualtor** web application built using **HTML, CSS, JAVASCRIPT**. The application allows users to calculate **compound interest ** by entering the principal amoujnt, rate of interest and the years like the time period.


## Features 
- Calculate **compound interest**
- Instant results using Javascript `onclick` event 
- Clean and user friendly interface 
- Fully client-side -- no backend required 
- only take numbers and return zero if client trys to write string or 
  negative numbers 

## Demo
![App Screenshot](images/Screenshot%202025-07-08%20170628.png)

## How It Works

The Calculator uses the standard compound interest formula:

compound interest = P(1+ r/n)^tn

when the user clicks the **submit** button, a javascript function is triggered vis the `onclick` property in the HTML file:
```html
<button type="button" onclick ="calcaulate()">submit</button>

This function takes the values from inout fields, performs the calculation, and displays the result on the page under total 

🧾Example  Code Snippet 
<label for="principal">Principal Amount:</label>
       <input type="number" id="principal">

       <label for="rate">Interest Rate:</label>
       <input type="number" id="rate">


       <label for="years">Years:</label>
       <input type="number" id="years">

       <button type="button"  onclick="calculate()">submit</button>

       <p id="total">Total: <span id="total-amount">$0.0</span></p>