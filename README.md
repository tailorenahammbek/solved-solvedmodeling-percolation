Download Link: https://assignmentchef.com/product/solved-solvedmodeling-percolation
<br>
* This program takes the name of a file as a command-line argument. * From that file, it * * – Reads the grid size N of the percolation system. * – Creates an N-by-N grid of sites (intially all blocked) * – Reads in a sequence of sites (row i, column j) to open. * * After each site is opened, it draws full sites in light blue, * open sites (that aren’t full) in white, and blocked sites in black, * with with site (0, 0) in the upper left-hand corner. * This program takes the grid size N as a command-line argument. * Then, the user repeatedly clicks sites to open with the mouse. * After each site is opened, it draws full sites in light blue, * open sites (that aren’t full) in white, and blocked sites in black. /** * Constructs a Percolation object that, given dimension N, creates an * NxN grid with all sites initially blocked. * * WeightedQuickUnionUF and QuickFindUF objects are created with N^2+2 sites. * 0 to N^2-1 represent the sites in the system while * N^2 represents the top virtual site and * N^2+1 represents the bottom virtual site. * * N^2 is connected to all the top row sites. * N^2+1 is connected to all the bottom row sites *