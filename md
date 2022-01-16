var itemlist=document.querySelector('#items');
//parent node
console.log(itemlist.parentNode);
itemlist.parentNode.style.backgroundColor='#f4f4f4';
console.log(itemList.parentNode.parentNode.parentNode);
// parent Element
console.log(itemList.oarentElement);
itemList.logparentElement.style.backgroundColor='#f4f4f4';
console.log(itemlist.parentElement.parentElement.parentElement);
// nextsibling
console.log(itemList.nextSibling);
// nextelementsibling
console.log(itemList.nextSibling);
// previousSibling
console.log(itemList.prevousSibling);

// createElement
// create a div 
var newDiv=document.createElement('Div');
// add class
newDiv.className='hello';
// add id
newDiv.id='hello1';
// add attribute
newDiv.setAttribute('title','hello div');
