nonstrictunif-optimize
======================

Linearity optimizer for functional patterns and non-strict unification
----------------------------------------------------------------------

This package contains a tool which replaces occurrences of
`(fp =:<= x)` by `(fp =:<<= x)` if the functional pattern `fp`
always evaluates to a linear term.

