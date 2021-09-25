**01_Pizza_menu_layout**

I hope you are hungry, because in this section we will create a `Pizza Menu`. You can choose any menu type you want, I will not control your hunger 😁This is just writing the website base, you are a storing `HTML` writer so this is just a refresher to you 💪🏻.

**🔁 Reminder:** 

> Create a folder and name it `myMenu`, hopefully you remember the camel case in naming your website. 

> Your first page is called `index.html`, this is the last time I will bother you with this. I’m sure you already know it 😎.

> You will need to clean up the `html:5`

> Don't forget saving and refreshing, when you copy the path to the browser

> You are a tag master, so try to recreate this without looking at the source code 👀:

![img](https://lh5.googleusercontent.com/oxUOl6ySPs8Zi3u7D4eoyOpRaQ58K_QsPyPl6foM7hx3mJYjS9JvrbjuiueR3xyK-ng-9_LB6pPZ8xL2IpmWCUdBxjsO5Nc4FJ8YYKPtKmPA6BreBzRnbsIO7C-9Vy7itMhnKSS5=s0)

> Source Code with some comments:

```html
html<!DOCTYPE html><html lang="en"><head>    <title>Pizza Menu</title></head><!-- All images have public source 🤫 --><body>    <h1>Pizza Menu</h1>    <img src="https://image.flaticon.com/icons/png/512/4812/4812106.png" alt="pizza icon" height="120px">    <p>Welcome to my Pizza Menu website</p>    <h4>The pizza we have are:</h4>    <!-- I used nested tags: -->    <!-- Unordered List of 2 Items -->    <ul>        <!-- Each Item contains a heading and an image -->        <li>            <h5>Cheese Pizza</h5>            <img src="https://www.insidetherustickitchen.com/wp-content/uploads/2020/07/Quattro-formaggi-pizza-square-Inside-the-rustic-kitchen.jpg"                alt="Cheese Pizza" height="160px" width="220px">        </li>        <li>            <h5>Pepperoni Pizza</h5>            <img src="https://food.fnr.sndimg.com/content/dam/images/food/fullset/2018/9/27/0/WU2004_Pepperoni-Pizza_s4x3.jpg.rend.hgtvcom.616.462.suffix/1538075335011.jpeg"                alt="Pepperoni Pizza" height="160px" width="220px">        </li>    </ul></body></html>
```

**01_Prettier**

Ok we need to talk guys, I will be honest with you. Developers love neat codes, and you are one of us now that's why I will show you something cool that organizes your code once you save it.

> We will use VS code extensions, there are some things you download from VS code itself that improve your performance and help you code faster.
>
> We will introduce `Prettier`, and try it together.
>
> **Steps to download Extensions:**
>
> 1. Open the extensions bar. ![img](https://lh3.googleusercontent.com/SAHAAdkjgzwacxC0jKSAzj98CAKGXJeQ6OLzzAKva6F9QjPsR5lRZa07gSB2Znz55WxzvAr349uGHAQNfmhIgmKLgHejHjY9G9XhytjxgUQKkqu4JS_X9L89aARYhPn3GkDQPumX=s0)
>
> 2. Type `Prettier` in the search bar
>
> 3. Pick the wanted extension 
>
> 4. Press `Install`![img](https://lh3.googleusercontent.com/wzn7rpPm3vSKbosriL8dbXeP0ZVjsYp90-HzL_rGoyQkt92ie5fmxtocPN5eRY-LeRGI6bpkG3ttVmO0jIaNg_v67TeYalZWcKI-v1oy1Ak33EgvcITUC9MkArZXhK2PyD3XixKg=s0)
>
> 5. Let us tested with a messy code: ![img](https://lh5.googleusercontent.com/Z5Vw9tx14vPjGuR-sb_cimM8TaZsnr3k6kCbQwLCOdpo1Qlqgnu-qts5Z_CERYgY9IPuRn3v4kDpbz_4KCq2m_gjny34SPi2A9Cb0hhvrKmpftaE-UgQwRVp-ElxzyvGlKYhV6N1=s0)
>
>     We LOOOOVE a code that gets organized by just saving it!!! 😍

**🚨 Common Issue:** 

> When I save nothing changes, I'm sad 😢! 
>
> Do the steps : `ctrl + ,` on windows, or `command + ,` Write in the search `on save`Check the `Format On Save `![img](https://lh3.googleusercontent.com/04AGqVQssLbwvB38Vb4qE9PoiQXDma4YY9vVKVSJyuRe9LpNY_Bg5KdGUww-6l8oHtuF179RMKOCPwp0Pa28Z5ESIDtg-V4ipIZLK3F-MLAQtkMLwAfp7ff1NDRIZ8xGiVEosmL5=s0)Now it should work, we got you 😎

**📝 Note:** 

> If you still have issues with formatting, then thi is another way to activate prettier: 
>
> 1. Go to settings 
> 2. Type in the search `default formatter`
> 3. Pick prettier from the options

![img](https://lh3.googleusercontent.com/FLgdzY47lc7jIQ35snf4lJWYGTjleTbFBP6xw07LIG8mLbt9_N-QhQwXXtjk25MSQtn6lpRUqeK6jFncQUGrcdRnNdh_86O5Ik8ZWN6a843aHIBgaB79LTkUjaTxVgLnOZSS5U0y=s0)

Now you are in the clear ✔

**02_Live_Server**

SOOO, since you are one of us now we will give you another cooler extension! This one will not let you `copy path` and put it in the browser again. 

> This one is called `Live Server`, just follow the same steps![img](https://lh6.googleusercontent.com/RYcWht_FGTgsCRIewT3YdxfIGZsgQbLrpXNT6-Jg6fzCUsK55J3EImsB2IKJs8M53bes0S4HwTHaiiSGcX36jkGMM8zKxPP0yAC-7LuURJYZBN24kKgZ9O3g5TPQl7Ks9YinOz8-=s0)Then `right click` your `index.html`, and choose `Open with Live Server`![img](https://lh3.googleusercontent.com/4If0IEJf150HByxSx1rtEbH9wVTE_sE02KsBguU-q--4BwYFMHwo5yU0d5c9MjRnpjmrs5pmRV0P5viaRgBKoIlB2-t9im_DFMTyx_44kLop4Krd9l4wkwk3pjkU6Wfi8i6_Wod9=s0)Now you can do this just by saving your changes!!!!! 😍: ![img](https://lh4.googleusercontent.com/t1EXxtzovH1DLxQNIkfipY9xBvkTlaUmNn8Htk2qjVy2cZMpu5TP5aXA2MATbw-ESgq1FApJGWPKV_ig41Axmh8OtcANkUQ4FocpBDI7R_drN_3rI9vyxroAy_01RLV5Yj30vIVi=s0)

**📝 Note:** 

> See how the path changed, this website will only work when VS code is open on this folder. Otherwise this page does NOT work, but we can finally save and see our changes directly without refreshing!!! 😎

