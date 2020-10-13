# How to Properly Plot Uncertainty Ellipses for 2D Nomally Distributed Data

This notebook demonstrates how to properly plot error ellipses that represent desired levels of uncertainty as given by the covariance matrix of normally distributed data in 2D.  The reason for this note is that I have seen others naively extend 1D covariance bounds to 2D, which is not technically correct. 

## Main Files

* [plotting-uncertainty-ellipses.ipynb](plotting-uncertainty-ellipses.ipynb) (Jupyter notebook)

## References

You can find a similar but partial treatment of this problem on the Matplotlib page called ["Plot a confidence ellipse of a two-dimensional dataset"](https://matplotlib.org/devdocs/gallery/statistics/confidence_ellipse.html). Vincent Spruyt also has a really nice and complete description on his page called ["How to draw a covariance error ellipse?"](https://www.visiondummy.com/2014/04/draw-error-ellipse-representing-covariance-matrix/). We also employ the book Johnson and Wichern (2007) [Applied Multivariate Statistical Anlaysis](https://ocul-qu.primo.exlibrisgroup.com/permalink/01OCUL_QU/11tsvcl/alma9925738833405158) (6th ed.), Chapter 4, Result 4.7 on page 163.

## License

This work is licensed under an [MIT License](LICENSE.txt).
