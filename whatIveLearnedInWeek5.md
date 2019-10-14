# What I've Learned In Week 5
- DOM(Document Object Model)
  - .querySelector will grab element from html
  - .createElement will create new element
```javascript
// A function that takes in text and returns an `<li>` with that text as its `innerText`.
function append2(node){
    const node1 = document.querySelector("#ol");
    const li = document.createElement("li");
    node1.appendChild(li).innerText = node;
}

append2('whatever text I want');
append2('coding is fun');
append2('I just added another li to the ul');
  ```

### API
Application programming interface (API) - Code that is designed to be used by coders.
```
 Ex. You want information about Luke Skywalker. You can grab it from starwarsapi.com/lukeskywalker
 Weather - day of week will output information in response weather forecast for that day from weatherapi.com
 ```

 - Create a calculotar
 - Dry - Don't repeat yourself