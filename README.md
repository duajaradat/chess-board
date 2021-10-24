# Chess Board

---

## Author : 

Du'a Jaradat

---


## Links and Resources

- [Pull Request](https://github.com/duajaradat/chess-board/pull/1)

---

## Overview

Constructing chess boards like it’s 1980.

---

## Feature Tasks and Requirements

- Render out chess boards with red and blue queens on them.
- Keeping it really basic here so the only pieces are queens and each queen is represented by a blue or red square.
- Chess board is an 8 by 8 grid of alternating black and white squares. The queens are red and blue squares.
- Each board will have one red and one blue queen at different coordinates. In addition to displaying the board you’ll need to identify if the queens are “under attack” based on their coordinates.

---

## User Acceptance Tests

- Queens on same row should be “under attack”
- Queens on same column should be “under attack”
- Queens on same diagonal should be “under attack”
- Queens with any other coordinates should NOT be “under attack”

**NOTE: Include assert statements directly in your notebook verifying the behavior above.**

---

## Stretch Goal

- Enlarge the chessboard to allow for pixel art drawn pieces. 16x16 ought to be enough.
- Add more attacking queens.
- Add opacity to cell colors.