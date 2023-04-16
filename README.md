# The Rust Book (Abridged)

v0.0.1 - Draft

By Jason Walton, based on ["The Rust Programming Language"](https://github.com/rust-lang/book/commit/c06006157b14b3d47b5c716fc392b77f3b2e21ce) by Steve Klabnik and Carol Nichols.

["The Rust Programming Language"](https://doc.rust-lang.org/stable/book/title-page.html) (AKA "the Rust Book") is a great resource for learning Rust, especially if you're new to programming. If you fall into this category, then I strongly suggest you put this book down and go read it instead.

But... the Rust Book is a bit wordy. It's an excellent introduction to Rust, but (fortunately or unfortunately, depending on your viewpoint) it's also an excellent introduction to many computer programming concepts, and if you're already familiar with one or more other programming languages, then you are no doubt familiar with these concepts already.

Take, for example, this excerpt from the section on functions:

> We define a function in Rust by entering `fn` followed by a function name and a set of parentheses. The curly brackets tell the compiler where the function body begins and ends. We can call any function we've defined by entering its name followed by a set of parentheses.

If you're a veteran programmer, this paragraph is probably something you didn't need to read. The [start of chapter 10](https://doc.rust-lang.org/stable/book/ch10-00-generics.html#removing-duplication-by-extracting-a-function) essentially explains [DRY principal](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself) at great length, which is something you probably already know. [Chapter 12](https://doc.rust-lang.org/stable/book/ch12-04-testing-the-librarys-functionality.html) spends quite a few paragraphs devoted to learning about test driven development, which is again something you are no doubt aware exists, and if you wanted to learn about TDD you'd probably be reading a book about TDD - what you want from this book is how `cargo` expects you to organize your tests and what syntax you need to define them.

This book is a rewrite of the Rust book, trying to make it less loquacious. The chapter names are all the same, and in many cases the subsections in each chapter are the same and examples have been copied directly from the original. This book tries to present information in the same order as the original Rust Book, but leaves out all the things an experienced developer would already know and focuses more on the parts that make Rust unique.  It also in many cases lets the code examples speak for themselves where the original book explained the code examples in great detail.

By using the same example code and keeping things in more or less the same order, the hope is that you can read this book, and if you come across something new or unclear, you can switch over to the original version of the Rust book and read the same section, with the exact same examples, and hopefully it will clear things up for you. (If this happens, please raise an issue to let me know where you got lost so I can improve this version!)

The original "The Rust Programming Language" is frequently abbreviated as "the Rust book".  We clearly need an even shorter abbreviation for this book, so we'll call this one "the rs book".

I wrote this while I was reading "The Rust Programming Language" and learning Rust, so if there are things you find in here that you think are wrong, it's entirely possible that this is because they _are_ wrong! Again, please feel free to raise an issue, or a PR and let me know!

Finally, right now this is a "draft" edition of this book, published as a collection of flat markdown files on GitHub, but at some point I will likely convert this into a pretty website similar to the original Rust Book, so if you want to bookmark something, I'd bookmark this page, as the individual `.md` files might get moved in the future.

## Table of Contents

- [Chapter 1: Getting Started][chap1]
- [Chapter 2: Guessing Game][chap2]
- [Chapter 3: Common Programming Concepts][chap3]
- [Chapter 4: Ownership, References, and Slices][chap4]
- [Chapter 5: Using Structs to Structure Related Data][chap5]
- [Chapter 6: Enums and Pattern Matching][chap6]
- [Chapter 7: Managing Growing Projects with Packages, Crates, and Modules][chap7]
- [Chapter 8: Common Collections][chap8]
- [Chapter 9: Error Handling][chap9]
- [Chapter 10: Generic Types, Traits, and Lifetimes][chap10]
- [Chapter 11: Writing Automated Tests][chap11]
- [Chapter 12: An I/O Project: Building a Command Line Program][chap12]
- [Chapter 13: Functional Language Features: Iterators and Closures][chap13]
- [Chapter 14: More About Cargo and Crates.io][chap14]
- [Chapter 17: Object Oriented Features of Rust][chap17]
- [Chapter 15: Smart Pointers][chap15]
- [Chapter 16: Fearless Concurrency][chap16]
- [Chapter 21: Bonus Chapter: Async Programming][chap21]

[chap1]: ./ch01-getting-started.md "Chapter 1: Getting Started"
[chap2]: ./ch02-guessing-game.md "Chapter 2: Guessing Game"
[chap3]: ./ch03-common-programming-concepts.md "Chapter 3: Common Programming Concepts"
[chap4]: ./ch04-ownership.md "Chapter 4: Ownership, References, and Slices"
[chap5]: ./ch05-structs.md "Chapter 5: Using Structs to Structure Related Data"
[chap6]: ./ch06-enums-and-pattern-matching.md "Chapter 6: Enums and Pattern Matching"
[chap7]: ./ch07-packages-crates-modules.md "Chapter 7: Managing Growing Projects with Packages, Crates, and Modules"
[chap8]: ./ch08-common-collections.md "Chapter 8: Common Collections"
[chap9]: ./ch09-error-handling.md "Chapter 9: Error Handling"
[chap10]: ./ch10-generic-types-traits-and-lifetimes.md "Chapter 10: Generic Types, Traits, and Lifetimes"
[chap11]: ./ch11-automated-tests.md "Chapter 11: Writing Automated Tests"
[chap12]: ./ch12-io-project-cli.md "Chapter 12: An I/O Project: Building a Command Line Program"
[chap13]: ./ch13-functional-language-features.md "Chapter 13: Functional Language Features: Iterators and Closures"
[chap14]: ./ch14-more-about-cargo.md "Chapter 14: More About Cargo and Crates.io"
[chap15]: ./ch15-smart-pointers.md "Chapter 15: Smart Pointers"
[chap16]: ./ch16-fearless-concurrency.md "Chapter 16: Fearless Concurrency"
[chap17]: ./ch17-object-oriented-features.md "Chapter 17: Object Oriented Features of Rust"
[chap21]: ./ch21-async.md "Chapter 21: Bonus Chapter: Async Programming"

TODO: Convert `foo()` to `foo`.
