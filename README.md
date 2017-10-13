# food-truck-jquery-plugin
jQuery plugin for listing food truck schedules

Possible interface:

```HTML
<div class="container">
<template class="locations">
{name}
{date}
{map}
{address}
</template>
</div>
```

```JS
jQuery('.locations').foodtruck({
count: 3,
empty: 'My custom message' // ..or selector
});
```
