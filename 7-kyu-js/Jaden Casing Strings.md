# 📝 Jaden Casing Strings

## 🔗 [Task description on CodeWars](https://www.codewars.com/kata/5390bac347d09b7da40006f6)

### 💡 Solution

```javascript
String.prototype.toJadenCase = function () {
    return this.split(' ').map(w => w[0].toUpperCase() + w.slice(1)).join(' ');
};
```
