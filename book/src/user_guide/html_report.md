# HTML Report

Criterion.rs can generate an HTML report displaying the results of the benchmark under
`target/criterion/reports/index.html`. By default, the plots are generated using
[gnuplot](http://www.gnuplot.info/) if it is available, or the
[plotters](https://github.com/38/plotters) crate if it is not. The example below was generated
using the gnuplot backend, but the charts generated by plotters are similar.

To see an example report, [click here](html_report/report/index.html). For more details on the
charts and statistics displayed, check the other pages of this book.
