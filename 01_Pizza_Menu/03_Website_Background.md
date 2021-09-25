Do we really wanna make our background jealous of our text, that's why we need to mix it up with the background too using inline styling. 

**01_Background_colors**

The same thing we did with `headings` and `paragraphs`will be done with background, 

LET'S DO THIS! 🔥

> This time we are not writing ``color`, rather then that we will say `background-color`
>
>  Give it a try: ![img](https://lh4.googleusercontent.com/GbcYWle1wOxrzBw_aJp2lv6K4_LnEwE1tbbwbe3ybBGFpKsHoh0DdqsiQGG93wxm5BtfLjasGnwjRJXyk4B1nwlaG4KrZBfQj_4EqXDkniRPsyXT_CsBD933hU53aIZdouAML9uO=s0)

**❓ Question:** 

> What if we want the full background? 

**🤓 Answer:** 

> Try the body, we are putting everything inside it after all. See this: 

![img](https://lh6.googleusercontent.com/VZSO8qwgiexf4dpFyqWHNE70jQs4UJPTknY19W8gCvspPWlKlgxmbTSQ7m6cfxUMeJerKEoPhq-zhfZ-6eyu-_erqTYcvcvYbsMifvRNTQ7TCmkZpHA4yRvz6QJLpPQ6BaEMaR7w=s0)

**02_Background_image**
Not all websites need a background image, but it's good to know how they are added. 

> Code in this case would be:
>
> ``````html
> <body style="background-image: url(https://i.pinimg.com/originals/b1/11/ed/b111edfe5c2376e01ee1a570ddcdbbbe.jpg);">
> .
> .
> .
> </body>
> ``````

To have this result: 

![img](https://lh4.googleusercontent.com/Trjg7SHqMeQHaXYaFCLNwTLBbhKc9BZAzpGZGcQcYFrlFyHdknV_cj3rl1EYLC5PK2tpBa9Hfk-NEEZwn1S5XpyDQQgvvWdHEroBDmu-0jvxeI5EUALMqwHmmxOK1wZ3pH3iiDPa=s0)

**📝 Note:** 

>  For more resources on how to control the image background in all cases, I encourage you to read it from [here](https://www.w3schools.com/css/css_background_image.asp).

**03_Palette_fixing**

Before continuing further, Let's fix the colors before someone gets hurt 😂

> Palette codes are: 
>
> - `<h1>` : `#003049`
> - `<h4>` , `<h5>`, `<p>` : `#d62828`
> - `<body>` :`#eae2b7`

**Source Code for the body:** 

``````html
<body style="background-color: #eae2b7;">
    <h1 style="color: #003049">Pizza Menu</h1>
    <img src="https://image.flaticon.com/icons/png/512/4812/4812106.png" alt="pizza icon" height="120px">
    <p style="color: #d62828">Welcome to my Pizza Menu website</p>
    <h4 style="color:#d62828">The pizza we have are:</h4>
    <!-- I used nested tags: -->
    <!-- Unordered List of 2 Items -->
    <ul>
        <!-- Each Item contains a heading and an image -->
        <li>
            <h5 style="color:#d62828">Cheese Pizza</h5>
            <img src="https://www.insidetherustickitchen.com/wp-content/uploads/2020/07/Quattro-formaggi-pizza-square-Inside-the-rustic-kitchen.jpg"
                alt="Cheese Pizza" height="160px" width="220px">
        </li>
        <li>
            <h5 style="color:#d62828">Pepperoni Pizza</h5>
            <img src="https://food.fnr.sndimg.com/content/dam/images/food/fullset/2018/9/27/0/WU2004_Pepperoni-Pizza_s4x3.jpg.rend.hgtvcom.616.462.suffix/1538075335011.jpeg"
                alt="Pepperoni Pizza" height="160px" width="220px">
        </li>
    </ul>
</body>

``````

**Website:** 

![img](https://lh6.googleusercontent.com/uOPQQEPyUxX6X_dA3QXrz9GdJN0CCw1-mrk7cdsuBx0-okl5G40VH5sC9_Kw8AZwygpn8llUddkAN0MWh9Qrmd20-p8fOeW0qpYFTO-tE7eBMZka5DVW_-WKZx1JJQccC7OtM7zn=s0)

