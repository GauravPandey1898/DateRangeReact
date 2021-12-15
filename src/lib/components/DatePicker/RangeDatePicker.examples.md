DatePicker examples:

###### RangeDatePicker

```js
import { RangeDatePicker } from 'react-google-flight-datepicker';

<div className="react-google-flight-datepicker">
  <div className="date-picker-demo">
    <RangeDatePicker
      // startDatePlaceholder="My from date"
      // onChange={(startDate, endDate) => console.log(startDate, endDate)}
      // onFocus={(inputFocus) => console.log(inputFocus)}
      startDate={new Date('2021-04-20')}
      endDate={new Date('2021-05-25')}
      // startWeekDay="sunday"
      minDate={new Date(2020, 6, 10)}
      maxDate={new Date()}
      dateFormat="DD/MM/YYYY"
      // monthFormat="MMM --- YY"
      highlightToday={true}
      disabled={false}
      isOpen={true}
    />
  </div>
</div>
```
