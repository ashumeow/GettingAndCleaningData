Using <code>RStudio</code>,
```R
> source("http://bioconductor.org/biocLite.R")
trying URL 'http://www.bioconductor.org/packages/3.0/bioc/bin/windows/contrib/3.1/BiocInstaller_1.16.4.zip'
Content type 'application/zip' length 54044 bytes (52 KB)
opened URL
downloaded 52 KB


The downloaded binary packages are in
	C:\Users\dell\AppData\Local\Temp\RtmpyAwlrX\downloaded_packages
Bioconductor version 3.0 (BiocInstaller 1.16.4),
  ?biocLite for help
A new version of Bioconductor is available after
  installing the most recent version of R; see
  http://bioconductor.org/install
  
  
> biocLite("rhdf5")
BioC_mirror: http://bioconductor.org
Using Bioconductor version 3.0 (BiocInstaller
  1.16.4), R version 3.1.3.
Installing package(s) 'rhdf5'
also installing the dependency ‘zlibbioc’

trying URL 'http://bioconductor.org/packages/3.0/bioc/bin/windows/contrib/3.1/zlibbioc_1.12.0.zip'
Content type 'application/zip' length 494105 bytes (482 KB)
opened URL
downloaded 482 KB

trying URL 'http://bioconductor.org/packages/3.0/bioc/bin/windows/contrib/3.1/rhdf5_2.10.0.zip'
Content type 'application/zip' length 5447420 bytes (5.2 MB)
opened URL
downloaded 5.2 MB

package ‘zlibbioc’ successfully unpacked and MD5 sums checked
package ‘rhdf5’ successfully unpacked and MD5 sums checked

The downloaded binary packages are in
	C:\Users\dell\AppData\Local\Temp\RtmpyAwlrX\downloaded_packages
Old packages: 'codetools', 'jsonlite', 'knitr',
  'lattice', 'manipulate', 'markdown', 'MASS',
  'Matrix', 'mgcv', 'plyr', 'Rcpp', 'RCurl',
  'stringr'
Update all/some/none? [a/s/n]: 
a
also installing the dependency ‘stringi’

trying URL 'http://cran.rstudio.com/bin/windows/contrib/3.1/stringi_0.4-1.zip'
Content type 'application/zip' length 13437893 bytes (12.8 MB)
opened URL
downloaded 12.8 MB

trying URL 'http://cran.rstudio.com/bin/windows/contrib/3.1/codetools_0.2-11.zip'
Content type 'application/zip' length 46174 bytes (45 KB)
opened URL
downloaded 45 KB

trying URL 'http://cran.rstudio.com/bin/windows/contrib/3.1/jsonlite_0.9.16.zip'
Content type 'application/zip' length 1009806 bytes (986 KB)
opened URL
downloaded 986 KB

trying URL 'http://cran.rstudio.com/bin/windows/contrib/3.1/knitr_1.10.5.zip'
Content type 'application/zip' length 657331 bytes (641 KB)
opened URL
downloaded 641 KB

trying URL 'http://cran.rstudio.com/bin/windows/contrib/3.1/lattice_0.20-31.zip'
Content type 'application/zip' length 729911 bytes (712 KB)
opened URL
downloaded 712 KB

trying URL 'http://cran.rstudio.com/bin/windows/contrib/3.1/manipulate_1.0.1.zip'
Content type 'application/zip' length 35784 bytes (34 KB)
opened URL
downloaded 34 KB

trying URL 'http://cran.rstudio.com/bin/windows/contrib/3.1/markdown_0.7.7.zip'
Content type 'application/zip' length 165467 bytes (161 KB)
opened URL
downloaded 161 KB

trying URL 'http://cran.rstudio.com/bin/windows/contrib/3.1/MASS_7.3-40.zip'
Content type 'application/zip' length 1085549 bytes (1.0 MB)
opened URL
downloaded 1.0 MB

trying URL 'http://cran.rstudio.com/bin/windows/contrib/3.1/Matrix_1.2-0.zip'
Content type 'application/zip' length 3603550 bytes (3.4 MB)
opened URL
downloaded 3.4 MB

trying URL 'http://cran.rstudio.com/bin/windows/contrib/3.1/mgcv_1.8-6.zip'
Content type 'application/zip' length 2039622 bytes (1.9 MB)
opened URL
downloaded 1.9 MB

trying URL 'http://cran.rstudio.com/bin/windows/contrib/3.1/plyr_1.8.2.zip'
Content type 'application/zip' length 1130019 bytes (1.1 MB)
opened URL
downloaded 1.1 MB

trying URL 'http://cran.rstudio.com/bin/windows/contrib/3.1/Rcpp_0.11.6.zip'
Content type 'application/zip' length 3192747 bytes (3.0 MB)
opened URL
downloaded 3.0 MB

trying URL 'http://cran.rstudio.com/bin/windows/contrib/3.1/RCurl_1.95-4.6.zip'
Content type 'application/zip' length 2703627 bytes (2.6 MB)
opened URL
downloaded 2.6 MB

trying URL 'http://cran.rstudio.com/bin/windows/contrib/3.1/stringr_1.0.0.zip'
Content type 'application/zip' length 82977 bytes (81 KB)
opened URL
downloaded 81 KB

package ‘stringi’ successfully unpacked and MD5 sums checked
package ‘codetools’ successfully unpacked and MD5 sums checked
package ‘jsonlite’ successfully unpacked and MD5 sums checked
package ‘knitr’ successfully unpacked and MD5 sums checked
package ‘lattice’ successfully unpacked and MD5 sums checked
package ‘manipulate’ successfully unpacked and MD5 sums checked
package ‘markdown’ successfully unpacked and MD5 sums checked
package ‘MASS’ successfully unpacked and MD5 sums checked
package ‘Matrix’ successfully unpacked and MD5 sums checked
package ‘mgcv’ successfully unpacked and MD5 sums checked
package ‘plyr’ successfully unpacked and MD5 sums checked
package ‘Rcpp’ successfully unpacked and MD5 sums checked
package ‘RCurl’ successfully unpacked and MD5 sums checked
package ‘stringr’ successfully unpacked and MD5 sums checked

The downloaded binary packages are in
	C:\Users\dell\AppData\Local\Temp\RtmpyAwlrX\downloaded_packages
	
	
> ## checking whether the package is working or not
> library(rhdf5)
```
That's it... Good to go now!
