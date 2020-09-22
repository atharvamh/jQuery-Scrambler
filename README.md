# jQuery Plugin - Text Scrambler

This plugin has a jQuery dependency. Make sure to have jQuery installed or linked through CDN.

<h3> Usage </h3>

// javaScript

1. Character by Character Effect

$("#btn1").click(function(){

       $("#text1").scrambler({
              effect: "charbychar",
              final_text : "Heisenberg",
              speed: 50,
              reveal: 100    // number of miliseconds to reveal one character
     });
});


2. Typing Effect

$("#btn2").click(function(){

      $("#text2").scrambler({
      	effect: "typing",
      	final_text: "Breaking Bad",
      	speed: 50,
      	reveal: 50
        });
});