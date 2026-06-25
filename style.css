/* 💌 Review Slider */

const reviews = document.querySelectorAll(".review");

let currentReview = 0;

setInterval(() => {

reviews[currentReview].classList.remove("active");

currentReview++;

if(currentReview >= reviews.length){
currentReview = 0;
}

reviews[currentReview].classList.add("active");

},3000);


/* 🌸 Hero Button Animation */

const button = document.querySelector(".hero button");

button.addEventListener("click", () => {

button.innerHTML = "✨ Welcome To Chai House ✨";

setTimeout(() => {

button.innerHTML = "🌸 Explore Our World 🌸";

},2000);

});


/* ✨ Floating Sparkles */

function createSparkle(){

const sparkle = document.createElement("div");

sparkle.innerHTML = "✨";

sparkle.style.position = "fixed";
sparkle.style.left = Math.random() * window.innerWidth + "px";
sparkle.style.top = "-20px";
sparkle.style.fontSize = (Math.random() * 20 + 15) + "px";
sparkle.style.pointerEvents = "none";
sparkle.style.zIndex = "999";
sparkle.style.opacity = "0.8";

document.body.appendChild(sparkle);

let pos = -20;

const fall = setInterval(() => {

pos += 2;

sparkle.style.top = pos + "px";

if(pos > window.innerHeight){

clearInterval(fall);

sparkle.remove();

}

},30);

}

setInterval(createSparkle,1500);


/* 🦋 Cute Hover Glow For Menu Cards */

const cards = document.querySelectorAll(".card");

cards.forEach(card => {

card.addEventListener("mouseenter", () => {

card.style.boxShadow =
"0 15px 35px rgba(255,182,193,0.6)";

});

card.addEventListener("mouseleave", () => {

card.style.boxShadow =
"0 10px 25px rgba(0,0,0,0.08)";

});

});


/* 🌷 Welcome Message */

window.addEventListener("load", () => {

setTimeout(() => {

alert(
"🌸 Welcome to Chai House 🍵\n\n✨ A magical place filled with tea, flowers and happiness ✨"
);

},1000);

});
