## skilled reflection  

With better words.

The *right* words will change  
  - your actions and 
  - your life.

It's time to live a better life.  
It starts with your words.

Read more in the [About](about.md) page.

## [Spring 2020 sessions](club_meetings.md)


## [you in 250](self250.md)  
What 250 words describe you? 

[how to do your first skilled reflection](self250.md)


## Contact 

Contact: 
skilledreflection at gmail dot com  
Instagram: [@skilledreflection](https://www.instagram.com/skilledreflection/)

<script>

var input_1 = 'How would your life look  if you put it on paper?'.split("");
var strike_1 = 'How <strike> would your life look if you put it on paper</strike>?';

var input_2a = 'How ';
var input_2 = 'do you get what you need and want?'.split("");
var strike_2 = 'How do you <strike>get what you need and want</strike>?' ;

var input_3a = 'How do you ' ;
var input_3 = 'clarify and direct your life?'.split("") ;

var text_speed = 30;
var step_dur = 200;
var text1_dur = 1000 ;

var loopTimer;
function textprint_1() {

  if(input_1.length > 0) {
    document.getElementById("type_text").innerHTML += input_1.shift();
    } else {
      clearTimeout(loopTimer);
      return false;
      }
    loopTimer = setTimeout('textprint_1()',text_speed);
    }

var update_text = function(new_text) {
document.getElementById("type_text").innerHTML = new_text
}

function textprint_2() {
  if(input_2.length > 0) {
    document.getElementById("type_text").innerHTML += input_2.shift();
    } else {
      clearTimeout(loopTimer);
      return false;
      }
    loopTimer = setTimeout('textprint_2()',text_speed);
    }

function textprint_3() {
  if(input_3.length > 0) {
    document.getElementById("type_text").innerHTML += input_3.shift();
    } else {
      clearTimeout(loopTimer);
      return false;
      }
    loopTimer = setTimeout('textprint_3()',text_speed);
    }

textprint_1();
setTimeout('update_text(strike_1)',2000); 
setTimeout('update_text(input_2a)',3600); 
setTimeout('textprint_2()',3800);

setTimeout('update_text(strike_2)',6000); 
setTimeout('update_text(input_3a)',6600); 
setTimeout('textprint_3()',6800);
 </script>
