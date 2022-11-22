![](https://i.pinimg.com/564x/dd/d8/aa/ddd8aa24d0dd845becc6811d0cfa3384.jpg)

Name and surname: Alexandr Shorokhov

Contact for communication: [Telegram](https://t.me/fmilone), Discord: 3OD1AK#9914

My goal: to learn how to develop working applications :)

Among the strengths: competent formulation of thoughts, good diction, moderate pace of speech. Perhaps the strength is also 6 kyu on [Codewars](https://www.codewars.com/users/3ODIAK )

Work experience: six months in a popular Russian online school as a technical support specialist, at the moment - a customer support specialist in one of the largest IT companies in Russia.

Skills:
- There is only one programming language so far: JavaScript — I know it at an average level;
- The framework is also the same: React — I know at an average level;
- From version control systems: Git — I know only the necessary basics.

Code Example:
- [Task with Codewars](https://www.codeweavers.com/kata/5264d2b162488dc400000001)

Solving task:
```js
function spinWords(string){
  let strLast = ''
  if ((/\s/).test(string) === false) {
    if (string.length > 5) {
      return string.split('').reverse().join('')
    } else {
      return string
    }
  } else {
    string = string.split(' ')
    for (let i in string) {
      if (string[i].length < 5) {
        strLast += string[i] + ' '
      } else {
        strLast += string[i].split('').reverse().join('') + ' '
      }
    }
    return strLast.trim()
  }
}
```

There is no commercial development experience.

Education:
Only not related to the development: a specialist in cooking and confectionery. 

English - A2
