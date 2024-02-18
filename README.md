const body = document.querySelector("body");
const btn = document.querySelector("button");
let light = "light";


function darkmode() {
    if (light === "light") {
       light = "dark"
       body.style.backgroundColor = "black"
       body.style.color = "white"
    }else{
       light = "light";
       body.style.backgroundColor = "white"
       body.style.color = "black"
    };
};
