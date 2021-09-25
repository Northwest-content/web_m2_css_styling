**❓ Question:** 

> Did you notice that the list is not really centered 🤔? To solve this we need to understand something called the `Box Model`, it will help us look deeper. I hope you remember how to `inspect` websites, we will need it in this section. 
>
> `Box Model`:
>
> ![img](https://lh4.googleusercontent.com/7mKMnZwFyW3JTEMcMdv83Ppb7vy0tl8ggypf3-8dySc9tSgm0VtDubVb1tKq3DGGFbEIvk4b2rntxr3CDfndy_h1zYWlRvfvAHZiTLOeyMwSdp7tHZeO09wX7_Z2zG0sErHQlIUv=s0)
>
> We will focus on `margin` and `padding` first 🔥

**📝 Note:**

> `border` is something is implemented by you as developer, we will create some in our next project 😁

**01_Margin**Margin is the part that is between elements and each other: ![img](https://lh5.googleusercontent.com/9hzkRb7F4mZYDGwCbLkvNeINKtq9j63IvFyQtU2XlCcgmzIQVyWVa59hzUVF4CTM3V2qoLgoVld0M7KKLfBDn8l8_51Vuk6FfO70yitFxE_3Q16zdc1eoXlouQ1U6I0vUQT-zojb=s0)**📝 Note:** 

> Most elements start with defaulted number of `margin`Lets see it in action using `inspect`: ![img](https://lh6.googleusercontent.com/u2wbbIfroaDnWZDcPSmJOJ9K0Ju4PGHagvZiJvOBe9MJJHRBuk8FWO1eurp2Rytkofh39_2y--lhojNF5GnLcY5t1u-uch5BMLdD2IRTN3hAypXJ8QjagypNT08KnNdyA5WmqxxW=s0)
>
> `margin` has an orange color, try to do it with other elements 😌

**02_Padding**

Padding is the part that is between the element and the `margin`:![img](https://lh3.googleusercontent.com/ml7qYaRIH1Le2PrMT1hLVAWzn9qJLo2tmTtOQo8Q8VGDnlUXgZqA_kKxrN07-4rjv0YYGs9Gxcvv2JAgZGy9fEvou8BERxQK6i5Gm9CYIemJx-8_5GHcbEujIsNY41_aduXzHGY1=s0)**📝 Note:** 

> Most elements start with `padding: 0px`, little that has a value. Lets see it in action using `inspect`: ![img](https://lh6.googleusercontent.com/iWLKxfczPrbRkurOft2SmGZzeGcTj4q6FDjD9X14LGy8NaNYCcakj5X4BmMfWy6n2_1eHRtvMgPCsqSQkqBnSW6ZYj0iIe49AgEdSzdYNIdOrZ8lLudHn_v6xpfEOUG5-CTrhTcV=s0)`padding` has an green color, try to do it with other elements 😌

**03_Box_Implementation**

Here we will do the following: 

- Remove the `padding` from `<ul>`

- Adding `margin` between the button and the last image 

- Adding `padding` between `<li>` elements> 

  Let's DO THIS!!!!

  1. **Remove the `padding` from `<ul>`**![img](https://lh5.googleusercontent.com/xTDN1YO2_7puu1NjLA3UaeALqsRksnbA4XjvmPy8eUMNerm-ynH8Lct10BxtbGnXe-0JlDYu5DZffeyXdWFFfDldhlPJ3UHg3pm0kHM1ls3jgnRUE4ZPTIG2keqqQGcAX1_u9lM5=s0)**Code:** 

     ``````css
     ul {
         padding: 0px;
     }
     ``````

     

  2. **Adding `margin` between the button and the last image**

     ![img](https://lh4.googleusercontent.com/kpEJhEa_DJ229IoBdSpx1vQKfRXjS903OiTEP4KP75Kn9EKTQfp3jiNGtGbZkeyGDtf-Rw6ud04ybX06EuZISPTEV51h6UNDCrTayGisqUyJWJhzM0v8OJhONvnSmMVbWEXAU77y=s0)

     **Code:** 

     ``````css
     button {
         margin: 20px;
     }
     ``````

     

  3. **Adding `padding` between `<li>` elements**

     ![img](https://lh4.googleusercontent.com/pXThXnRQgQ6xu8U_PcmwozRUJEgQLvym-cWlw0WIQQhXFxhfIreRMuNe9fMK5BXZanhWUD1Cs3JdwToLqVwxdUKIMAPhJX2tj5giniFWtiU6cVWcmsoVad6mvBc6J2Dflq4_roFz=s0)

     **Code:**

     ``````css
     li {
         padding: 10px;
     }
     ``````

 What a nice thing to not edit each element individually, `<style>` tag saved us!!! 😍