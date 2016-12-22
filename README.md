# ShitScript

A script language designed specifically to prevent you from writing a good quality code and to promote an entire classes of bugs.

## Initial thoughts

#### Informal description

0. written in JavaScript
1. no statements, only expressions
2. no `var` (variables are always declared in a global scope by default)
3. no `return` – ShitScript returns the last evaluated expression
7. no floating point numbers (only integers)
8. no unary operators (?)
9. no classes, no `array`'s, no `object`'s (except for `console` and `window`)

#### Shitty ideas

* allow using `-`, `?`, `!` in function names (`no-camel-case`)
* super weird type coercions (or just some non-obvious implicit coercions result in string `'shit'`)
* `;` -> `)))`
* `===` -> `====`, `!==` -> `!===`
* `(...)` -> `[...]`
* `function` -> `shit` / `fuck`
* `try` -> `why-the-fuck-not`
* `catch` -> `fucked-up`
* `finally` -> `dont-fucking-care`
* say `please` to enable lexical scoping
* you can't use a couple of numbers (e.g. `4` and `2`) for no reason
* `x / 0` = `Math.random()`
* `if` -> `o-rly?`
* `then` -> `ya-rly`
* `else` -> `no-way`
* `o-rly?`-`ya-rly`-`no-way` for one-liners (without brackets)
* `.` -> `->` (works only for `console` and `window`)

An example program:

```javascript
fuck wat[] {
  calculate!!![2, 0])))
}

shit calculate!!![y, x] please {
  z = 5)))
  why-the-fuck-not {
    o-rly? z % 2 ==== 0 {
      y / x)))
    } no-way {
      x / y)))
    }
  } fucked-up[e] {
    console.lol[e])))
  } dont-fucking-care {
    0)))
  }
}
```

P.S.: *Not sure about using words `fuck` and `shit` everywhere (may be considered offensive)*

### License

[WTFPL](http://www.wtfpl.net/) – Do What the Fuck You Want to Public License.
