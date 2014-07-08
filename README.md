gutabslider
===========

Animated underline for active tabs

## Basic usage

Just call `$("#my-tabs").gutabslider();` to get started

Call `$("#my-tabs").gutabslider("active-tab-changed");` to let us know the active tab has changed. We'll find the new active tab and move the underline to it

## Lets animate

To animated the underline just use CSS... to make it slide just add the following

```css
.gu-sliding-bar {
    -webkit-transition: all 0.2s ease;
    -moz-transition: all 0.2s ease;
    transition: all 0.2s ease;
}
```

