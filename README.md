# Aircraft-arrangement-results

The datasets are provided in "GA and GWO algorithm for the special bin packing problem encountered in field of aircraft arrangement" and "Heuristic algorithms for the special knapsack packing problem with defects arising in aircraft arrangement" by Luo, Q et al. To facilitate experimental reproducibility, the authors have collected these two datasets and made them available here.

Piece data are provided in Dataset\Pieces, where piece 1 to piece 5 are the pieces of dataset PS, piece l1 to piece l4 are the pieces of dataset L. Each line in the "piece" file stores the x and y coordinates of the vertices of the piece in counterclockwise order. Each line in the "support points" file stores the x and y coordinates of the support points of the piece. 

Sheet data are provided in Dataset\Sheets, where sheet 1 to sheet 4 are the sheets of dataset PS, sheet l is the sheet of dataset L. Each line in the "sheet" file stores the x and y coordinates of the vertices of the sheet in counterclockwise order. The defects of the sheets are stored in "sheet ihj" (which means the j-th hole of sheet i). 

---------------------------------------------

The packing results are provided in Results. The file name "pisjek" means that it is the result of packing piece i into sheet j with k even step angles. For example, p2s4e45 indicates that piece 2 is to be placed into sheet 4, and that 360 degrees is divided into 45 equal parts, i.e., the angular step size is 8 degrees. In each file, the first line contains the total number of packed pieces and the computation time (in seconds). Each of the subsequent lines records the x and y coordinates of a part and its rotation angle (measured counterclockwise).

