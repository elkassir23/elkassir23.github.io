
<html>
<head>
	<title>BMI and Interest Rate Calculator</title>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<header>
		<h1>BMI and Interest Rate Calculator</h1>
	</header>
	<div class="calculator">
		<h2>BMI Calculator</h2>
		<label for="height">Height (cm):</label>
		<input type="number" id="height" name="height">
		<label for="weight">Weight (kg):</label>
		<input type="number" id="weight" name="weight">
		<button onclick="calculateBMI()">Calculate</button>
		<p>Your BMI is: <span id="result"></span></p>
	</div>
	<div class="calculator">
		<h2>Interest Rate Calculator</h2>
		<label for="principal">Principal:</label>
		<input type="number" id="principal" name="principal">
		<label for="rate">Interest Rate (%):</label>
		<input type="number" id="rate" name="rate">
		<label for="time">Time (years):</label>
		<input type="number" id="time" name="time">
		<button onclick="calculateInterest()">Calculate</button>
		<p>Your interest earned is: <span id="interest"></span></p>
	</div>
	<script src="script.js"></script>
</body>
</html>
