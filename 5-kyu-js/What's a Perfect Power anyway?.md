# 📝 What's a Perfect Power anyway?

## 🔗 [Task description on CodeWars](https://www.codewars.com/kata/54d4c8b08776e4ad92000835)

### 💡 Solution

```javascript
function isPP(n) {
    for (let m = 2; m * m <= n; m++) {
        for (let k = 2; Math.pow(m, k) <= n; k++) {
            if (Math.pow(m, k) === n) return [m, k];
        }
    }
    return null;
}
```
