# Daily Simple Group

A daily puzzle about the Classification of Finite Simple Groups. You have six guesses to find the day's finite simple group. Each guess is compared with the answer by kind, family, order, and the primes in the order.

The site is the single file `index.html`. It has no build step and loads nothing from other sites. Progress and streaks are stored in the browser's local storage. Each day from October 27, 2026 has its own answer, taken from a fixed shuffle of 68 groups.

To run it locally, open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

The fonts embedded in the page, STIX Two Text and Source Sans 3, are under the [SIL Open Font License 1.1](https://openfontlicense.org). Their copyright notices are in a comment above the `@font-face` rules in `index.html`.
