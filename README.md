# GC-Calendar

Welcome to GEPCODE Calendar!
This is calendar library for web.

# Usage

For now, we provide for **jquery library** first.
**Example:**
```javascript
$("yourElement").calendarGC(options)
```

# Options

Our options provided for you to customize the calendar esier.
**Example**
```javascript
const option = {
  dayNames: ['sunday', 'monday', 'tuesday', 'wednesday', 'thursday', 'friday', 'saturday']
}
```

## dayNames

You can use `dayNames` to replace your day name. We provide day name default like this.

```javascript
['Sun', 'Mon', 'Tue', 'Wed', 'Thu', 'Fri', 'Sat']
```

if you want to write it as long name, you can replace that.

**Remember**
You have to write the `dayNames` from **Sunday** until **Saturday**

## monthNames

You can use `monthNames` to replace your month name. We provide month name default like this.
```javascript
['January', 'February', 'March', 'April', 'May', 'June', 'July', 'August', 'September', 'October', 'November', 'December']
```
