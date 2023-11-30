let textBoxElement = prompt('Please enter the element class'); 
let textBoxValue = prompt('Please enter the text you want'); 
let elements = document.getElementsByClassName(textBoxElement);
for (var i = 0; i < elements.length; i++) {
        elements[i].value = textBoxValue;   
}