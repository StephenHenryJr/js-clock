# js-clock

Clock created using JS and CSS

- CSS transform-origin was new and what determines where the transition will start from
In this case it’s 100% meaning it will start at the end of the shape vs the middle which is the default 

- div’s are left to right so we transform: rotate the hands 90deg in order to get them at 12:00

- transition-timing function was cool and what was used to get the hands to tick like a clock, specifically the second hand 

- when calculating the degrees in JS, we need to add 90deg because otherwise it will rotate based on it’s original position which is 9:00. By adding 90deg to the equation we take that into consideration and ensure the degrees being rotated are based off a starting position of 12:00 

Thank you :) 
