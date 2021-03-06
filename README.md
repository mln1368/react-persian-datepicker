# react-persian-datepicker

**persian-react-datepicker** is a React.js component that helps you create datepickers based on Persian calendar.

**[See the demo here](http://mohebifar.github.io/react-persian-datepicker/)**

![Screenshot](https://www.dropbox.com/s/m4ryf0jxs4ce4wf/calendar.png?dl=1)

## Installation

You can install this package using `npm`:

    npm install --save react-persian-datepicker
  
It would be easy to destruct Calendar component from the package:

```es6
import { Calendar } from 'react-persian-datepicker';
```

## Basic Calendar

You can create a persian date picker by using the `Calendar` component. The `props` are as following:

* onSelect: Invoked when a date is selected and the `moment` object will be passed.
* prevMonth: The element for navigating to the previous month button.
* nextMonth: The element for navigating to the next month button.
* month: The default shown month on the date picker.
* min: The minimum selectable date. It can be a `Date` or `moment` object.
* max: The maximum selectable date. It can be a `Date` or `moment` object.
