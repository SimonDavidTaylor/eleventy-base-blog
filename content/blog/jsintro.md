---
title: Intro to JavaScript
date: 2023-11-13
draft: false
---
<a href="https://codepen.io/SimonDTaylor/pen/yLGdNKv" target="_blank">Here's</a> a link to my CodePen for the JavaScript below.

<h3>Percentage Calculator</h3>
<code>
function calculatePercentage (number, percentage) {<br>
  var number;<br>
  var percentage;<br>
  var result;<br>
  
  result = number * percentage / 100;<br>
  return result;<br>
}
</code>

<h3>Switch Statement</h3>
<code>
	function drinkOrder (size, buttonName) {<br>
  
  var size;<br>
  var buttonName;<br>
  var drinkName;<br>
  var orderText;<br>
  
  switch (buttonName) {<br>
    case "cola":<br>
      drinkName = "Cola";<br>
      break;<br>
    case "lemon":<br>
      drinkName = "Lemonade";<br>
      break;<br>
    case "orange":<br>
      drinkName = "Orangeade";<br>
      break;<br>
  }<br>
  
  orderText = `You have ordered a ${size} ${drinkName}.`;<br>
  
  return orderText;<br>
  
}
</code>

<h3>Calculator</h3>
<code>

 function calculator (firstNumber, secondNumber, operator) {<br>
  var firstNumber;<br>
  var secondNumber;<br>
  var operator;<br>
  let resultNumber;<br>
  
  switch (operator) {<br>
    case "+":<br>
      resultNumber = firstNumber + secondNumber;<br>
      break;<br>
    case "-":<br>
      resultNumber = firstNumber - secondNumber;<br>
      break;<br>
    case "*":<br>
      resultNumber = firstNumber * secondNumber;<br>
      break;<br>
    case "/":<br>
      resultNumber = firstNumber / secondNumber;<br>
      break;<br>
    case "%":<br>
      resultNumber = firstNumber % secondNumber;<br>
      break;<br>
    default:<br>
      resultNumber = "Undefined";<br>
      break;<br>
  }<br>
  
  return resultNumber;<br>
  
}
</code>
