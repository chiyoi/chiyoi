# Chiyoi
魔女です。[Nyan~](https://neko03.moe/chiyoi)
- Business - chiyoi2140@outlook.com
- Personal - chiyoi@neko03.moe
* Twitter (This name is far better than X) - [@chiyoi2140](https://twitter.com/chiyoi2140)
* Logs of algorithm solutions - [leetcode.com/chiyoi](https://leetcode.com/chiyoi)

---

## Go
[Go](https://go.dev/) is our favourite language. It is very simple, but very powerful.

For building web services, the standard library [`net/http`](https://pkg.go.dev/net/http) provides a `Server`-`Handler` architecture as a basic framework.
By defining our [`Handler`](https://pkg.go.dev/net/http#Handler)s, we can easily build a wide range of web services.
By configuring the [`Server`](https://pkg.go.dev/net/http#Server), we can control the behavior of the underlying network, like the listening address and the TLS configuration.

There are some features make this work even easier.
With [`context`](https://pkg.go.dev/context), we can pass data synchronously during a HTTP request, and control the lifecycle of our service.
With [`chan`]([https://pkg.go.dev/go/types#Chan](https://go.dev/ref/spec#Channel_types)), we can pass data asynchronously among handlers or other parts of our program.

Go lifted some commonly used utilities onto the language level, like containers [`map`](https://go.dev/ref/spec#Map_types) and [`slice`](https://go.dev/ref/spec#Slice_types).
The syntax is consistent for common operations, like get, set, iterate, and pre-allocate memory.
With these powerful containers, we can easily implement other common data structures, like hash set and queue.

---

## C
C looks retro. It is one of the very first programming languages, but is good until now.

We control the data on our own, and think like a computer.
When designing algorithms in C, we are clear about the detailed work the computer will do for each step.

---

## React
[React](https://react.dev/) is especially suitable for graphical application.

We use the syntax of TypeScript, which is a very flexible language.
It has a good support for functional-style programming, along with a smart typing system.

Features provided by React allow us to design applications declaratively.
We define our application as multiple `state`s, each with a pure `render` process.
Upon user interactions or other events, the `state` changes, and the display automatically re-`render`s.

---

## Rust
[Rust](https://www.rust-lang.org/) is a beautiful language.

Language features allow us to write elegent code.
Pure functions came from last-line return, valued control flow and pattern match.
Monads, data packed with operations, introduced by iterators.
We forget how computers work, but only think about what we want.

Rust is designed for memory security and high performance.
It neither relies on an internal memory manager, nor lets programmer to do its job, but the compiler controls everything well.

---

*Programming is an art.*
