# Qwirty

We've now covered the basics of HTML and CSS. Let's put it all together!
In this review activity, you will be recreating a standard e-commerce site.
You can visit [the live Qwirty demo](https://fsa-qwirty.netlify.app/) to see
the end goal. Get as close as you can!

## Instructions

1. Create a new repository under your GitHub account using this one as a template.
2. Open the cloned repository in VS Code.
3. Build!

## Tips

While you are free to tackle this however you'd like, here are some tips:

- Break the website down into smaller components and focus on completing each component.
- Use separate css files for each component to stay organized.
- Use a combination of flex and grid to arrange the elements on the page.
- Make frequent commits as you work.
- As a last resort, you can always inspect the live demo. However, try to build
  as much as you can from scratch first!

### Use an external font

[Google Fonts](https://fonts.google.com/) is a popular resource where you can get
external fonts to use in your website. After selecting a font, **get embed code**
to get `<link>` elements to add in the `<head>` of your HTML. Once that is done,
you can refer to the name of that font in the `font-family` property in your CSS.

### Use an icon font

Google Fonts also provides an [icon font](https://fonts.google.com/icons)!

1. Select an icon that you want to use.
2. Add the provided `<link>` element in the `<head>` of your HTML.
3. Add the provided CSS rule to your CSS.
4. Insert the icon as a `<span>` with the provided class.
   The text contents of that span should match the icon you want to use.

### Show or hide an element

You can use the CSS property [`display`](https://developer.mozilla.org/en-US/docs/Web/CSS/display)
to change the visibility of an element. By combining it with a pseudoclass like
`:hover` or a media query, you can make an element appear or disappear based on some condition.

```css
.example:hover {
  display: none;
}
```

## Submission

On Canvas, submit a link to your public GitHub repository.
