var audio = document.getElementById('https://henrypersonalweb.github.io/play.mp3');

$("#btn").bind("touchstart", function bf() {

  

if(audio !== null) {

//alert(audio.paused);

if(audio.paused) {

audio.play(); //audio.play();

$("#btn").addClass("active")

} else {

audio.pause(); 
$("#btn").removeClass("active")

}

}

})