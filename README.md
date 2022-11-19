# Randable (Random string generator with custom length in javascript)
Generate random string with mixed lowercase, uppercase and numbers to use anywhere (such as generating unique IDs or URLs).
## How to use
```javascript
import randable from 'randable'
```
<br />
After importing, you can use it like the syntax below (for example, generating random string of 5 characters length):

```javascript
randable(5) // ipEg1
```
```javascript
randable(12) // ofGnd1t5Lc8Z
```
### Notes:
* The default length for randable is 10
* The returned string only includes uppercase & lowercase letters with numbers. There's not any dashes, underscores or any other special characters.

## Disclaimer
* This is a public/general licensed package developed by [devban](https://www.devban.com), you're free to use & modify it anywhere in your projects. Feel free to suggest edits or add yours (pull requests)