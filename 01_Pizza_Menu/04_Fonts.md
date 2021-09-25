It is time to change more than the text color 😎. We can change any text on the page, from their size,family type and text placement on the page.

**01_Font_size**

> The code: ```font-size: ...```
>
> Implementation:**⚠ Common Mistake:** 
>
> ![img](https://lh6.googleusercontent.com/BRRyrDJEG1DHby79ekAiQdeDZMhLSgc37v7pifIOk1siLx9Hhj-78SY6VzDcTLUvLj6e2381_51P204w9PVCa2_Ce2J457XlWbIKwzPHF6R0k2n_FVU9qFGUPvhe3WZIyY62GCCC=s0)
>
> **⚠ Mistake Fix:** 
>
> ![img](https://lh4.googleusercontent.com/TeN2K0r-wBOUWF3kyf6ygSfQ68tRSB22jA-tm_sYk_1Fo0ZoGUmQgAuZkzjDAoa0wuMcPjGytrqZosgWNzIP_FRbyWbgM2YF7dFuSvVAnGJDfOiOyIPh2-PhFzZuNlckXrADOL5Z=s0)
>
>  Mistake FIXED 😌 `Proud of you 👏🏻`, don't forget the `;` between attributes.

**02_Font_family**

The code: ```font-family: ...```

> Implementation:Changing 
>
> - `<p>` : 
>
> ![img](https://lh6.googleusercontent.com/XmW1NtmHHFzSdWPs2CIIyvOCQ6F0mxUQ7A9PmSEUyDMqDfCnTU-9dch9RNzBufDAg8PtjLMP1AsMlBC6p4ZISzGlCw9O7lKnYvrPpl9zN1b_HLWCXuJ-s2V_bG71qM1elBd7vfgd=s0)
>
> - Changing`<ul>`:
>
>   ![img](https://lh5.googleusercontent.com/USE-aRI2copZQch0pOoskMdVQQMDWzKNObfx6docnxVwXM4cneD7V8SbeASJuYijxK9e2vL0aAvt9PpFxTSFxx_LOhL9D_0QP1JFPrvN38waGwbip9kO7Vz7bq_KMT1mPU3178Pn=s0)

**📝 Note:**

> Notice how rather then editing the `font-family` for each `<li>`, we can do it for the whole list by putting it on `<ul>`. 😍

**03_Text_alignment** 

Ok this one you will love, I’m sure you are bored from things being only on the left. Now it's time to change that! 💪🏻

> The code: ```text-align: ...```

>  Implementation:
>
> - On `<h1>`:
>
>   ![img](https://lh5.googleusercontent.com/GaEBAL-coBjXwQ38Ty2mvXu5wQsSyUNqOS2BahSYkv5vsPWmEqKtBKLZIPhLgYSDLoNj-5SS0TD1MnmIjavq_rcWUYwOU-AnaSsPkObowcgII8AVWpeFsV0edqEUjqb6E99kvDy0=s0)
>
> - The whole `<body>`:
>
>   ![img](https://lh5.googleusercontent.com/XLVRs78as07gNJoLlaLuNWP7Te5fX0O9iYDIn5IaJ0DbZkm8eHZmQqYfD7TPwv5tnJ5bXSioUOWvShHS8ZnEzZPzz9dSpYEKQLqc1bmlSrhC8KPPG88ZDMB7zt69B8NUpnMWy2xy=s0)

**04_List_style** 

I think we both agree that the list built points are ruining the websites look 😬.

> Lets remove them by using this code: ```list-style-type: ...```
>
> Implementation: 
>
> - Directly on the `<ul>` rather on each item: 
>
>   ![img](https://lh3.googleusercontent.com/mDfSAcJynvbJjl3ejSGmCYB4wruI8MD2ZkyOYTjlaUgJqGlrrIQA1O_9mLL28USyfnAjzIW2DZXbdnPLH1O1iSid9T9cn_ZidoKJ4PdABdWKA8YFXm0GfJNDQDjweIxezPJGZIvH=s0)

**Source Code for the body:**

``````html
<body style="background-color: #eae2b7; text-align: center;">
    <h1 style="color: #003049 ;font-size:50px ; text-align: center;">Pizza Menu</h1>
    <img src="https://image.flaticon.com/icons/png/512/4812/4812106.png" alt="pizza icon" height="120px">
    <p
        style="color: #d62828 ; font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif; ">
        Welcome to my Pizza Menu website</p>
    <h4 style="color:#d62828">The pizza we have are:</h4>
    <!-- I used nested tags: -->
    <!-- Unordered List of 2 Items -->
    <ul
        style="font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif; list-style-type: none;">
        <!-- Each Item contains a heading and an image -->
        <li>
            <h5 style="color:#d62828;">Cheese Pizza</h5>
            <img src="https://www.insidetherustickitchen.com/wp-content/uploads/2020/07/Quattro-formaggi-pizza-square-Inside-the-rustic-kitchen.jpg"
                alt="Cheese Pizza" height="160px" width="220px">
        </li>
        <li>
            <h5 style="color:#d62828; ">Pepperoni Pizza</h5>
            <img src="https://food.fnr.sndimg.com/content/dam/images/food/fullset/2018/9/27/0/WU2004_Pepperoni-Pizza_s4x3.jpg.rend.hgtvcom.616.462.suffix/1538075335011.jpeg"
                alt="Pepperoni Pizza" height="160px" width="220px">
        </li>
    </ul>
</body>

``````

**Website:** 

**![img](https://lh5.googleusercontent.com/IgH7Fg3V_UKF7kOINwekzdrnNDIalgQOeRdKnrCSWf_2qdpaV_H_It-qR2WnfNwWTR4uGLSJVvNQMdTh3vqdN29CfI6W1BM-LN6HwBzsVLsx7PNeomlVt3bGqMvprddXAlTC50oK=s0)**

