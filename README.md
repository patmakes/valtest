# valtest
### A combination of CSS and JS to test input validation at presentation layer

Try it here! https://patmakes.github.io/valtest/

- With the :invalid pseudoclass we can add an extra validation check at the presentation layer of a page.
- When anything other than a-z A-z 0-9 is typed, the formatting changes and the form input becomes invalid by having the js add the pseudoclass
- This isn't a lot on it's own, but it prevents links being submitted in the form
- the :invalid pseudo selector can then also be used by other scripts to further prevent bad form submissions, injection, and CSS
