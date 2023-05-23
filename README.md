# elkassir23.github.io
function calculateBMI() {
	const height = document.getElementById('height').value;
	const weight = document.getElementById('weight').value;

	if (height === '' || weight === '') {
		alert('Please enter your height and weight.');
		return;
	}

	const bmi = weight / ((height / 100) ** 2);
	document.getElementById('result').innerText = bmi.toFixed(2);
}

function calculateInterest() {
	const principal = document.getElementById('principal').value;
	const rate = document.getElementById('rate').value;
	const time = document.getElementById('time').value;

	if (principal === '' || rate === '' || time === '') {
		alert('Please enter values for all fields.');
		return;
	}

	const interest = (principal * rate * (time/12)) / 100;
	document.getElementById('interest').innerText = interest.toFixed(2);
}
