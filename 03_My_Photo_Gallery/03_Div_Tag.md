The last new tag we took was `<style>` and that saved us from repeated code, so trust my when I saw we will have another life saving tag which is `<div>` 😍

`<div>` are written this way:

```html
<div>
  <! - - content - ->
</div>
```

We can imagen `<div>` like having another `<body>` within the actual one, this gives us a changes to control each section on its own without interfering with each other.

**Implementation Time!!!!**

We will implement it to wrap each topic:

![img](https://lh3.googleusercontent.com/Qzw_oG_ftD2SYna3iLpwMNW3nvBHEXnQPfnepS99dZdECa1on9lJu6gnZ7n4cRgSwV0P6kp2Xa4-f5pgUCaw4M_fWmGP7JPAMD-YNBbMi0-wMXjvqdEHJsmUxP3yMB7pD6piwMWD=s0)

I know what are you thinking,

**❓ Question:**

> What is the benefit of wrapping elements with `<div>`?

**🤓 Answer:**

> We can control a specific area of the page like this!!!!

![img](https://lh4.googleusercontent.com/Ds_3Eu-gUh1CajYl26SHGHiC9k3QlJgS8L4FSXnfzKStZRXMBeSb6h3rQf-TeXXaTWDh0phB5Za_In-yTL2fmS6F0qKuGxxrH8lAKpkU8k0csBkmbDEdXhqeq0neSW7NNeJdUIS7=s0)

AMAZING!!!!!!

We will fix it a bit with this code:

```css
div {
  background-color: azure;
  text-align: center;
  margin: 10px;
  padding: 5px;
}
```

So we can get this result:

![img](https://lh6.googleusercontent.com/Znv9ZwbhKkWUZ-Kr-9bl8oaEAPzHkT2H5-N1VYBK1W7EXlkFaigMtl4F451vuBpg9-iZHRfhPwoGBHz8ySxE4Q1xgCgzrnYJAmRww4Y2J6HdHw5Wfds0MntsyvfhpszBKBH-3JmV=s0)

**📝 Note:**

> `CSS`and `HTML` are case sensitive, which is given to the languages that take everything literally.

**Example:**

> `<div>` is not like` <dvi>`, it will not auto correct what is already written.
> This will be clearly shown in the next part. 👀
