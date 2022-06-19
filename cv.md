# Pavel Kuvshinchikov
### Junior Frontend Developer

---

### Contact information:

**Phone:** +7999782****<br>
**E-mail:** ....@gmail.com<br>
**Telegram:** @...<br>

---

### Briefly About Myself:

about me....<br>

---

### Skills and Proficiency:

- HTML5, CSS3
- JavaScript Basic  
- C++, C#, WinForms, WPF, EntityFramework, ASP.NET(MVC, RazerPage)
    
- Git, GitHub
- VS Code, VS Studio 2019/2022, MS Sql Server Management Studio


---

### Code example:

**Peak array index KATA from CODEWARS:**
*Given an array of ints, return the index such that the sum of the elements to the right of that index equals the sum of the elements to the left of that index. If there is no such index, return -1. If there is more than one such index, return the left-most index.*

```javascript
function peak(arr) {

  for (let i = 1; i < arr.length - 1; i++) {
    let leftSum = arr.slice(0, i).reduce((accumulator, currentValue) => accumulator + currentValue);
    let rightSum = arr.slice(i + 1).reduce((accumulator, currentValue) => accumulator + currentValue);
    if (leftSum === rightSum) {
      return i;
    }
  }
  return -1;
}
```
---

### Courses:

- IT Academy "Step"  
---

### Languages:

- English  
- Russian  
