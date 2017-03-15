# Taskviews genesis

The usage of the **taskviews** R package  with live examples on GitHub pages

## CRAN Task Views statistics 

Total [CRAN packages](https://cran.r-project.org/web/packages): **10036**

Total [CRAN Task Views](https://cran.r-project.org/web/views): **34**

**The distribution of CRAN task views combinations:**

|Number of task views   |    0|    1|   2|  3|  4|  5|  7|  6|  8|  9| 10|
|:--|----:|----:|---:|--:|--:|--:|--:|--:|--:|--:|--:|
|Number of packages | 7390| 2177| 340| 84| 30|  7|  4|  1|  1|  1|  1|

- **Zero means:** no task view assignment.
- **One:** exactly one task view assignment.
- **More than one:** packages having more than one task view assignment.

**The distribution of all CRAN task views related packages:**
<p align="center"><img src="img/tviews_freq_v1.png" width="90%" alt="The distribution of all CRAN task views related packages"></p>

**The distribution of all CRAN task views versus unique CRAN task views:**
- **Red:** all task views.
- **Blue:** unique task views.
<p align="center"><img src="img/tviews_freq_all_vs_unique.png" width="92%" alt="all CRAN task views vs. unique CRAN task views"></p>



## Examples of D3 forceNetwork for CRAN Task Views

**D3 forceNetwork graph visualizing connections between task views:**
- [D3 forceNetwork](http://bemined.github.io/TaskviewsGenesis/FN/FN_tviews.html) for all task views

**D3 forceNetwork graph visualizing connections between task views and related packages:**

For task views:
- [WebTechnologies](https://cran.r-project.org/web/views/WebTechnologies.html), [Spatial](https://cran.r-project.org/web/views/Spatial.html), [ReproducibleResearch](https://cran.r-project.org/web/views/ReproducibleResearch.html), [gR](https://cran.r-project.org/web/views/gR.html), [Bayesian](https://cran.r-project.org/web/views/Bayesian.html):
  - [D3 forceNetwork](http://bemined.github.io/TaskviewsGenesis/FN/FN_some_tviews_1_labels_no.html)
  - [D3 forceNetwork](http://bemined.github.io/TaskviewsGenesis/FN/FN_some_tviews_1_labels_views.html) - with task view names being displayed
  - [D3 forceNetwork](http://bemined.github.io/TaskviewsGenesis/FN/FN_some_tviews_1_labels_all.html) - with task view and package names being displayed
  - [D3 forceNetwork](http://bemined.github.io/TaskviewsGenesis/FN/FN_some_tviews_1_labels_all_clickable.html) - with task view and package names being displayed. A click on a node takes the user to the webpage with the corresponding task view/package
- [NaturalLanguageProcessing](https://cran.r-project.org/web/views/NaturalLanguageProcessing.html), [WebTechnologies](https://cran.r-project.org/web/views/WebTechnologies.html), [HighPerformanceComputing](https://cran.r-project.org/web/views/HighPerformanceComputing.html):
  - [D3 forceNetwork](http://bemined.github.io/TaskviewsGenesis/FN/FN_some_tviews_2_labels_no.html)
  - [D3 forceNetwork](http://bemined.github.io/TaskviewsGenesis/FN/FN_some_tviews_2_labels_views.html) - with task view names being displayed
  - [D3 forceNetwork](http://bemined.github.io/TaskviewsGenesis/FN/FN_some_tviews_2_labels_all.html) - with task view and package names being displayed
- all currently available task views:
  - [D3 forceNetwork](http://bemined.github.io/TaskviewsGenesis/FN/FN_all_tviews_labels_no.html)
  - [D3 forceNetwork](http://bemined.github.io/TaskviewsGenesis/FN/FN_all_tviews_labels_views.html) - with task view names being displayed
  - [D3 forceNetwork](http://bemined.github.io/TaskviewsGenesis/FN/FN_all_tviews_labels_all.html) - with task view and package names being displayed
  
For packages:
- "abbyyR", "alm", "anametrix", "bigrquery", "downloader", "RgoogleMaps", "plotGoogleMaps", "akima", "cleangeo", "rgdal", "spaMM", "vec2dtransf", "plotKML", "leafletR", "recmap"
  - [D3 forceNetwork](http://bemined.github.io/TaskviewsGenesis/FN/FN_some_packages_1_labels_no.html)
  - [D3 forceNetwork](http://bemined.github.io/TaskviewsGenesis/FN/FN_some_packages_1_labels_views.html) - with task view names being displayed
  - [D3 forceNetwork](http://bemined.github.io/TaskviewsGenesis/FN/FN_some_packages_1_labels_all.html) - with task view and package names being displayed
- all packages related to the [High-Performance and Parallel Computing with R](https://cran.r-project.org/web/views/HighPerformanceComputing.html) task view
  - [D3 forceNetwork](http://bemined.github.io/TaskviewsGenesis/FN/FN_some_packages_2_labels_no.html)
  - [D3 forceNetwork](http://bemined.github.io/TaskviewsGenesis/FN/FN_some_packages_2_labels_views.html) - with task view names being displayed
  - [D3 forceNetwork](http://bemined.github.io/TaskviewsGenesis/FN/FN_some_packages_2_labels_all.html) - with task view and package names being displayed

## Examples of Three.js graph for CRAN Task Views

**Three.js graph visualizing connections between task views and related packages:**
- for task views:
    - [Three.js graph](http://bemined.github.io/TaskviewsGenesis/GraphJS/graphjs_tviews.html) for all task views
    - [Three.js graph](http://bemined.github.io/TaskviewsGenesis/GraphJS/graphjs_tviews_with_labels.html) for all task views, labels for task views are displayed
    - [Three.js graph](http://bemined.github.io/TaskviewsGenesis/GraphJS/graphjs_tviews_with_num_and_labels.html) for all task views, labels for task views with number of assigned packages are displayed
    - [Three.js graph](http://bemined.github.io/TaskviewsGenesis/GraphJS/graphjs_tviews_with_all_labels_01.html) for task views: [WebTechnologies](https://cran.r-project.org/web/views/WebTechnologies.html), [Spatial](https://cran.r-project.org/web/views/Spatial.html), [ReproducibleResearch](https://cran.r-project.org/web/views/ReproducibleResearch.html), [gR](https://cran.r-project.org/web/views/gR.html), [Bayesian](https://cran.r-project.org/web/views/Bayesian.html), labels for all task views (with number of assigned packages) and packages are displayed
- for packages:
    - [Three.js graph](http://bemined.github.io/TaskviewsGenesis/GraphJS/graphjs_tviews_with_given_package_labels.html) for all task views related to packages: "no_tview", "abbyyR", "alm", "anametrix", "bigrquery", "downloader", "RgoogleMaps", "plotGoogleMaps", "akima", "cleangeo", "rgdal", "spaMM", "vec2dtransf", "plotKML", "leafletR", "recmap"
