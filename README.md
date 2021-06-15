# Default Emoji Visuals

How Emojis look with default font on different devices and browsers

## Source

All fully-qualified emojis from:
https://unicode.org/Public/emoji/13.1/emoji-test.txt

## TODO:

1. Test with BrowserStack and capture results.
2. Write script to compare results and create a report like: https://unicode.org/emoji/charts/full-emoji-list.html
3. Github Page for the report
4. Automate all steps including "update from source", "testing" and "report generation" stages and run them in a schedule.
5. Add support for test in popular websites and apps (if possible with BrowserStack or similar services)

## Motivations

1. Find the most and least stable looking emojis across devices, also per device-usage (stats like caniuse.com)
2. Usefull for deciding whether to implement an emoji picker and use a custom font/img-pack scenario for normalizing across-devices OR go with the native support.
