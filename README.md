# Chiyoi
魔女です。
- E-mail: chiyoi@neko03.moe
- My page: https://neko03.moe/chiyoi
- Twitter: https://twitter.com/chiyoi2140
- Leetcode: https://leetcode.com/chiyoi

---

## Go
Go is the best language. It is very simple, but very powerful.

For building web services, the standard library `net/http` provides a `Server`-`Handler` architecture as a basic framework.
By defining our `Handler`s, we can easily build any type of web services.
We can also control the underlying network configurations like listening address and TLS configurations
by configuring the `Server`.

There are also some language features make this work even easier.
Using `context`, we can pass data synchronously during a HTTP request, and control the lifecycle of our service.
Using `chan`, we can pass data asynchronously among handlers or other parts of our program.

It also lifted some commonly used utilities onto the language level, like `map` and `slice`.
For common operations, like get or set items, iteration over elements, pre-allocate memory and free them,
we can use nearly the same syntax for both the containers.
We can also extend the containers for more specific tasks, like using `map[type]bool` as hash set and using slice as queue or stack.

All of these features makes Go a very simple and easy to use language.

---

## C
C is also a good language, it has a flavor of inferior beauty.

In C, we can control the memory on our own, and think like a computer.
When designing algorithms in C, we should clearify the detailed work for each step,
including the memory positions it modified and the resources it should request or release.

We can customize every part of our program to fit the specific task, and optimize our implementation
to get the highest efficiency. As a result, C is good for building infrastructures like codec libraries
or network protocol implementations.

---

## TypeScript with React
TypeScript with React is especially suitable for building graphical application.

TypeScript based on JavaScript, which is a very flexible language, and has a good support for
functional like programming. The typing system in TypeScript is also flexible and smart, so that
we can easily write codes while guaranteeing type safety.

Using `state` and `render` in React, we can design a graphical application in a declarative way.
We can define our application as multiple `state`s, each has a pure `render` process,
and move among them when getting user interactions or other events out of the application.

---

## Rust
Rust is a beautiful language.

In Rust, there are a large amount of elegent strategies,
for example last-line-return and functional iterators.
With them we can write very beautiful code.

At the same time, Rust is designed for memory security and high performance.
Unlike C, the Rust compiler did most things for us.

---

*Programming is an art.*
