---
layout: default
title:  Lanfeng Pan
---
<h1>Lanfeng Pan</h1>
<p>
  <span class="subtitle">PhD in Statistics</span>
</p>

I am currently PhD candidate in Statistics at Iowa State University under the direction of [Dr. Yehua Li](http://www.public.iastate.edu/~yehuali/). My research interests include High Performance Computing, False Discovery Rate Control, Clustering and Missing Data Analysis.

I completed my Master and Bachelor degree in Renmin University of China. My advisor of Master degree is Dr. Xiaolin Lyu. My research was about data mining and matrix factorization at that time.

The programming languages I use most are R and Julia. I have been using R for 8 years and Julia for 4 years. I use R for plotting and reporting as well as small projects. When need to do heavy computing, I will turn to Julia for higher performance.

[View CV in PDF](./about/LanfengPanCV.pdf).

<!-- <iframe src="http://lanfeng.me/about/LanfengPanCV.pdf" style="width:680px; height:1800px;" frameborder="0"></iframe>
-->

## Contact Me

* Email: [pan@iastate.edu](mailto:pan@iastate.edu)
* Homepage: [lanfeng.me](http://lanfeng.me/)

## Education

* Ph.D., Iowa State University, 2012 -- Now.
* Master, Renmin University of China, 2010 -- 2012.
* Bachelor, Renmin University of China, 2006 -- 2010.

## Papers

* __PAN, L.__, LI, Y., HE, K., LI, Y. and LI, Y. (2016). Latent Gaussian Mixture Models For Nationwide Kidney Transplant Center Evaluation. *The Annals of Applied Statistics* (submitted).

* LU, X., SI, J., __PAN, L.__ and ZHAO, Y. (2011). Imputation of missing data using ensemble algorithms. *Fuzzy Systems and Knowledge Discovery, 2011 Eighth International Conference on Shanghai*. pp. 1312-1315

## Awards
* First Place in the 15th Annual Data Mining Cup, May 2014.

<p style="padding-left:60px;">
Analyzing online shopping data, predicting product returning probability given customer shopping records and item information. Our team achieved the lowest prediction error rate among challengers all over the world.
</p>

## Work experience

* Research Assistant, 2014 -- Now.

<p style="padding-left:60px;">
Evaluating the performance of national wide kidney transplant centers.
Clustering transplant centers based on their performance and detecting under performing and out performing while control the false discovery rate.
</p>

* Intern at Novartis Pharmaceuticals, NJ, May 2015 -- August 2015.

<p style="padding-left:60px;">
Project 1: Building <code class="highlighter-rouge">shiny</code> apps to help other statisticians to visualize and analyze their data.

Project 2: Modeling and visualizing labor investment in hundreds of pharmaceutical projects, predicting future labor investments and detecting projects that may consume a lot of resources.
</p>

* Agriculture Experiment Station Consulting Group, May 2014 -- July 2014.

<p style="padding-left:60px;">
Helping researchers from other departments with their models and data analysis.
</p>

* Teaching Assistant, August 2012 -- May 2014.

<p style="padding-left:60px;">
Teaching assistant for various levels of Mathematical Statistics, from entry level to master level.
</p>

## Research Interests

* High Performance Computing
* Multiple Testing, False Discovery Rate Control
* Clustering, Subgroup Analysis
* Missing Data Analysis
* Nonparametrics
* Health Policy

## Skills

* 8 years experience with R
* 4 years experience with Julia
* 4 years experience with Linux Shell and git
* Some experience with Python
* Proficient with `shiny`, `ggplot2`, `knitr`, `rmarkdown` and $\TeX$

## Contributions
* Julia package [`KernelEstimator.jl`](http://github.com/panlanfeng/KernelEstimator.jl). Implement kernel density estimation and kernel regression. In particular this package can deal with bounded kernel estimation using beta and gamma kernel and can choose bandwidth via cross valuation.

* Julia package `LatentGaussianMixtureModel.jl`. Fit a Generalized Linear Mixed Model with Gaussian mixture random effects and decide the number of components for Gaussian mixture. And further conduct a multiple test to detect heterogeneity while controlling the False Discovery Rate.

* Julia package [`RFlavor.jl`](http://github.com/panlanfeng/RFlavor.jl). Implement a lot of useful and handy R functions in Julia. The purpose is to provide better statistical functions for Julia language as well as make it easy to translate R code into Julia.

* Julia package [`GaussianMixtureTest.jl`](http://github.com/panlanfeng/GaussianMixtureTest.jl). Implement the Kasahara-Shimotsu Test to decide number of components in Gaussian Mixture Model.

* Contribute to [`Yeppp.jl`](http://github.com/JuliaMath/Yeppp.jl). Port the [`Yeppp!`](http://www.yeppp.info/) library into Julia, significantly speeding up several basic arithmetic operations.

* Contribute to several core statistical packages in Julia community including  [`StatsBase.jl`](https://github.com/JuliaStats/StatsBase.jl), [`Rmath.jl`](https://github.com/JuliaStats/Rmath.jl), [`DataArrays.jl`](https://github.com/JuliaStats/DataArrays.jl) and [`KernelDensity.jl`](https://github.com/JuliaStats/KernelDensity.jl).

* R package [`bignmf`](http://github.com/panlanfeng/bignmf). Solve the nonnegative matrix factorization problem using coordinate descent.

<br/><br/>

<!--
<div id="disqus_thread"></div>
<script>
    /**
     *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
     *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables
     */

    var disqus_config = function () {
        this.page.url = "{{site.url}}";  // Replace PAGE_URL with your page's canonical URL variable
        this.page.identifier = "/"; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
    };

    (function() {  // DON'T EDIT BELOW THIS LINE
        var d = document, s = d.createElement('script');

        s.src = '//lanfeng.disqus.com/embed.js';

        s.setAttribute('data-timestamp', +new Date());
        (d.head || d.body).appendChild(s);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript" rel="nofollow">comments powered by Disqus.</a></noscript>

-->
