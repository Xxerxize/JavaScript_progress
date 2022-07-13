# JavaScript_progress
JavaScript projects
>>>> The Switch statement <<<<<< 
const day = 'wednesday';

switch(day) {
case 'monday':
	console.log('plan survey work with the surveying team');
	console.log('Go to a coding meetup');
	
	case 'tuesday' :
		console.log('take cooking classes');
		break;
		case 'wednesday':
			case 'thursday':
				console.log('practice getComputedStyle, work on projects for 12 hours');
				break;
				case 'friday':
					console.log('Visit the family and record videos');
					break;
					case 'saturday':
						case 'sunday':
							console.log('Practice more coding');
							break;
							default:
								console.log('check for day!!!')
}

if (day === 'monday') {
	console.log('plan survey work with the surveying team');
	console.log('Go to a coding meetup');
}else if (day ==='tuesday'){
	console.log('take cooking classes');
}else if (day === 'wednesday' || day === 'thursday'){
	console.log('practice getComputedStyle, work on projects for 12 hours');
}else if (day === 'friday'){
	console.log('Visit the family and record videos');
}else  if (day === 'saturday' || day === 'sunday'){
	console.log('Practice more coding');
}else{
	console.log('check for day!!!')
}



>>>GUESS THE CORRECT NUMBER<<<<<

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">

    <title>Number guessing game</title>

    <style>
      html {
        font-family: sans-serif;
      }

      body {
        width: 50%;
        max-width: 800px;
        min-width: 480px;
        margin: 0 auto;
      }

      .lastResult {
        color: white;
        padding: 3px;
      }
    </style>
  </head>

  <body>
    <h1>Number guessing game</h1>

    <p>We have selected a random number between 1 and 100. See if you can guess it in 10 turns or fewer. We'll tell you if your guess was too high or too low.</p>

    <div class="form">
      <label for="guessField">Enter a guess: </label>
      <input type="text" id="guessField" class="guessField">
      <input type="submit" value="Submit guess" class="guessSubmit">
    </div>

    <div class="resultParas">
      <p class="guesses"></p>
      <p class="lastResult"></p>
      <p class="lowOrHi"></p>
    </div>

    <script>

      // Your JavaScript goes here

    </script>
  </body>
</html>
