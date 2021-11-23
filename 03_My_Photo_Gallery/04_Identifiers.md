Do you remember when we talked about having “similar styling”, and thought that grouping them will solve everything.

**❓ Question:**

> What if we don't want everything to be similar, we want some unique details?

**🤓 Answer:**

> We will need some kind of identifier!

We have two things:

1. Classes
2. Ids

**❓ Question:**

> What's the difference between `classes` and `ids`?

**🤓 Answer:**

> Other then written in a different way, you can use the same class name for multiple elements

We will start with `class` then try `id` 💪🏻

**01_classes**

We can use `class` for styling `h3` to make their font larger.

**📝 Note:**

> In `CSS` to call a `class` and identify it we must put a `.` before the class name, like this:
>
> ```css
> .class-name{
>     ….
> }
> ```

Implementation Time!!!:

1. To do so, I will add `class: heading-3` to all the `<h3>`

   ![img](https://lh4.googleusercontent.com/L170z7T3W7v_AhyQB6u-9kELseootNuVP8TuiPqBCZC7LNG6m3NC8yyUtK8SsoUUKU_ONjVuaGrTrgwKoVH7LT6a_lKdRIVsuONnvOD5cFshygDEFKm8WwhB3Oiir_ec8XoaOgmT=s0)

2. Now we can go to the `<style>` to add the styling we want

   ![img](https://lh5.googleusercontent.com/Xj6JvbencAbEnh581JysDXoe_tDpjiRoM_nTo_VKDk_Y2mDtmVV5BR0Ifsy617k92V7JJe8w2EyYHkzjvW_fIHZoKQEwJKMy3E0CYyJ_7wt4CrXdNwgOLHu5U1gwNMxMg_HA7t_J=s0)

**📝 Note:**

> Choosing `classes` here was because we want the available `h3` only to change, adding more `<h3>` that do not have the same `font-size` if they do not have the same `class` name.

**02_ids**

Now, for `id` we will use it to give each `div` a color. Since we know that it makes each element unique, we will need 3 `ids`:

1. `div-1``
2. ``div-2`
3. div-3`

**📝 Note:**

> In `CSS` to call a `id`and identify it we must put a `#` before the class name, like this:

```css
#id-name{
    ….
}
```

**Implementation Time!!!:**

1. Like what we did with classes, first we add the id to each `div`

![img](https://lh6.googleusercontent.com/P6vQUPPh3gO_3niIam-fruz08wwC8PgSPYQAzRqKQCZzjOgmlPQszIN1QupT1de3Wpipo_396ks5bXXelIPeSLwHZCFqd9qKguUgqez6pnk7PvdMP1vuG-9q8louGxAb5MqokmBX=s0)

2. Remove the `background-color: azure;` from the `div` style, we will give each one a color.

3. Now we edit them in the `<style>` tag

![img](https://lh6.googleusercontent.com/kLjdM4ObXsRPA9N3_BYL8AKKxRslCkVlIz9x844vdpUUyTnyj_6xCBGnPdhqY8lO2ZMJfyEpwu-4UcgoLS4hGHn_AM9YD7_cJTF2NwjDVNKAE5kDq8STZb9M4yA8quubYId6ukfo=s0)

We notice now that `div-2` has sort of similar `background-color` to `div-1`, we can edit that without affecting all the other `div`s
