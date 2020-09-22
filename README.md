# jQuery Plugin - Text Scrambler

This plugin has a jQuery dependency. Make sure to have jQuery installed or linked through CDN.

<body>
      <h1 class="scramble" id="text1">Walter H. White</h1>
      <button id="btn1">char by char</button>
      <hr />
      <h1 class="scramble" id="text2">Jesse Pinkman</h1>
      <button id="btn2">Typewriter</button>
</body>


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