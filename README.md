# To-Do-App
[Click Me](https://kaplanh.github.io/To-Do-App/)

![todo app](https://github.com/kaplanh/To-Do-App/assets/101884444/79ab9c46-9e64-437f-a3b8-89ed31afab80)

## Description

The project aims to create a Todo App using JS and Css.

## Problem Statement

- Your company has recently started on a project that aims to create a Todo App. So you and your colleagues have started to work on the project.

## Project Skeleton 

```
Todo App (folder)
|
|----readme.md                        
|----index.html
|----style.css
|----app.js
|----withCreateElement.js 
``` 


### At the end of the project, the following topics are to be covered;

- HTML
  - font-awesome
    ~~~css
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css"
      integrity="sha512-9usAa10IRO0HhonpyAIVpjrylPvoDwiPUiKdWk5t3PyolY1cOd4DSE0Ga+ri4AuTroPR5aQvXU9xC6qOPnzFeg=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
    ~~~
  - [html entities](https://www.w3schools.com/charsets/ref_html_entities_4.asp)
    ~~~css
    &plus;
    &copy;
    
    ~~~ 
  
- CSS
  - [google fonts]("https://fonts.googleapis.com/css2?family=Rajdhani:wght@500&display=swap")
   ~~~
   @import url("https://fonts.googleapis.com/css2?family=Rajdhani:wght@500&display=swap");
   ~~~ 
  - @media query

  

  
- JS
  - DOM Manipulations
    - innerHTML
    - innerText
    - textContent
     
  - DOM Selectors
  - querySelector
  - querySelectorAll
  - const productList = document.querySelector("div.main__product-painel"); //?basina div yazarak belirtirsek performans acisindan daha hizli olur
  -  Date() object [^1]
    [^1]: id: new Date().getTime(), //Date.now() anlik zamani alip unique id yapmak icin
    
  - Events
    - click
    - load
    - keydown
  
    ```
        todoInput.addEventListener("keydown", (e) => {
    if (e.key === "Enter") {
        btn.click();
    }
    })
    ```
  - Capturing & Bubbling
  - DOM Traversing
    - nextElementSibling
    - nextElementSibling
    - e.target.closest(".main__product-info")
    - if (e.target.classList.contains("fa-plus"))
    - e.target.previousElementSibling.innerText++;
    - firstElementChild
    - children
    - prepend [^2]
      [^2]:li.prepend(iCheck);
    - appendChild [^3]
      [^3]:span.appendChild(content);
   
  - localStorage 
    ```
     - localStorage.setItem("tasks", JSON.stringify(tasks));
 
     - tasks = JSON.parse(localStorage.getItem("tasks")) || [];
     
    ```
 
 
 
  
  - Array Methods
  - filter()
     ```

    tasks = tasks.filter((task) => task.id != id);
    }
  
    ```
  

  
  - if else - if - else  conditions


### At the end of the project, developers will be able to;

- improve coding skills within HTML, CSS and JS 

- use git commands (push, pull, commit, add etc.) and Github as a Version Control System.


## Notes

- You can use HTML, CSS and JS to complete this project.



<p align="center"> ⌛<strong> Happy Coding </strong> ✍ </p>



