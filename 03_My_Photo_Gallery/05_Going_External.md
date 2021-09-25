I think you will agree with me when I say “Our code is getting too long!!”, and you are thinking “They said developers are neat organized people”. Please don't judge, we are here to fix this for our future developers. 

> The fix for this is the fix in mind, what about if `CSS` has its own page!!! 
>
> Lets imaging it together: ![img](https://lh4.googleusercontent.com/Q_c8y_kTYb6DlQle3itWxjb3Bk-vSP3Ss3U-xPhnCygy-B0nTGZPfNgx5MRJgfA_IWSaM0Nk2umddK2p8E6fQMGq4M3sFHMD3-cKrI6tU3dI7RBd_F9mf-ThbB7uRV-tFY7nYwEc=s0)

Implementation for this is great, be careful I'll trick you 😬 

> **Implementation :**
>
> 1. Create a `styles.css` file
> 2. Cut all what is inside the `<style>` tag (Without the `<style>`s)
> 3. Paste the styling inside `styles.css`
> 4. Remove the `<style>` from `HTML` `<head>`
> 5. SAVE all your work 

![img](https://lh3.googleusercontent.com/-pSwUxu_5h0L-V_H1gb1S2A2r9seUGa_ARx_xNr9TdV-GJVKXQQtSiur_xZghcLKdidUMzoEbdl7hhumKO1Gm5b-HDEOpz3DOGzAae2iEfKjau0_sFaHLSKPr3FIgVvlfSswFzq9=s0)

Lets see what happened to our page: 
DON'T FREAK OUT!! This was the trick and a common mistake!

**🚨 Common Issue:** 

> Some people forget to link the `index.html` and the `styles.css` together.
>
> How will the pooooor `HTML` know there is a `CSS` file? 

**⚠ Quick Fix:** 

> using a new tag to link them called `<link>`, I know so creative 😅

**Implementation:**

We will add the `<link>` inside the `<head>`, which looks like this:

``````html
<link rel="stylesheet" href="...">
``````

![img](https://lh6.googleusercontent.com/Nv_oiqbzfnF8qI_FQKhXyeh82yzqs5tIYLjkUrY7I9BdXQdW0c2-EktCwFYD9DyahlzXJRlXfarGDk_BXwEL9JVydRFTa_IQEaJpth1LrN9jAqKbKDnqQCdXo2XCXQBcawPwZ_OW=s0)

