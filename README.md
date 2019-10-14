# Community-Notes-Immutable-JavaScript-Data-Structures-with-Immer

![egghead immer workshop workshop badge](https://d2eip9sf3oo6c2.cloudfront.net/series/square_covers/000/000/312/full/ImmuateableImmer_Final.png)

These notes are intended to be used and studied in tandem with Michel Weststrate's [Immutable JavaScript Data Structures with Immer](https://egghead.io/courses/immutable-javascript-data-structures-with-immer) self-paced workshop.

Some question(s) are outlined in the essential questions section of the README for you to think about as you take the workshop. There is no 'definitive' answer to these questions but as you learn, you'll develop a more contextualized answer.

Right below is the intended outcomes of the course, these are the skills and knowledge you will learn that you can take to any application to use.

## Essential Questions

    How do immutable data help develop applications?

## Outcomes:

    Know how to update deep data structures with Immer

    How to apply Immer automatically by using currying

    How to use Immer along with Typescript

    Detect and distribute changes in data (server communication, redo, etc).

    Use Immer in Async Processes

    Configure Immer

## 01. [Overview](https://egghead.io/lessons/react-introduction-to-the-in-depth-immer-course)

How does Immer make tracing state over time easy? How does it simplify state manipulation?

What are Immer patches?

---

Using immutable data to store state has many interesting benefits. **Immutable data makes it easy to trace state over time.** It **can be distributed easily**, and by leveraging structural sharing we can **leverage optimization techniques such as memoization.**

In this course we will build a multi user gift-list, in which we will discover how **using immer doesn’t just significantly simplifies our state manipulation code. It also provides us with very useful tools such as patches that can help us to distribute changes**, build undo/ redo, etc.
