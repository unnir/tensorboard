# Tensor Widget

Tensor Widget is a DOM library for flexible, interactive, and efficient
display of values of tensors, i.e., typed n-dimensional arrays.

Features

- The header region displays the dtype, shape and optionally the name of
  the tensor.
- The **health pill** section of the header displays succinct summary of the
  tensor's element values, e.g., minimum, maxmimum, arithmetic mean,
  standard deviation, as well as distribution of the elements among value
  types such as zero, finite, infinite and NaN.
- In the main section of the basic UI, the widget displays element values as
  a 2D table. Tensors with dimensionality (rank) greater than 2 are sliced in
  ways that reduce them to 2D. The detailed slicing is configurable in the UI.
- The API allows for programmatic interaction with the UI, as well as listening
  to events in the UI.

*This component is in early stage of active development.*
*Many of its features are still incomplete.*
