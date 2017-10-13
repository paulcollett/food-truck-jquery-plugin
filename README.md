# Food Truck jQuery plugin
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
### Not using jQuery?

You can use vanilla javascript too!

```JS
FoodTruck('.locations', {
  count: 3,
  empty: 'my custom message'
});
```

### Using Wordpress?

Manage you locations within your wordpress admin panel, with the simple Food Truck plugin:
https://wordpress.org/plugins/food-truck/

Once installed, you'll be able to use the features above!
