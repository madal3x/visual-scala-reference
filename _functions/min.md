---
title: min
layout: function
permalink: /min
---

# `min`

~~~ scala
trait Collection[A] {
  def min: A
}
~~~

`min` returns the smallest value in this collection.

<figure class="diagram">
  <img src="images/min.1.svg" alt="min function">
  <!-- <figcaption class="diagram-desc"></figcaption> -->
</figure>

On empty collections `min` throws a `UnsupportedOperationException` exception.

<figure class="diagram">
  <img src="images/min.2.svg" alt="min function">
  <!-- <figcaption class="diagram-desc"></figcaption> -->
</figure>