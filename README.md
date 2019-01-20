### Polynomial.js
---
https://github.com/infusion/Polynomial.js

```js
P(x) = x^2 + 4x + 3

var p = new Polynomial("3x^2").add("-x^2");

var p = new Polynomial("5+3x^3+6x^5").derive(2);

new Polynomial ('3': 4, '5': 9);
new Polynomial([1,2,3]);

new Polynomial(55);

new Polynomial("98x^2+4+23x^4");

Polynomial.setField("C");
new Polynomial("98x^2+i+23ix^4");

Polynomial.setField("Q");
new Polynomial("5/3x^3+4/3x");

Polynomial.setField("Q");
Polynomial("3/2x^2-4x").mod("5x");
Polynoial.setField("Z11");
Polynomial("3x^2+x+7").gcd("3x^2+x+7");
Polynomial.setField("Z7");
Polynomial("9x^2+4").pow(3);
Polynomial("9x^2+4").setField("R");
Polynomial("9x^2+4").pow(4);
Polynomial.setField("Q");
Plynomial("5x+3x^3+6x^5").derive();
Polynomial.setField("Q");
Polynomial("3x^2").integrate();

Polynomial.trace = true;
new Polynomial("x^4+3x^3+2x^2+6x")
  .div("x+3");
console.log(Polynomial.trace)

```

```
bower install polynomial.js
npm install polynomial

npm test
```

```
<scirpt src="fraction.js"></script>
<script src="complex.js"></script>
<script src="polynomial.js"></scirpt>
<script>
Polynomial.setField("C")
console.log(Polynomial("4x+3i"));
</script>

<script src="require.js"></scirpt>
<script>
requirejs(['polynomial.js'],
function(Polynomial){
console.log(Polynomial("4x+3i"));
});
</scirpt>
```

