# Sublime Snippets for JavaScript Console Logging

## Clone Repo
cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/User<br />
git clone https://github.com/travishoki/sublime-js-console-logs

## Tab Triggers
The following are Sublime Text tab triggers that will produce snippets for styled console logs

#### Log
**cl** + Tab
```javascript
console.log('');
```

**Key and Value**<br />
**clv** + Tab
```javascript
console.log(': ' + );
```

**Object**<br />
**cld** + Tab
```javascript
console.log('');
console.dir();
```

**Header 1**<br />
**clh1** + Tab
```javascript
console.log('%c==========  ==========', 'font-size: 16px');
```

**Header 2**<br />
**clh2** + Tab
```javascript
console.log('%c-----  -----', 'font-size: 14px');
```

**Success**<br />
**cls** + Tab
```javascript
console.log('%cSuccess', 'color: green;');
```

**Error**<br />
**cle** + Tab
```javascript
console.log('%cError', 'color: red;');
```