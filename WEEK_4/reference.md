
SCRIPT

(function () {

    var names = ["Yaakov", "John", "Jen", "Jason", "Paul", "Frank", "Larry", "Paula", "Laura", "Jim"];
    for (var i = 0; i < names.length; i++) {
      var firstLetter = names[i].charAt(0).toLowerCase();
      if (firstLetter === 'j') {
        spp.speak(names[i]);
      } 
      else {
        sp.speak(names[i]);
      }
    }
    
    })();



SPEAKGOODBYE


var spp={};
spp.speak = function (name) {
  console.log("Good Bye " + name);
}


SPEAKHELLO

var sp={};
sp.speak = function (name) {
  console.log("Hello " + name);
}