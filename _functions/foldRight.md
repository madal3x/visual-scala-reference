---
title: foldRight
layout: function
permalink: /foldRight
---

# `foldRight`

~~~ scala
trait Collection[A] {
  def foldRight[B](z: B)(op: (B, A) => B): B
}
~~~

`foldRight` applies the binary operator `op` to each element, going from right to left, and the previous `op` result. The first time `op` is applied it's fed with the initial value `z`.

<figure class="diagram">
  <img src="images/foldRight.1.svg" alt="foldRight function">
  <!-- <figcaption class="diagram-desc"></figcaption> -->
</figure>

On empty collections, `foldRight` doesn't apply `op` and the initial value `z` is directly returned.

<figure class="diagram">
  <img src="images/foldRight.2.svg" alt="foldRight function">
  <!-- <figcaption class="diagram-desc"></figcaption> -->
</figure>
