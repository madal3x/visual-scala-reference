---
name: reduceRightOption
---

# `reduceRightOption`

@include [signatures/reduceRightOption.md]

`reduceRightOption` applies the binary operator `op` to each element, going from right to left, and the previous `op` result.
The first time `op` is applied it's fed with the last two elements.
The final result is wrapped with `Some`.

<figure class="diagram">
  <img src="images/reduceRightOption.svg" alt="reduceRightOption function">
  <!-- <figcaption class="diagram-desc"></figcaption> -->
</figure>

On empty collections this function returns `None`.

<figure class="diagram">
  <img src="images/reduceRightOption.2.svg" alt="reduceRightOption function">
  <!-- <figcaption class="diagram-desc"></figcaption> -->
</figure>