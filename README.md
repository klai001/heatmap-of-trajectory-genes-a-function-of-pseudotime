plot_pseudotime_heatmap() function has been deleted from monocle3.
As a result, this is a example script of how to create a heatmap of these trajectory genes along with pseudotime information from cds object created from monocle3 using Complex Heatmap package.  
Backbone of this script was modified from jonhsussman's helpful comment here: https://github.com/cole-trapnell-lab/monocle-release/issues/295 
which performs a smooth spline function row-wise across all the cells.
to include user-defined annotations, clustering based splitting and pseudotime barplot.

Author: Kei Onn, Lai 
