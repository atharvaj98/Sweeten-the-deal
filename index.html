<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Let's Sweeten the Deal 😊</title>
<style>
  body {
    font-family: Arial, sans-serif;
    background-color: #f8f8f8;
    margin: 0;
    padding: 20px;
  }
  .container {
    max-width: 400px;
    margin: 0 auto;
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }
  h1 {
    text-align: center;
    color: #333;
  }
  label {
    display: block;
    margin-bottom: 5px;
    font-weight: bold;
    color: #555;
  }
  input[type="text"] {
    width: calc(100% - 20px);
    padding: 8px;
    margin-bottom: 15px;
    border: none;
    border-bottom: 1px solid #ccc;
    outline: none;
    color: #333;
  }
  button {
    width: 48%;
    padding: 10px;
    background-color: #e83350;
    color: #fff;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    transition: background-color 0.3s;
    margin-right: 4%;
  }
  button:last-child {
    margin-right: 0;
  }
  button:hover {
    background-color: #cc2a40;
  }
  .result {
    margin-top: 20px;
  }
  #effectivePrice {
    font-weight: bold;
    color: green;
  }
  #total {
    color: red;
  }
  #discountPercentage {
    font-weight: bold;
  }
</style>
</head>
<body>

<div class="container">
  <h1>Let's Sweeten the Deal 🥳</h1>
  <label>Item Total:</label>
  <input type="text" id="itemTotal" oninput="validateNumber(this)">
  <label>Discount Percentage:</label>
  <input type="text" id="discountPercentage" oninput="validateNumber(this)">
  <label>Cost of Modular after Discount:</label>
  <input type="text" id="afterDiscount" readonly>
  <label>You Save:</label>
  <input type="text" id="youSave" readonly>
  <label>Handling Fees (inc. GST CGST):</label>
  <input type="text" id="handlingFees" readonly>
  <p>Final Price: <span id="effectivePrice"></span></p>
  <div class="buttons">
    <button onclick="calculate()">Calculate</button>
    <button onclick="clearInputs()">Clear</button>
  </div>
</div>

<script>
function validateNumber(input) {
  // Remove any characters except digits and dot
  input.value = input.value.replace(/[^0-9.]/g, '');
  // Ensure only one dot is present
  if ((input.value.match(/\./g) || []).length > 1) {
    input.value = input.value.slice(0, -1);
  }
}

function calculate() {
  var itemTotal = parseFloat(document.getElementById('itemTotal').value) || 0;
  var discountPercentage = parseFloat(document.getElementById('discountPercentage').value) || 0;
  var handlingFees = (itemTotal * 0.1).toFixed(2);
  
  var afterDiscount = (itemTotal - (discountPercentage / 100 * itemTotal)).toFixed(2);
  var youSave = (itemTotal - afterDiscount).toFixed(2);
  var effectivePrice = (parseFloat(afterDiscount) + parseFloat(handlingFees)).toFixed(2);
  
  document.getElementById('afterDiscount').value = afterDiscount;
  document.getElementById('youSave').value = youSave;
  document.getElementById('handlingFees').value = handlingFees;
  document.getElementById('effectivePrice').textContent = effectivePrice;
}

function clearInputs() {
  document.getElementById('itemTotal').value = '';
  document.getElementById('discountPercentage').value = '';
  document.getElementById('afterDiscount').value = '';
  document.getElementById('youSave').value = '';
  document.getElementById('handlingFees').value = '';
  document.getElementById('effectivePrice').textContent = '';
}
</script>
</body>
</html>
