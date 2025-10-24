Step-by-step logic:
- Start with an empty board.
- Try placing a queen in each column of the current row.
- Check if the placement is safe:
- No queen in the same column.
- No queen on the same major diagonal (row - col).
- No queen on the same minor diagonal (row + col).
- If safe, place the queen and move to the next row.
- If not safe, try the next column.
- Backtrack if no column in the current row is valid.
- Repeat until all rows are filled.


