# Gradient Color Generator

[![https://i.imgur.com/JtGsC7g.gif](https://i.imgur.com/JtGsC7g.gif "https://i.imgur.com/JtGsC7g.gif")](https://i.imgur.com/JtGsC7g.gif "https://i.imgur.com/JtGsC7g.gif")

### 📄 Content 
In this project a gradient color generator is developed using HTML, CSS and JAVASCRIPT technologies. The generator allows you to choose the color you want as well as the direction of the color gradient. It has a button to give different random colors, as well as a button to copy the code of these.

The concepts put into practice in this project are different:
- [EventTarget: addEventListener() method](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener "EventTarget: addEventListener() method")
- [if...else](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Statements/if...else "if...else")
- [Arrow function expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions "Arrow function expressions")
- [Event reference](https://developer.mozilla.org/en-US/docs/Web/Events "Event reference")
- [Event: target property](https://developer.mozilla.org/en-US/docs/Web/API/Event/target "Event: target property")
- [HTMLStyleElement](https://developer.mozilla.org/es/docs/Web/API/HTMLStyleElement "HTMLStyleElement")
- [Navigator: clipboard property](https://developer.mozilla.org/en-US/docs/Web/API/Navigator/clipboard "- Navigator: clipboard property")
- [Template literals (Template strings)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals "Template literals (Template strings)")

We use the template literals to be able to give the values of the strings and implement them in the change of the background and at the moment of showing the code of the gradient color to the user:
```javascript
const generateGradient = (isRandom) => {
    if(isRandom){
        colorInputs[0].value = getRandomColor();
        colorInputs[1].value = getRandomColor();
    }
    // Creating a gradient string using the color input values
    const gradient = `linear-gradient(${selectMenu.value}, ${colorInputs[0].value}, ${colorInputs[1].value})`;
    gradientBox.style.background = gradient;
    textarea.value = `background: ${gradient};`;
};
```


<h3 align="left">Languages and Tools</h3>
<p align="left"> <a href="https://www.w3.org/html/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> </p>

### ✒️  Autor
- [Tristan Venegas](https://github.com/TG-VA "Tristan Venegas") - Front end Developer.

# Generador de colores degradados

[![https://i.imgur.com/JtGsC7g.gif](https://i.imgur.com/JtGsC7g.gif "https://i.imgur.com/JtGsC7g.gif")](https://i.imgur.com/JtGsC7g.gif "https://i.imgur.com/JtGsC7g.gif")

### 📄 Introducción
En este proyecto se desarrolla un generador de colores degradados con las tecnologías HTML, CSS y JAVASCRIPT. El generador te permite escoger el color que deseas al igual que la dirección del degradado del color. Tiene un botón para dar diferentes colores random, al igual que un botón para copiar el código de estos.

Los conceptos que se ponen en práctica en este proyecto son diferentes:
- [EventTarget: addEventListener() method](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener "EventTarget: addEventListener() method")
- [if...else](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Statements/if...else "if...else")
- [Arrow function expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions "Arrow function expressions")
- [Event reference](https://developer.mozilla.org/en-US/docs/Web/Events "Event reference")
- [Event: target property](https://developer.mozilla.org/en-US/docs/Web/API/Event/target "Event: target property")
- [HTMLStyleElement](https://developer.mozilla.org/es/docs/Web/API/HTMLStyleElement "HTMLStyleElement")
- [Navigator: clipboard property](https://developer.mozilla.org/en-US/docs/Web/API/Navigator/clipboard "- Navigator: clipboard property")
- [Template literals (Template strings)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals "Template literals (Template strings)")

Utilizamos los template literals para poder dar los valores de las cadenas e implementarlas en el cambio del background y al momento de enseñar el código del color degradado  al usuario:
```javascript
const generateGradient = (isRandom) => {
    if(isRandom){
        colorInputs[0].value = getRandomColor();
        colorInputs[1].value = getRandomColor();
    }
    // Creating a gradient string using the color input values
    const gradient = `linear-gradient(${selectMenu.value}, ${colorInputs[0].value}, ${colorInputs[1].value})`;
    gradientBox.style.background = gradient;
    textarea.value = `background: ${gradient};`;
};
```

<h3 align="left">Tecnologías y herramientas</h3>
<p align="left"> <a href="https://www.w3.org/html/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> </p>

### ✒️  Autor
- [Tristan Venegas](https://github.com/TG-VA "Tristan Venegas") - Front end Developer.