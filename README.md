# Triangle-Obstacle-Challenger
You must find the shortest path starting from point A (home) to point B (workplace). A path is an ordered sequence of points connected one to another with a single and straight line. 


# The input file is made of several lines:

The first one contains 4 integers (Xs ; Ys;  Xf ; Yf) identifying the coordinates of the starting point (Xs ; Ys) and the finishing point (Xf ; Yf).
The second one contains the N number of obstacles. An obstacle is a triangle which vertexes are 3 couples of coordinates: (ax ; ay), (bx ; by), (cx ; cy). Obstacles may overlap.
Each of the following N lines indicates the vertexes of one obstacle.
Please note that a problem can be unsolvable, i.e. it is possible that there is no path to reach the destination. The perimeter of the obstacle is considered as part of the obstacle.

# Output format:

The output file is made of several lines:

The first one contains the number P of points your path is made of.
  Each of the following P lines contains the coordinates of a single point: two integers values separated with a space.
  If no path exists (or your algorithm can't find it) then the output must be one single line reporting exactly the word: IMPOSSIBLE. Please remember that the file encoding must be ASCII (or, in this case, UTF-8 as well).
  
# Constraints:
  0 <= N <= 105
  -106 <= x <= 106, -106 <= y <= 106 (for each coordinate)
  0 <= P <= 104

# Scoring
Rating is assigned as 1/(total path length) *1.000.000

# Exceptions:
If you output "IMPOSSIBLE" the score is always 0.
If your solution intersects one of the given obstacles, or you can’t reach the finishing point your score is always -100.
