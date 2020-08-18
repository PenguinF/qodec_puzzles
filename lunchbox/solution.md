# Warning: contains spoilers.

Intentionally only mentioning the crucial and what I think are non-straightforward steps to solving this puzzle. Obfuscation by big-blob-of-text also intentional.

Notice that for sandwiches of size 8 there are only 5 possibilities for its total and the value of the single cell outside of the sandwich, the 'outlier' cell.
They are 27+9, 28+7, 29+5, 32+8 and 35+2. All of the options contain a 2.
The rightmost 2 columns contain an 8-cell sandwich, so the 2 in box 6 must go into its leftmost column, where a 4-cell column sandwich is located.
The 2 can only go to the crust cell. We can then place a couple of 1's.
There are 3 stacked 6-cell sandwiches in rows 4, 5 and 6, and they span exactly 2 boxes. Its digits sum to 90, which is an even number.
All of the 6 digits in a 6-cell sandwich with a 10-19-total always sum to an odd number.
All of the 6 digits in a 6-cell sandwich with a 20-29-total however always sum to an even number.
As the total is 90, we _must_ therefore have two 10-19-total sandwiches and one 20-29-total sandwich.
One of the 10-19-total sandwiches must be in row 4.
The two 1's of boxes 4 and 5 must therefore be in one of the six sandwich crust cells, and so the 1 in the inner column 4 sandwich (white arrows) gets resolved.
The total of the 6-cell sandwich in row 4 must be either 18 (3+4+5+6) or 19 (3+4+5+7).
The sum of the digits in the entire sandwich is 18+1+8 = 27 or 19+1+9 = 29, which leaves a remainder of 90-27 = 63 or 90-29 = 61 for the other two sandwiches.
Consider options for the remaining 10-19-total and 20-29-total. We cannot make a 29 total (repeated 9) or a 28 total (repeated 8).
The maximum sum of the 6 20-29-total sandwich digits is therefore 27+2+7 = 36.
Can the 10-19-total be 17 or lower? No, the maximum sum of that sandwich would be 17+1+7=25.
The 20-29-total sandwich must then be a 27 total, summing up to 36, and because 25+36 = 61 it also forces the row 4 sandwich to be a 19 total.
And then we have three 7 digits in boxes 4 and 5, the 7 in '27', the 7 in '17', and the 7 in 3+4+5+7 = 19.
Can we have two 18 totals? No, it would again force the 27 sandwich, and this time the digits summing up to 27 cannot use an 8 or a 7, and 4+5+6+9 is lower than 27.
Can we have two 19 totals? No, because it breaks the 12 sandwich in box 6. We'd have a 3+4+5+7 = 19 sandwich in row 4, and the two other sandwiches are 2+3+6+8 = 19 which rules out the 3+9 option for the 12 sandwich, and 4+6+7+8 = 25 which rules out both 4+8 and 5+7 for the 12 sandwich, and now it has no options left.
We must therefore have these three 6-cell sandwiches in rows 4, 5 and 6: 3+4+5+7 = 19, 2+3+6+7 = 18 and 4+5+8+9 = 26.
The 4-cell sandwich clue in column 4 now disambiguates the sandwiches. This sandwich now only works if the 26 sandwich is in row 5, and the 18 sandwich in row 6.
Options for this 4-cell sandwich are now 13 = 4+9, 13 = 5+8, or 16 = 7+9.
Now we can use the given 6 digit to do further disambiguation, place a bunch of 6'es, and do some tidying up.
In particular, this process lands a 6 in the middle of the 4-cell sandwich in row 9.
The crust cell of this sandwich which is not the 1 is also the 'outlier' cell of an 8-cell column sandwich, and so its options are limited to 2, 5, 7, 8 and 9.
We can rule out 7, 8 and 9 trivially, and we can rule out 2 (yields repeated 6), so that cell must be a 5.
The total of the sandwich in column 8 is now 29.
The options of the outlier cell in r9c4 are also limited to 2, 5, 7, 8 and 9.
9 and 5 are ruled out by existing digits. 2 and 8 are ruled out because they force a 35 or 32 total in a column already containing a 3. So this cell is a 7.
The cell in row 2, column 4 is now a naked single, so the total of the 5-cell sandwich in row 2 is 15.
So the total of this sandwich is 15, and this total can only be made with digits 3+4+8.
The sandwich in column 9 can now be resolved, then finally the 12 sandwich we started with.
The rest of the grid is done by regular sudoku.
