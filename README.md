# Span Checker

A small website that helps you study linear algebra. Enter some vectors and it tells you:

- the **dimension of their span** (the rank)
- whether they are **linearly independent**
- whether they **fill the whole space** R^n
- whether another vector **lies in their span**

## Live demo

https://bilash-sarkar.github.io/linear-algebra-span-checker/


## How to use it

1. Type one vector per line, with numbers separated by commas. Example:
   ```
   1, 0, 2
   0, 1, 1
   1, 1, 3
   ```
2. Optionally type a vector to test, such as `2, 3, 7`.
3. Click **Check**.

All vectors must have the same number of entries.

## How it works

The vectors become the rows of a matrix. Gaussian elimination reduces the matrix, and the number of non-zero rows left is the rank. The rank equals the dimension of the span. A test vector is in the span if adding it to the matrix does not increase the rank.

## Run it on your computer

No installation needed. Download `index.html` and double-click it to open it in your browser.

## Built with

Plain HTML, CSS and JavaScript in a single file. No libraries.

## License

Free to use and modify. This project is licensed under the MIT License. See the LICENSE file for details.
