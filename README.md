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
