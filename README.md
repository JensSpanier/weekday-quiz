# Weekday quiz

What day of the week was this date? Take a quiz with this HTML file.

- You can download this file and open it with a browser to take the quiz
- Or you can selfhost this file to share it with other people

## Settings

You can change the settings to match your preferred language or between which dates the random date should be.

```js
const settings = {
  startDate: new Date('1950-01-01'),
  endDate: new Date('2050-12-31'),
  dateOptions: {
    locales: 'de-DE',
    options: {
      day: '2-digit',
      month: '2-digit',
      year: 'numeric'
    }
  }
};
```
