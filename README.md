# Hurwitz's Theorem in Lean 4

A formalization of **Hurwitz's approximation theorem**: for irrational ξ, there are
infinitely many rationals x/y with |ξ - x/y| < 1/(√5 y²).

The proof avoids continued fractions, using Farey brackets (pairs p/q < ξ < r/s with
qr - ps = 1) and mediant descent. It uses the property of at least one of p/q, r/s, and the
mediant (p+r)/(q+s) satisfying the bound. Compiles against Mathlib with no `sorry`s.
