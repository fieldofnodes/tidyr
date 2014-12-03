# tidyr 0.1.0.9000

* Experimental new `expand()` function (#21).

* `gather()` has better defaults if `key` and `value` are not supplied.

* If `...` is ommitted, `gather()` selects all columns (#28)

* Spread gains `drop` argument, which allows you to preserve missing
  factor levels (#25).

* Spread converts factor value variable to character, instead of embedding
  matrix inside data frame (#35).

* Preserve negative signs in `extract_numeric()` (#20).

* `separate()` gains `extra` argument which lets you control what happens
  to extra pieces. The default is to throw an "error", but you can also
  "merge" or "drop".

* `gather()` performance is now comparable to `reshape2::melt()` (#18).

* Added experiment unnest function for converting named lists into
  data frames. (#3, #22)