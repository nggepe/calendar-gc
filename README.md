# GC-Calendar

Welcome to GEPCODE Calendar!
This is a calendar library for the web.

**Demo**

<img src="https://github.com/nggepe/calendar-gc/blob/master/docs/Animation.gif" style="max-width: 100%">

# Usage

For now, this plugin is dependent on the **jQuery library**.

**Basic Usage Example:**

```javascript
$("yourElement").calendarGC(options);
```

# Options

Our options provided for you to customize the calendar easier.

**Example**

```javascript
const option = {
  dayNames: ["sunday", "monday", "tuesday", "wednesday", "thursday", "friday", "saturday"],
};
```

## dayNames

You can use `dayNames` to replace your day name. We provide day name default like this.

```javascript
["Sun", "Mon", "Tue", "Wed", "Thu", "Fri", "Sat"];
```

if you want to write it as long name, you can replace that.

**Remember**
You have to write the `dayNames` from **Sunday** until **Saturday**

## monthNames

You can use `monthNames` to replace your month name. We provide month name default like this.

```javascript
[
  "January",
  "February",
  "March",
  "April",
  "May",
  "June",
  "July",
  "August",
  "September",
  "October",
  "November",
  "December",
];
```

These will show when the month you picked is on that number of month, so you have to short carefully

## nextIcon

Next icon is html that you can use for next button, the default is `&gt;`

## prevIcon

this is html that you can use for prev button, the difault is `&lt;`

## onPrevMonth

is the callback that will call when the prev button pressed.

**Example**

```javascript
const option = {
  onPrevMonth: function (pickedDate) {
    console.log(pickedDate);
  },
};
```

## onNextMonth

is the callback that will cal when the next button pressed.

**Example**

```javascript
const option = {
  onNextMonth: function (pickedDate) {
    console.log(pickedDate);
  },
};
```

## dateBegin

is the Integer that you can use for the beginning of date.
0 is Sunday
...
6 is Saturday

## events

this option is an array that you can build any events in spesific date.

**Example**

```javascript
const option = {
  events: [
    {
      date: new Date("2022-02-07"),
      eventName: "Holiday",
      className: "badge bg-danger",
      onclick(e, data) {
        console.log(data);
      },
      dateColor: "red",
    },
  ],
};
```

## Functions

Allows interaction with an existing calendar object to update the object inline.

### `setDate()`

Sets the active date and jumps the calendar to the month that contains the selected date.

```javascript
// Initialize the calendar object
let calendar = $("#calendar").calendarGC(options);
// Set the date and redraw the calendar
calendar.setDate("2023-01-01");
```

### `setEvents()`

Sets the list of events that are displayed on the calendar

```javascript
// Initialize the calendar object
let calendar = $("#calendar").calendarGC(options);
const events = [
  {
    date: new Date(),
    eventName: "Event #1",
    className: "badge bg-info",
    dateColor: "red",
  },
];
// Set the list of events and redraw the calendar
calendar.setEvents(events);
```

# Styling

You can also customize the style with your own css. See the `calendar-gc.css` when you need your own styling
