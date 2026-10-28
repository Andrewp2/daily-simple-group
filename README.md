# Daily Simple Group

A daily puzzle about the Classification of Finite Simple Groups. You have six guesses to find the day's finite simple group, from a table of 98 groups. Each guess is compared with the answer by kind, family and order, and by whether the two orders agree on being divisible by 5 and by 7.

The site is the single file `index.html`. It has no build step and loads nothing from other sites. Progress and streaks are stored in the browser's local storage. Each day from October 27, 2026 has its own answer. The first two days are fixed, and later days come from a fixed shuffle of the 90 non-cyclic groups.

To run it locally, open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

The fonts embedded in the page, STIX Two Text and Source Sans 3, are under the [SIL Open Font License 1.1](https://openfontlicense.org). Their copyright notices are in a comment above the `@font-face` rules in `index.html`.
