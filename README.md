# KIT Locker
Light and easy way to prevent browser window from scrolling

### Demo
:tada: - https://natteke.github.io/kit/locker/demos/

## Installation
### CSS
```HTML
<link rel="stylesheet" href="/styles/kit.locker.min.css">
```
### JS
#### Initiation
```javascript
kit.locker.createLocker();
```

Or with callbacks

```javascript
kit.locker.createModal({
    onLock: onScrollLock,
    onRelease: onScrollRelease,
});
```
####Activate or deactivate

```javascript
kit.locker.lock();
kit.locker.unlock();
```

###Note
If window have **no scroll** (means that content's height less than window's height), then there is nothing to block, so plugin not will block anything and no callbacks will be fired.

Full guide could be found here:
http://localhost:8080/kit/modal/docs

### Licence
The code and the documentation are released under the MIT License.

