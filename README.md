#### [Home](https://github.com/lukefisha/README.md.git)
#### Hometown
#### Hobbies
#### Family
# School and Degree
I go to University of Missouri Columbia and I am an Information Technology major. I am freshmen currently and right now I am taking two introductory courses. Below is one of my coding assignments. This is html code for fizzbuzz. For numbers 1-100 this program takes each number indivdually and if it is divisbile by 3 it says fizz, if it divisible by 5 it says buzz, and if it's divisible by both 3 and 5 it says fizzbuzz.
```html
	<!DOCTYPE html>
	<html>
	<head>
	<meta charset="UTF-8">
	<title>Fizz Buzz</title>
	<script>

	function fizzbuzz() {
		var display = document.getElementById('display');
		var displayHTML = "";
		var result = '';
		for (i = 1; i < 101; i++) {
		 if (i % 3 === 0 && i % 5 === 0) {
		result = "FizzBuzz";
		} else if (i % 5 === 0) {
		result = "buzz";
		} else if (i % 3 === 0) {
		 result = "Fizz";
		} else {
		 result = i;
	    }


	    displayHTML += "<p>" + result + "</p>";
		}
		display.innerHTML = displayHTML
	}

	</script>

	</head>

	<body onload="fizzbuzz()">
	<div id="display">

	</div>
	</body>

	</html>
```
