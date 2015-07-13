// C to F

var tempc = prompt ("Please type a temperature in Celcius.")

var far = Math.ceil(tempc * 1.8 + 32);
alert('Your temperature in Fahrenheit is ' + far);

  // F to C

var tempf = prompt ("Please type a temperature in Fahrenheit.")

var cel = Math.ceil((tempf - 32) /1.8);
alert('Your temperature in Celcius is ' + cel);
