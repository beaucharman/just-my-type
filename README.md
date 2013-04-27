# Just My Type

**A typography reference, markup guide and stylesheet checklist.**

*A work in progress*

See **Just My Type** in action on [Codepen](http://codepen.io/beaucharman/pen/FDBIf).

Tag references from the awesome MDN. Images from Lorempixel.

A pretty wicked tool to use during and after CSS development is Harry Roberts' debug.scss, which is a part of the Inuit CSS framework.

### Todo

- Add in an actual checklist system.

### Usage

1) Grab the HTML from the `just-my-type.html` file and place it in a page of you project.

2) Place the `.jmt-section-heading` css in your porject so that each tag section is easily defined.

**Expanded version**

```css
.jmt-section-heading {
  background-color: #5185cc;
  font-family: sans-serif;
  color: #fff;
  display: block;
  padding: 0.1em 0.5em;
  position: relative;
}
.jmt-section-heading small, .jmt-section-heading code {
  color: #a0bce3;
  font-size: 15px !important;
}
h2.jmt-section-heading {
  font-size: 28px !important;
}
h3.jmt-section-heading {
  font-size: 22px !important;
}
h4.jmt-section-heading {
  font-size: 18px !important;
}
```

**Minified version**

```html
<style>
.jmt-section-heading{background-color:#5185cc;font-family:sans-serif;color:#fff;display:block;padding:.1em .5em;position:relative}.jmt-section-heading small,.jmt-section-heading code{color:#a0bce3;font-size:15px!important}h2.jmt-section-heading{font-size:28px!important}h3.jmt-section-heading{font-size:22px!important}h4.jmt-section-heading{font-size:18px!important}
</style>
```

3) Go ahead and check all your styles against the various HTML elements!