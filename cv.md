# Stasulevich Daniil

### Contacts

- email: alexgrist133@gmail.com
- telephone: +375293848860

### Summary

I'm Junior Web Developer. Usually work with Javascript,React and C#. 

### Skills

- Javascript
- TypeScript
- React.JS
- C#
- Unity3D
- Git
- Photoshop
- MicrosoftSQL
- C++

```JavaScript
function convert(input, source, target) {
  return fromBase10(toBase10(input, source), target);
}

function toBase10(input, encrypt){
  let base = encrypt.length;
  return input.split("").reduce((v,a) => v*base + encrypt.indexOf(a), 0);
}

function fromBase10(input, encrypt){
  if (input == 0) return encrypt[0];
  
  let base = encrypt.length;
  let res = [], value = input;
  while(value> 0){
    var r = value% base;
    res.push(encrypt[r]);
    value = (value-r)/base;
  }
  return res.reverse().join("");
}
```

### Experience

In 2020, completed a 3-month internship at an IT company "Ocsico".

### Education

Vocational education.

### English level

A2
