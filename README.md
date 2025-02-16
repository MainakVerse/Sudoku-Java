# Sudoku-Java
![image](https://github.com/user-attachments/assets/a4db0979-0404-4ea2-8f25-ea6f3b0646e2)

<table>
  <tr>
    <td>
      <h2>ABOUT</h2>
      <p>Sudoku is a logic-based puzzle that challenges players to fill a 9×9 grid with digits from 1 to 9. The grid is divided into nine 3×3 sub-grids, often referred to as boxes or regions. The objective is to ensure that each row, column, and sub-grid contains all the digits from 1 to 9 without any repetition. The game is widely recognized for its emphasis on deductive reasoning and logical thinking, making it a popular pastime around the world.</p>
    </td>
     </tr>
 <tr>
  <td>
   <h2>INVENTOR & HISTORY</h2>
   <p>The modern version of Sudoku was invented by American architect Howard Garns in 1979, originally published as "Numbers in Place" by Dell Magazines. The puzzle gained significant popularity in Japan after being published by Maki Kaji's puzzle company Nikoli in 1984, where it was renamed "Sudoku," meaning "Single Numbers." It became widely recognized outside Japan when Wayne Gould, a New Zealander, created a computer program to generate Sudoku puzzles and successfully introduced them to various newspapers, including The Times in London in 2004. This sparked a global Sudoku craze, particularly in the United States starting in 2005.</p>
  </td>
 </tr>
 <tr>
  <td>
   <h2>ALGORITHM</h2>
   <p>The algorithm for solving Sudoku typically involves backtracking, which is a form of depth-first search used in constraint satisfaction problems. The basic steps include: Find an empty cell: Locate an empty cell in the grid. Try possible numbers: For each number from 1 to 9, check if placing the number violates Sudoku rules (i.e., no duplicates in the corresponding row, column, or sub-grid). Place the number: If a number can be placed without conflict, place it and recursively attempt to fill the next empty cell. Backtrack if necessary: If placing a number leads to an unsolvable configuration, remove the number (backtrack) and try the next possibility. Repeat until solved: Continue this process until the grid is completely filled or all possibilities have been exhausted</p>
  </td>
 </tr>
</table>


