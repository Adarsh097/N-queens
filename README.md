- The N-Queens problem is a well-known puzzle in the realm of combinatorial optimization and computer science. It involves placing N chess queens on an N×N chessboard so that no two queens threaten each other. A queen can attack any other piece in the same row, column, or diagonal.

- Problem Constraints:
Row Constraint: Each row must contain exactly one queen.
Column Constraint: Each column must contain exactly one queen.
Diagonal Constraint: No two queens can share the same diagonal.
Objective:
The primary goal is to arrange N queens on the board such that none of them can attack each other. This means finding a placement where no two queens share the same row, column, or diagonal.

- Key Challenges:
Combinatorial Explosion: The number of possible configurations increases dramatically with N, making exhaustive search methods impractical for large N.
Efficiency Requirements: Efficient algorithms are required to explore potential solutions without redundant computations.
Unique Solutions: For a given N, the problem often has multiple valid solutions (arrangements of queens).
Strategies to Solve:
Backtracking: A common approach involves recursively placing queens and backtracking when a conflict is detected, i.e., when a queen can attack another.

- Constraint Satisfaction: Using constraints (row, column, diagonal checks) to prune the search space, reducing unnecessary computations.

- Optimization Techniques: Various optimizations can be applied, such as early termination when a solution is found, symmetry breaking to reduce redundant searches, and heuristic methods to guide the search.


-  WEBSITE IS LIVE AT :    [n-queens](https://adarsh097.github.io/N-queens/)