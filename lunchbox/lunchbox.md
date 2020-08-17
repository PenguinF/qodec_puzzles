# Lunchbox sudoku

[![Lunchbox puzzle](https://github.com/PenguinF/qodec_puzzles/blob/master/lunchbox/lunchbox_penpa.png)](https://rjrudman.github.io/penpa-edit/?m=solve&p=tVTLihsxELzPZ+isgNSt5xzzOoU95MEShsHsIeQS4sQhhNjsv291j8wqY13DWK1yTatULbX96+fvh9MX6518uFjMeIIvOqgkGdPi8ALPOi3GG2sIw5t1upzfz5fzYV7WR3v+9Aw/zBfEu/liPBUzLyYZqMoS0F5ffsZLZrzL1jycTsc/h7vDS2NptYbzkA5pTEt2fKbvNzp60NhzT9NQJEl2R7fsLNmddsvOsmWnfaWl1FuRIr5vRerOYKO9c8N07+Sw+EbduzjWIdEZ5LPs2/HXfBadES/23S0fwjg/iM4of3cMVz+hDi/Kx51/1UHjvNX2IY0f0W72zBpfa3QSzY/jt79fj98hAOqdpr5Bv5EPlqQhCS1MaO+A+xUcyFKEP8GRgVGbYuRH1KM4djn4WUQ0geIM3DQjNCPqUVwtJdQgODlgnLtiD9z29Vgr9yGYwcvZqR/Zq9PJuHvBGd5K27dky25bi9my39ZitkzbWsyWQ1srnnPzk+GntBoLaqzNfy3Q2bxhhs5WL2botLUV3mo7hwrN2vxU1NLpUG3+KzxIT6tP/Mf0nl3by2Ev6W/FDCzecGn3enWvNAbEx2lamPUvantqhxMG7b7/+/w/5oV3CSFYnL58Cxg4gvUJ)

Inspired by the [Stacked Sandwiches Sudoku](https://logic-masters.de/Raetselportal/Raetsel/zeigen.php?id=0003SX).

## Rules

* Normal sudoku rules apply.
* Arrows of the same color (white or black) pointing at each other in the same column or row must contain the digits of the sum of the enclosed cells, in any order. For instance, the white arrows pointing at each other in row 2 enclose 3 cells. Examples of valid options for these cells are 1 3 4 5 2 because 3 + 4 + 5 = 12, but also 1 7 5 9 2 because 7 + 5 + 9 = 21. In both examples, the 1 and 2 must go into the cells containing the white arrows.
