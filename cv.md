# Pavel Kuvshinchikov
### Junior Frontend Developer

---

### Contact information:

**Phone:** +7999782****<br>
**E-mail:** ....@gmail.com<br>
**Telegram:** @...<br>

---

### Briefly About Myself:

Having started my career as a layout designer in a local newspaper with minimum skills, I became profficient in printing design.<br>
My keen interest in printing technologies led me to working as a Prepress and DTP Engineer in the largest printing house in my city,<br>
where I continued self-learning, examining the process of creating wine and food labels, magazines and other printed goods.<br>

Three years ago I’ve become passionate about retouching. I’ve mastered different retouching techniques,<br>
learned to work with graphic tablet, become an advanced Photoshop user and found my first job as a retoucher.<br>

Remote work as a retoucher gives me extra free time, which I spend learning Frontend Development.<br>
I’m interested in Web Development because this occupation provides endless possibilities for professional growth,<br>
besides there’s a huge amount of free high quality resources for self-education and a large community of developers.<br>

I believe, that my ability to learn and to gain new skills will lead me through this path of becoming a proficient Frontend Developer.<br>

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
