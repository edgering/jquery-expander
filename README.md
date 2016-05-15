# element expander - jQuery plugin

Auto adding expand button which can toggle between predefined minimum and full height of elemnt. 

- Works with `em`,`px` units 
- Displaying only if usable

```html
<div class="wrap" data-height="3em" data-view="view all" data-hide="hide me">
... content ...
</div>
```

Adding plugin:

```jquery
$(".wrap").expander();
```
