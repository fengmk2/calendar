
# Calendar

  Calendar UI component designed for use as a date-picker,
  full-sized calendar or anything in-between.

  ![javascript calendar component](http://f.cl.ly/items/043N1r0e1L130y162R2f/Screen%20Shot%202012-09-17%20at%209.17.32%20PM.png)

## Installation

    $ component install component/calendar

## Example

```js
var Calendar = require('calendar');
var cal = new Calendar;
cal.el.appendTo('body');
```

## Events

  - `prev` when the prev link is clicked
  - `next` when the next link is clicked
  - `change` (date) when the selected date is modified

## API

### new Calendar(date)

  Initialize a new `Calendar` with the given `date` shown,
  defaulting to now.

### Calendar#select(date)

  Select the given `date` (`Date` object).

### Calendar#show(date)

  Show the given `date`. This does _not_ select the given date,
  it simply ensures that it is visible in the current view.

### Calendar#prev()

  Show the previous view (month).

### Calendar#next()

  Show the next view (month).

# License

  MIT

