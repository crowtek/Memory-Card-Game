# Memory-Card-Game

## Here you can find a easy JavaScript learning Project from me









<!-- First Project -->
## Color-Flipper Project





In this Project I worked with Array functions to generate Random hex Values.<br><br>
 <br><br>
 
 ```JavaScript
const hex = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, "A", "B", "C", "D", "E", "F"];

const btn = document.getElementById("btn");
const color = document.querySelector(".color");

btn.addEventListener("click", () => {
    let hexColor = "#";
    for(let i = 0; i < 6; i++){
        hexColor += hex[Math.floor(Math.random() * hex.length)]
    }
    document.body.style.backgroundColor = hexColor;
    color.innerHTML = hexColor
})
```



<br><br><br><br><br><br><br><br>


<!-- CONTACT -->
## Contact

Meik Grünholz -  prt3@hotmail.de






