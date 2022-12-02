<div align="center"><img src="./assets/head.jpg"></div>

# AWESOME DATA SCIENCE

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) 

**An open source Data Science repository to learn and apply towards solving real world problems.**

This is a shortcut path to start studying **Data Science**. Just follow the steps to answer the questions, "What is Data Science and what should I study to learn Data Science?"

## Sponsors

| Sponsor | Pitch |
| --- | --- |
| --- | Be the first to sponsor! `github@academic.io` |



<br>

## Table of Contents

- [What is Data Science?](#what-is-data-science)
- [Where do I Start?](#where-do-i-start)
- [Training Resources](#training-resources)
  - [Tutorials](#tutorials)
  - [Free Courses](#free-courses)
  - [Massively Open Online Courses](#moocs)
  - [Intensive Programs](#intensive-programs)
  - [Colleges](#colleges)
- [The Data Science Toolbox](#the-data-science-toolbox)
  - [Algorithms](#algorithms)
    - [Supervised Learning](#supervised-learning)
    - [Unsupervised Learning](#unsupervised-learning)
    - [Semi-Supervised Learning](#semi-supervised-learning)
    - [Reinforcement Learning](#reinforcement-learning)
    - [Data  Mining Algorithms](#data-mining-algorithms)
    - [Deep Learning Architectures](#deep-learning-architectures)
  - [General Machine Learning Packages](#general-machine-learning-packages)
  - [Deep Learning Packages](#deep-learning-packages)
    - [PyTorch Ecosystem](#pytorch-ecosystem)
    - [TensorFlow Ecosystem](#tensorflow-ecosystem)
    - [Keras Ecosystem](#keras-ecosystem)
  - [Visualization Tools](#visualization-tools)
  - [Miscellaneous Tools](#miscellaneous-tools)
- [Literature and Media](#literature-and-media)
  - [Books](#books)
    - [Book Deals (Affiliated)](#book-deals-affiliated-)
  - [Journals, Publications, and Magazines](#journals-publications-and-magazines)
  - [Newsletters](#newsletters)
  - [Bloggers](#bloggers)
  - [Presentations](#presentations)
  - [Podcasts](#podcasts)]
  - [YouTube Videos & Channels](#youtube-videos--channels)
- [Socialize](#socialize)
  - [Facebook Accounts](#facebook-accounts)
  - [Twitter Accounts](#twitter-accounts)
  - [Telegram Channels](#telegram-channels)
  - [Slack Communities](#slack-communities)
  - [GitHub Groups](#github-groups)
  - [Data Science Competitions](#data-science-competitions)
- [Fun](#fun)
  - [Infographics](#infographics)
  - [Datasets](#datasets)
  - [Comics](#comics)
- [Other Awesome Lists](#other-awesome-lists)
  - [Hobby](#hobby)

## What is Data Science?
**[`^        back to top        ^`](#awesome-data-science)**

Data Science is one of the hottest topics on the Computer and Internet farmland nowadays. People have gathered data from applications and systems until today and now is the time to analyze them. The next steps are producing suggestions from the data and creating predictions about the future. [Here](https://www.quora.com/Data-Science/What-is-data-science) you can find the biggest question for **Data Science** and hundreds of answers from experts.


| Link | Preview |
| --- | --- |
| [What is Data Science @ O'reilly](https://www.oreilly.com/ideas/what-is-data-science) | _Data scientists combine entrepreneurship with patience, the willingness to build data products incrementally, the ability to explore, and the ability to iterate over a solution. They are inherently interdisciplinary. They can tackle all aspects of a problem, from initial data collection and data conditioning to drawing conclusions. They can think outside the box to come up with new ways to view the problem, or to work with very broadly defined problems: “here’s a lot of data, what can you make from it?”_ |
| [What is Data Science @ Quora](https://www.quora.com/Data-Science/What-is-data-science) | Data Science is a combination of a number of aspects of Data such as Technology, Algorithm development, and data interference to study the data, analyse it, and find innovative solutions to difficult problems. Basically Data Science is all about Analysing data and driving for business growth by finding creative ways. |
| [The sexiest job of 21st century](https://hbr.org/2012/10/data-scientist-the-sexiest-job-of-the-21st-century) | _Data scientists today are akin to Wall Street “quants” of the 1980s and 1990s. In those days people with backgrounds in physics and math streamed to investment banks and hedge funds, where they could devise entirely new algorithms and data strategies. Then a variety of universities developed master’s programs in financial engineering, which churned out a second generation of talent that was more accessible to mainstream firms. The pattern was repeated later in the 1990s with search engineers, whose rarefied skills soon came to be taught in computer science programs._ |
| [Wikipedia](https://en.wikipedia.org/wiki/Data_science) | _Data science is an inter-disciplinary field that uses scientific methods, processes, algorithms and systems to extract knowledge and insights from many structural and unstructured data. Data science is related to data mining, machine learning and big data._ |
| [How to Become a Data Scientist](https://www.mastersindatascience.org/careers/data-scientist/) | _Data scientists are big data wranglers, gathering and analyzing large sets of structured and unstructured data. A data scientist’s role combines computer science, statistics, and mathematics. They analyze, process, and model data then interpret the results to create actionable plans for companies and other organizations._ |
| [a very short history of #datascience](https://www.forbes.com/sites/gilpress/2013/05/28/a-very-short-history-of-data-science/) | _The story of how data scientists became sexy is mostly the story of the coupling of the mature discipline of statistics with a very young one--computer science.  The term “Data Science” has emerged only recently to specifically designate a new profession that is expected to make sense of the vast stores of big data. But making sense of data has a long history and has been discussed by scientists, statisticians, librarians, computer scientists and others for years. The following timeline traces the evolution of the term “Data Science” and its use, attempts to define it, and related terms._ |
|[Software Development Resources for Data Scientists](https://www.rstudio.com/blog/software-development-resources-for-data-scientists/)|Data scientists concentrate on making sense of data through exploratory analysis, statistics, and models. Software developers apply a separate set of knowledge with different tools. Although their focus may seem unrelated, data science teams can benefit from adopting software development best practices. Version control, automated testing, and other dev skills help create reproducible, production-ready code and tools.|

## Where do I Start?
**[`^        back to top        ^`](#awesome-data-science)**

While not strictly necessary, having a programming language is a crucial skill to be effective as a data scientist. Currently, the most popular language is _Python_, closely followed by _R_. Python is a general-purpose scripting language which sees applications in a wide variety of fields. R is a domain-specific language for statistics, which contains a lot of common statistics tools out of the box.

Python is by far the most popular language in science, due in no small part to the ease at which it can be used and the vibrant ecosystem of user-generated packages. To install packages, there are two main methods: Pip (invoked as `pip install`), the package manager that comes bundled with Python, and [Anaconda](https://www.anaconda.com) (invoked as `conda install`), a powerful package manager that can install packages for Python, R, and can download executables like Git. 

Unlike R, Python was not built from the ground up with data science in mind, but there are plenty of third party libraries to make up for this. A much more exhaustive list of packages can be found later in this document, but these four packages are a good set of choices to start your data science journey with: [Scikit-Learn](https://scikit-learn.org/stable/index.html) is a general-purpose data science package which implements the most popular algorithms - it also includes rich documentation, tutorials, and examples of the models it implements. Even if you prefer to write your own implementations, Scikit-Learn is a valuable reference to the nuts-and-bolts behind many of the common algorithms you'll find. With [Pandas](https://pandas.pydata.org/), one can collect and analyze their data into a convenient table format. [Numpy](https://numpy.org/) provides very fast tooling for mathematical operations, with a focus on vectors and matrices. [Seaborn](https://seaborn.pydata.org/), itself based on the [Matplotlib](https://matplotlib.org/) package, is a quick way to generate beautiful visualizations of your data, with many good defaults available out of the box, as well as a gallery showing how to produce many common visualizations of your data.

 When embarking on your journey to becoming a data scientist, the choice of language isn't particularly important, and both Python and R have their pros and cons. Pick a language you like, and check out one of the [Free courses](#free-courses) we've listed below!

## Training Resources
**[`^        back to top        ^`](#awesome-data-science)**

How do you learn data science? By doing data science, of course! Okay, okay - that might not be particularly helpful when you're first starting out. In this section, we've listed some learning resources, in a rough order from least to greatest commitment - [Tutorials](#tutorials), [Massively Open Online Courses (MOOCs)](#moocs), [Intensive Programs](#intensive-programs), and [Colleges](#colleges).


### Tutorials
**[`^        back to top        ^`](#awesome-data-science)**

- [1000 Data Science Projects](https://cloud.blobcity.com/#/ps/explore) you can run on the browser with IPython.
- [#tidytuesday](https://github.com/rfordatascience/tidytuesday) A weekly data project aimed at the R ecosystem.
- [Data science your way](https://github.com/jadianes/data-science-your-way)
- [PySpark Cheatsheet](https://github.com/kevinschaich/pyspark-cheatsheet)
- [Machine Learning, Data Science and Deep Learning with Python ](https://www.manning.com/livevideo/machine-learning-data-science-and-deep-learning-with-python)
- [How To Label Data](https://www.lighttag.io/how-to-label-data/)
- [Your Guide to Latent Dirichlet Allocation](https://medium.com/@lettier/how-does-lda-work-ill-explain-using-emoji-108abf40fa7d)
- [Over 1000 Data Science Online Courses at Classpert Online Search Engine](https://classpert.com/search/data-science)
- [Tutorials of source code from the book Genetic Algorithms with Python by Clinton Sheppard](https://github.com/handcraftsman/GeneticAlgorithmsWithPython)
- [Tutorials to get started on signal processings for machine learning](https://github.com/jinglescode/python-signal-processing)
- [Realtime deployment](https://www.microprediction.com/python-1) Tutorial on Python time-series model deployment.
- [Python for Data Science: A Beginner’s Guide](https://learntocodewith.me/posts/python-for-data-science/)
- [Minimum Viable Study Plan for Machine Learning Interviews](https://github.com/khangich/machine-learning-interview)
- [Understand and Know Machine Learning Engineering by Building Solid Projects](http://mlzoomcamp.com/)


### Free Courses
**[`^        back to top        ^`](#awesome-data-science)**

- [Data Scientist with R](https://www.datacamp.com/tracks/data-scientist-with-r)
- [Data Scientist with Python](https://www.datacamp.com/tracks/data-scientist-with-python)
- [Genetic Algorithms OCW Course](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-034-artificial-intelligence-fall-2010/lecture-videos/lecture-1-introduction-and-scope/)
- [AI Expert Roadmap](https://github.com/AMAI-GmbH/AI-Expert-Roadmap) - Roadmap to becoming an Artificial Intelligence Expert
- [Convex Optimization](https://www.edx.org/course/convex-optimization) - Convex Optimization (basics of convex analysis; least-squares, linear and quadratic programs, semidefinite programming, minimax, extremal volume, and other problems; optimality conditions, duality theory...)
- [Skillcombo - Data Science](https://skillcombo.com/courses/development/data-science/free/) - 1000+ free online Data Science courses
- [Learning from Data](https://home.work.caltech.edu/telecourse.html) - Introduction to machine learning covering basic theory, algorithms and applications
- [Kaggle](https://www.kaggle.com/learn) - Learn about Data Science, Machine Learning, Python etc


### MOOC's
**[`^        back to top        ^`](#awesome-data-science)**

- [Coursera Introduction to Data Science](https://www.coursera.org/specializations/data-science)
- [Data Science - 9 Steps Courses, A Specialization on Coursera](https://www.coursera.org/specializations/jhu-data-science)
- [Data Mining - 5 Steps Courses, A Specialization on Coursera](https://www.coursera.org/specializations/data-mining)
- [Machine Learning – 5 Steps Courses, A Specialization on Coursera](https://www.coursera.org/specializations/machine-learning)
- [CS 109 Data Science](https://cs109.github.io/2015/)
- [OpenIntro](https://www.openintro.org/)
- [CS 171 Visualization](https://www.cs171.org/#!index.md)
- [Process Mining: Data science in Action](https://www.coursera.org/learn/process-mining)
- [Oxford Deep Learning](https://www.cs.ox.ac.uk/projects/DeepLearn/)
- [Oxford Deep Learning - video](https://www.youtube.com/playlist?list=PLE6Wd9FR--EfW8dtjAuPoTuPcqmOV53Fu)
- [Oxford Machine Learning](https://www.cs.ox.ac.uk/research/ai_ml/index.html)
- [UBC Machine Learning - video](https://www.cs.ubc.ca/~nando/540-2013/lectures.html)
- [Data Science Specialization](https://github.com/DataScienceSpecialization/courses)
- [Coursera Big Data Specialization](https://www.coursera.org/specializations/big-data)
- [Statistical Thinking for Data Science and Analytics by Edx](https://www.edx.org/course/statistical-thinking-for-data-science-and-analytic)
- [Cognitive Class AI by IBM](https://cognitiveclass.ai/)
- [Udacity - Deep Learning](https://www.udacity.com/course/intro-to-tensorflow-for-deep-learning--ud187)
- [Keras in Motion](https://www.manning.com/livevideo/keras-in-motion)
- [Microsoft Professional Program for Data Science](https://academy.microsoft.com/en-us/professional-program/tracks/data-science/)
- [COMP3222/COMP6246 - Machine Learning Technologies](https://tdgunes.com/COMP6246-2019Fall/)
- [CS 231 - Convolutional Neural Networks for Visual Recognition](https://cs231n.github.io/)
- [Coursera Tensorflow in practice](https://www.coursera.org/professional-certificates/tensorflow-in-practice)
- [Coursera Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning)
- [365 Data Science Course](https://365datascience.com/)
- [Coursera Natural Language Processing Specialization](https://www.coursera.org/specializations/natural-language-processing)
- [Coursera GAN Specialization](https://www.coursera.org/specializations/generative-adversarial-networks-gans)
- [Codecademy's Data Science](https://www.codecademy.com/learn/paths/data-science)
- [Linear Algebra](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/video-lectures/) - Linear Algebra course by Gilbert Strang
- [A 2020 Vision of Linear Algebra (G. Strang)](https://ocw.mit.edu/resources/res-18-010-a-2020-vision-of-linear-algebra-spring-2020/)
- [Python for Data Science Foundation Course](https://intellipaat.com/academy/course/python-for-data-science-free-training/)
- [Data Science: Statistics & Machine Learning](https://www.coursera.org/specializations/data-science-statistics-machine-learning)
- [Machine Learning Engineering for Production (MLOps)](https://www.coursera.org/specializations/machine-learning-engineering-for-production-mlops)
- [Recommender Systems Specialization from University of Minnesota](https://www.coursera.org/specializations/recommender-systems) is an intermediate/advanced level specialization focused on Recommender System on Coursera platform.
- [Stanford Artificial Intelligence Professional Program](https://online.stanford.edu/programs/artificial-intelligence-professional-program)
- [Data Scientist with Python](https://app.datacamp.com/learn/career-tracks/data-scientist-with-python)


### Intensive Programs
**[`^        back to top        ^`](#awesome-data-science)**

- [S2DS](https://www.s2ds.org/)


### Colleges
**[`^        back to top        ^`](#awesome-data-science)**

- [A list of colleges and universities offering degrees in data science.](https://github.com/ryanswanstrom/awesome-datascience-colleges)
- [Data Science Degree @ Berkeley](https://ischoolonline.berkeley.edu/data-science/)
- [Data Science Degree @ UVA](https://datascience.virginia.edu/)
- [Data Science Degree @ Wisconsin](https://datasciencedegree.wisconsin.edu/)
- [MS in Computer Information Systems @ Boston University](https://www.bu.edu/online/programs/graduate-programs/computer-information-systems-masters-degree/)
- [MS in Business Analytics @ ASU Online](https://asuonline.asu.edu/online-degree-programs/graduate/master-science-business-analytics/)
- [MS in Applied Data Science @ Syracuse](https://ischool.syr.edu/academics/applied-data-science-masters-degree/)
- [M.S. Management & Data Science @ Leuphana](https://www.leuphana.de/en/graduate-school/masters-programmes/management-data-science.html)
- [Master of Data Science @ Melbourne University](https://study.unimelb.edu.au/find/courses/graduate/master-of-data-science/#overview)
- [Msc in Data Science @ The University of Edinburgh](https://www.ed.ac.uk/studying/postgraduate/degrees/index.php?r=site/view&id=902)
- [Master of Management Analytics @ Queen's University](https://smith.queensu.ca/grad_studies/mma/index.php)
- [Master of Data Science @ Illinois Institute of Technology](https://www.iit.edu/academics/programs/data-science-mas)
- [Master of Applied Data Science @ The University of Michigan](https://www.si.umich.edu/programs/master-applied-data-science-online)
- [Master Data Science and Artificial Intelligence @ Eindhoven University of Technology](https://www.tue.nl/en/education/graduate-school/master-data-science-and-artificial-intelligence/)
- [Master's Degree in Data Science and Computer Engineering @ University of Granada](https://masteres.ugr.es/datcom/)

## The Data Science Toolbox
**[`^        back to top        ^`](#awesome-data-science)**

This section is a collection of packages, tools, algorithms, and other useful items in the data science world.

### Algorithms
**[`^        back to top        ^`](#awesome-data-science)**

These are some Machine Learning and Data Mining algorithms and models help you to understand your data and derive meaning from it.

#### Supervised Learning

- Regression
- [Linear Regression](https://en.wikipedia.org/wiki/Linear_regression)
- [Ordinary Least Squares](https://en.wikipedia.org/wiki/Ordinary_least_squares)
- [Logistic Regression](https://en.wikipedia.org/wiki/Logistic_regression)
- [Stepwise Regression](https://en.wikipedia.org/wiki/Stepwise_regression)
- [Multivariate Adaptive Regression Splines](https://en.wikipedia.org/wiki/Multivariate_adaptive_regression_spline)
- Locally Estimated Scatterplot Smoothing
- Classification
  - [k-nearest neighbor](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm)
  - [Support Vector Machines](https://en.wikipedia.org/wiki/Support_vector_machine)
  - [Decision Trees](https://en.wikipedia.org/wiki/Decision_tree)
  - ID3 algorithm
  - C4.5 algorithm
- [Ensemble Learning](https://scikit-learn.org/stable/modules/ensemble.html)
  - Boosting
  - Stacking
  - Bagging
  - Random Forest
  - AdaBoost

#### Unsupervised Learning
- [Clustering](https://scikit-learn.org/stable/modules/clustering.html#clustering)
  - [Hierchical clustering](https://scikit-learn.org/stable/modules/clustering.html#hierarchical-clustering)
  - [k-means](https://scikit-learn.org/stable/modules/clustering.html#k-means)
  - [Density-based clustering](https://scikit-learn.org/stable/modules/clustering.html#dbscan)
  - Fuzzy clustering
  - Mixture models
- Dimension Reduction
  - [Principal Component Analysis (PCA)](https://scikit-learn.org/stable/modules/decomposition.html#principal-component-analysis-pca)
  - [t-SNE; t-distributed Stochastic Neighbor Embedding](https://scikit-learn.org/stable/modules/decomposition.html#principal-component-analysis-pca)
  - [Factor Analysis](https://scikit-learn.org/stable/modules/decomposition.html#factor-analysis)
  - [Latent Dirichlet Allocation (LDA)](https://scikit-learn.org/stable/modules/decomposition.html#latent-dirichlet-allocation-lda)
- Neural Networks
- Self-organizing map
- Adaptive resonance theory
- Hidden Markov Models (HMM)

#### Semi-Supervised Learning

- S3VM
- Clustering
- Generative models
- Low-density separation
- Laplacian regularization
- Heuristic approaches

#### Reinforcement Learning

- Q Learning
- SARSA (State-Action-Reward-State-Action) algorithm
- Temporal difference learning

#### Data Mining Algorithms

- C4.5
- k-Means
- SVM
- Apriori
- EM
- PageRank
- AdaBoost
- kNN
- Naive Bayes
- CART

#### Deep Learning architectures

- Multilayer Perceptron
- Convolutional Neural Network (CNN)
- Recurrent Neural Network (RNN)
- Boltzmann Machines
- Autoencoder
- Generative Adversarial Network (GAN)
- Self-Organized Maps
- Transformer
- Conditional Random Field (CRF)

### General Machine Learning Packages
**[`^        back to top        ^`](#awesome-data-science)**

* [scikit-learn](https://scikit-learn.org/)
* [scikit-multilearn](https://github.com/scikit-multilearn/scikit-multilearn)
* [sklearn-expertsys](https://github.com/tmadl/sklearn-expertsys)
* [scikit-feature](https://github.com/jundongl/scikit-feature)
* [scikit-rebate](https://github.com/EpistasisLab/scikit-rebate)
* [seqlearn](https://github.com/larsmans/seqlearn)
* [sklearn-bayes](https://github.com/AmazaspShumik/sklearn-bayes)
* [sklearn-crfsuite](https://github.com/TeamHG-Memex/sklearn-crfsuite)
* [sklearn-deap](https://github.com/rsteca/sklearn-deap)
* [sigopt_sklearn](https://github.com/sigopt/sigopt-sklearn)
* [sklearn-evaluation](https://github.com/edublancas/sklearn-evaluation)
* [scikit-image](https://github.com/scikit-image/scikit-image)
* [scikit-opt](https://github.com/guofei9987/scikit-opt)
* [scikit-posthocs](https://github.com/maximtrp/scikit-posthocs)
* [pystruct](https://github.com/pystruct/pystruct)
* [Shogun](https://www.shogun-toolbox.org/)
* [xLearn](https://github.com/aksnzhy/xlearn)
* [cuML](https://github.com/rapidsai/cuml)
* [causalml](https://github.com/uber/causalml)
* [mlpack](https://github.com/mlpack/mlpack)
* [MLxtend](https://github.com/rasbt/mlxtend)
* [modAL](https://github.com/modAL-python/modAL)
* [Sparkit-learn](https://github.com/lensacom/sparkit-learn)
* [hyperlearn](https://github.com/danielhanchen/hyperlearn)
* [dlib](https://github.com/davisking/dlib)
* [RuleFit](https://github.com/christophM/rulefit)
* [pyGAM](https://github.com/dswah/pyGAM)
* [Deepchecks](https://github.com/deepchecks/deepchecks)
* [scikit-survival](https://scikit-survival.readthedocs.io/en/stable)

### Deep Learning Packages

#### PyTorch Ecosystem
* [PyTorch](https://github.com/pytorch/pytorch)
* [torchvision](https://github.com/pytorch/vision)
* [torchtext](https://github.com/pytorch/text)
* [torchaudio](https://github.com/pytorch/audio)
* [ignite](https://github.com/pytorch/ignite)
* [PyTorchNet](https://github.com/pytorch/tnt)
* [PyToune](https://github.com/GRAAL-Research/poutyne)
* [skorch](https://github.com/skorch-dev/skorch)
* [PyVarInf](https://github.com/ctallec/pyvarinf)
* [pytorch_geometric](https://github.com/pyg-team/pytorch_geometric)
* [GPyTorch](https://github.com/cornellius-gp/gpytorch)
* [pyro](https://github.com/pyro-ppl/pyro)
* [Catalyst](https://github.com/catalyst-team/catalyst)
* [pytorch_tabular](https://github.com/manujosephv/pytorch_tabular)

#### TensorFlow Ecosystem
* [TensorFlow](https://github.com/tensorflow/tensorflow)
* [TensorLayer](https://github.com/tensorlayer/TensorLayer)
* [TFLearn](https://github.com/tflearn/tflearn)
* [Sonnet](https://github.com/deepmind/sonnet)
* [tensorpack](https://github.com/tensorpack/tensorpack)
* [TRFL](https://github.com/deepmind/trfl)
* [Polyaxon](https://github.com/polyaxon/polyaxon)
* [NeuPy](https://github.com/itdxer/neupy)
* [tfdeploy](https://github.com/riga/tfdeploy)
* [tensorflow-upstream](https://github.com/ROCmSoftwarePlatform/tensorflow-upstream)
* [TensorFlow Fold](https://github.com/tensorflow/fold)
* [tensorlm](https://github.com/batzner/tensorlm)
* [TensorLight](https://github.com/bsautermeister/tensorlight)
* [Mesh TensorFlow](https://github.com/tensorflow/mesh)
* [Ludwig](https://github.com/ludwig-ai/ludwig)
* [TF-Agents](https://github.com/tensorflow/agents)
* [TensorForce](https://github.com/tensorforce/tensorforce)

#### Keras Ecosystem

* [Keras](https://keras.io)
* [keras-contrib](https://github.com/keras-team/keras-contrib)
* [Hyperas](https://github.com/maxpumperla/hyperas)
* [Elephas](https://github.com/maxpumperla/elephas)
* [Hera](https://github.com/keplr-io/hera)
* [Spektral](https://github.com/danielegrattarola/spektral)
* [qkeras](https://github.com/google/qkeras)
* [keras-rl](https://github.com/keras-rl/keras-rl)
* [Talos](https://github.com/autonomio/talos)

#### Visualization Tools
**[`^        back to top        ^`](#awesome-data-science)**

- [altair](https://altair-viz.github.io/)
- [addepar](https://opensource.addepar.com/ember-charts/#/overview)
- [amcharts](https://www.amcharts.com/)
- [anychart](https://www.anychart.com/)
- [bokeh](https://bokeh.org/)
- [Comet](https://www.comet.com/site/products/ml-experiment-tracking/?utm_source=awesome-datascience)
- [slemma](https://slemma.com/)
- [cartodb](https://cartodb.github.io/odyssey.js/)
- [Cube](https://square.github.io/cube/)
- [d3plus](https://d3plus.org/)
- [Data-Driven Documents(D3js)](https://d3js.org/)
- [dygraphs](https://dygraphs.com/)
- [ECharts](https://echarts.baidu.com/index-en.html)
- [exhibit](https://www.simile-widgets.org/exhibit/)
- [gephi](https://gephi.org/)
- [ggplot2](https://ggplot2.tidyverse.org/)
- [Glue](http://docs.glueviz.org/en/latest/index.html)
- [Google Chart Gallery](https://developers.google.com/chart/interactive/docs/gallery)
- [highcarts](https://www.highcharts.com/)
- [import.io](https://www.import.io/)
- [jqplot](https://www.jqplot.com/)
- [Matplotlib](https://matplotlib.org/)
- [nvd3](https://nvd3.org/)
- [Netron](https://github.com/lutzroeder/netron)
- [Openrefine](https://openrefine.org/)
- [plot.ly](https://plot.ly/)
- [raw](https://rawgraphs.io)
- [Seaborn](https://seaborn.pydata.org/)
- [techanjs](https://techanjs.org/)
- [Timeline](https://timeline.knightlab.com/)
- [variancecharts](https://variancecharts.com/index.html)
- [vida](https://vida.io/)
- [vizzu](https://github.com/vizzuhq/vizzu-lib)
- [Wrangler](http://vis.stanford.edu/wrangler/)
- [r2d3](https://www.r2d3.us/visual-intro-to-machine-learning-part-1/)
- [NetworkX](https://networkx.org/)
- [Redash](https://redash.io/)
- [C3](https://c3js.org/)
- [TensorWatch](https://github.com/microsoft/tensorwatch)

### Miscellaneous Tools
**[`^        back to top        ^`](#awesome-data-science)**

| Link | Description |
| --- | --- |
| [The Data Science Lifecycle Process](https://github.com/dslp/dslp) | The Data Science Lifecycle Process is a process for taking data science teams from Idea to Value repeatedly and sustainably. The process is documented in this repo  |
| [Data Science Lifecycle Template Repo](https://github.com/dslp/dslp-repo-template) | Template repository for data science lifecycle project  |
| [RexMex](https://github.com/AstraZeneca/rexmex) | A general purpose recommender metrics library for fair evaluation.  |
| [ChemicalX](https://github.com/AstraZeneca/chemicalx) | A PyTorch based deep learning library for drug pair scoring.  |
| [PyTorch Geometric Temporal](https://github.com/benedekrozemberczki/pytorch_geometric_temporal) | Representation learning on dynamic graphs.  |
| [Little Ball of Fur](https://github.com/benedekrozemberczki/littleballoffur) | A graph sampling library for NetworkX with a Scikit-Learn like API.  |
| [Karate Club](https://github.com/benedekrozemberczki/karateclub) | An unsupervised machine learning extension library for NetworkX with a Scikit-Learn like API. |
| [ML Workspace](https://github.com/ml-tooling/ml-workspace) | All-in-one web-based IDE for machine learning and data science. The workspace is deployed as a Docker container and is preloaded with a variety of popular data science libraries (e.g., Tensorflow, PyTorch) and dev tools (e.g., Jupyter, VS Code) |
| [Neptune.ai](https://neptune.ai) | Community-friendly platform supporting data scientists in creating and sharing machine learning models. Neptune facilitates teamwork, infrastructure management, models comparison and reproducibility. |
| [steppy](https://github.com/minerva-ml/steppy) | Lightweight, Python library for fast and reproducible machine learning experimentation. Introduces very simple interface that enables clean machine learning pipeline design. |
| [steppy-toolkit](https://github.com/minerva-ml/steppy-toolkit) | Curated collection of the neural networks, transformers and models that make your machine learning work faster and more effective. |
| [Datalab from Google](https://cloud.google.com/datalab/docs/) | easily explore, visualize, analyze, and transform data using familiar languages, such as Python and SQL, interactively. |
| [Hortonworks Sandbox](https://www.cloudera.com/downloads/hortonworks-sandbox.html) | is a personal, portable Hadoop environment that comes with a dozen interactive Hadoop tutorials. |
| [R](https://www.r-project.org/) | is a free software environment for statistical computing and graphics. |
| [Tidyverse](https://www.tidyverse.org/) | is an opinionated collection of R packages designed for data science. All packages share an underlying design philosophy, grammar, and data structures. |
| [RStudio](https://www.rstudio.com) | IDE – powerful user interface for R. It’s free and open source, works on Windows, Mac, and Linux. |
| [Python - Pandas - Anaconda](https://www.anaconda.com) | Completely free enterprise-ready Python distribution for large-scale data processing, predictive analytics, and scientific computing |
| [Pandas GUI](https://github.com/adrotog/PandasGUI) | Pandas GUI |
| [Scikit-Learn](https://scikit-learn.org/stable/) | Machine Learning in Python |
| [NumPy](https://numpy.org/) | NumPy is fundamental for scientific computing with Python. It supports large, multi-dimensional arrays and matrices and includes an assortment of high-level mathematical functions to operate on these arrays. |
| [Vaex](https://vaex.io/) | Vaex is a Python library that allows you to visualize large datasets and calculate statistics at high speeds. |
| [SciPy](https://scipy.org/) | SciPy works with NumPy arrays and provides efficient routines for numerical integration and optimization. |
| [Data Science Toolbox](https://www.coursera.org/learn/data-scientists-tools) | Coursera Course |
| [Data Science Toolbox](https://datasciencetoolbox.org/) | Blog |
| [Wolfram Data Science Platform](https://www.wolfram.com/data-science-platform/) | Take numerical, textual, image, GIS or other data and give it the Wolfram treatment, carrying out a full spectrum of data science analysis and visualization and automatically generating rich interactive reports—all powered by the revolutionary knowledge-based Wolfram Language. |
| [Datadog](https://www.datadoghq.com/) | Solutions, code, and devops for high-scale data science. |
| [Variance](https://variancecharts.com/) | Build powerful data visualizations for the web without writing JavaScript |
| [Kite Development Kit](https://kitesdk.org/docs/current/index.html) | The Kite Software Development Kit (Apache License, Version 2.0) , or Kite for short, is a set of libraries, tools, examples, and documentation focused on making it easier to build systems on top of the Hadoop ecosystem. |
| [Domino Data Labs](https://www.dominodatalab.com) | Run, scale, share, and deploy your models — without any infrastructure or setup. |
| [Apache Flink](https://flink.apache.org/) | A platform for efficient, distributed, general-purpose data processing. |
| [Apache Hama](https://hama.apache.org/) | Apache Hama is an Apache Top-Level open source project, allowing you to do advanced analytics beyond MapReduce. |
| [Weka](https://www.cs.waikato.ac.nz/ml/weka/) | Weka is a collection of machine learning algorithms for data mining tasks. |
| [Octave](https://www.gnu.org/software/octave/) | GNU Octave is a high-level interpreted language, primarily intended for numerical computations.(Free Matlab) |
| [Apache Spark](https://spark.apache.org/) | Lightning-fast cluster computing |
| [Hydrosphere Mist](https://github.com/Hydrospheredata/mist) | a service for exposing Apache Spark analytics jobs and machine learning models as realtime, batch or reactive web services. |
| [Data Mechanics](https://www.datamechanics.co) | A data science and engineering platform making Apache Spark more developer-friendly and cost-effective. |
| [Caffe](https://caffe.berkeleyvision.org/) | Deep Learning Framework |
| [Torch](https://torch.ch/) | A SCIENTIFIC COMPUTING FRAMEWORK FOR LUAJIT |
| [Nervana's python based Deep Learning Framework](https://github.com/NervanaSystems/neon) | .  |
| [Skale](https://github.com/skale-me/skale) | High performance distributed data processing in NodeJS |
| [Aerosolve](https://airbnb.io/aerosolve/) | A machine learning package built for humans. |
| [Intel framework](https://github.com/intel/idlf) | Intel® Deep Learning Framework |
| [Datawrapper](https://www.datawrapper.de/) | An open source data visualization platform helping everyone to create simple, correct and embeddable charts. Also at [github.com](https://github.com/datawrapper/datawrapper) |
| [Tensor Flow](https://www.tensorflow.org/) | TensorFlow is an Open Source Software Library for Machine Intelligence |
| [Natural Language Toolkit](https://www.nltk.org/) | An introductory yet powerful toolkit for natural language processing and classification |
| [Annotation Lab](https://www.johnsnowlabs.com/annotation-lab/) | Free End-to-End No-Code platform for text annotation and DL model training/tuning. Out-of-the-box support for Named Entity Recognition, Classification, Relation extraction and Assertion Status Spark NLP models. Unlimited support for users, teams, projects, documents. |
| [nlp-toolkit for node.js](https://www.npmjs.com/package/nlp-toolkit) | .  |
| [Julia](https://julialang.org) | high-level, high-performance dynamic programming language for technical computing |
| [IJulia](https://github.com/JuliaLang/IJulia.jl) | a Julia-language backend combined with the Jupyter interactive environment |
| [Apache Zeppelin](https://zeppelin.apache.org/) | Web-based notebook that enables data-driven, interactive data analytics and collaborative documents with SQL, Scala and more  |
| [Featuretools](https://github.com/alteryx/featuretools) | An open source framework for automated feature engineering written in python |
| [Optimus](https://github.com/hi-primus/optimus) | Cleansing, pre-processing, feature engineering, exploratory data analysis and easy ML with PySpark backend.  |
| [Albumentations](https://github.com/albumentations-team/albumentations) | А fast and framework agnostic image augmentation library that implements a diverse set of augmentation techniques. Supports classification, segmentation, detection out of the box. Was used to win a number of Deep Learning competitions at Kaggle, Topcoder and those that were a part of the CVPR workshops. |
| [DVC](https://github.com/iterative/dvc) | An open-source data science version control system. It helps track, organize and make data science projects reproducible. In its very basic scenario it helps version control and share large data and model files. |
| [Lambdo](https://github.com/asavinov/lambdo) | is a workflow engine which significantly simplifies data analysis by combining in one analysis pipeline (i) feature engineering and machine learning (ii) model training and prediction (iii) table population and column evaluation. |
| [Feast](https://github.com/feast-dev/feast) | A feature store for the management, discovery, and access of machine learning features. Feast provides a consistent view of feature data for both model training and model serving. |
| [Polyaxon](https://github.com/polyaxon/polyaxon) | A platform for reproducible and scalable machine learning and deep learning. |
| [LightTag](https://www.lighttag.io/) | Text Annotation Tool for teams |
| [UBIAI](https://ubiai.tools) | Easy-to-use text annotation tool for teams with most comprehensive auto-annotation features. Supports NER, relations and document classification as well as OCR annotation for invoice labeling |
| [Trains](https://github.com/allegroai/clearml) | Auto-Magical Experiment Manager, Version Control & DevOps for AI |
| [Hopsworks](https://github.com/logicalclocks/hopsworks) | Open-source data-intensive machine learning platform with a feature store. Ingest and manage features for both online (MySQL Cluster)  and offline (Apache Hive) access, train and serve models at scale. |
| [MindsDB](https://github.com/mindsdb/mindsdb) | MindsDB is an Explainable AutoML framework for developers. With MindsDB you can build, train and use state of the art ML models in as simple as one line of code. |
| [Lightwood](https://github.com/mindsdb/lightwood) | A Pytorch based framework that breaks down machine learning problems into smaller blocks that can be glued together seamlessly with an objective to build predictive models with one line of code. |
| [AWS Data Wrangler](https://github.com/awslabs/aws-data-wrangler) | An open-source Python package that extends the power of Pandas library to AWS connecting DataFrames and AWS data related services (Amazon Redshift, AWS Glue, Amazon Athena, Amazon EMR, etc). |
| [Amazon Rekognition](https://aws.amazon.com/rekognition/) | AWS Rekognition is a service that lets developers working with Amazon Web Services add image analysis to their applications. Catalog assets, automate workflows, and extract meaning from your media and applications.|
| [Amazon Textract](https://aws.amazon.com/textract/) | Automatically extract printed text, handwriting, and data from any document. |
| [Amazon Lookout for Vision](https://aws.amazon.com/lookout-for-vision/) | Spot product defects using computer vision to automate quality inspection. Identify missing product components, vehicle and structure damage, and irregularities for comprehensive quality control.|
| [Amazon CodeGuru](https://aws.amazon.com/codeguru/) | Automate code reviews and optimize application performance with ML-powered recommendations.|
| [CML](https://github.com/iterative/cml) | An open source toolkit for using continuous integration in data science projects. Automatically train and test models in production-like environments with GitHub Actions & GitLab CI, and autogenerate visual reports on pull/merge requests. |
| [Dask](https://dask.org/) | An open source Python library to painlessly transition your analytics code to distributed computing systems (Big Data) |
| [Statsmodels](https://www.statsmodels.org/stable/index.html) | A Python-based inferential statistics, hypothesis testing and regression framework |
| [Gensim](https://radimrehurek.com/gensim/) | An open-source library for topic modeling of natural language text |
| [spaCy](https://spacy.io/) | A performant natural language processing toolkit |
| [Grid Studio](https://github.com/ricklamers/gridstudio) | Grid studio is a web-based spreadsheet application with full integration of the Python programming language. |
|[Python Data Science Handbook](https://github.com/jakevdp/PythonDataScienceHandbook)|Python Data Science Handbook: full text in Jupyter Notebooks|
| [Shapley](https://github.com/benedekrozemberczki/shapley) | A data-driven framework to quantify the value of classifiers in a machine learning ensemble.  |
| [DAGsHub](https://dagshub.com) | A platform built on open source tools for data, model and pipeline management.  |
| [Deepnote](https://deepnote.com) | A new kind of data science notebook. Jupyter-compatible, with real-time collaboration and running in the cloud. |
| [Valohai](https://valohai.com) | An MLOps platform that handles machine orchestration, automatic reproducibility and deployment. |
| [PyMC3](https://docs.pymc.io/) | A Python Library for Probabalistic Programming (Bayesian Inference and Machine Learning) |
| [PyStan](https://pypi.org/project/pystan/) | Python interface to Stan (Bayesian inference and modeling) |
| [hmmlearn](https://pypi.org/project/hmmlearn/) | Unsupervised learning and inference of Hidden Markov Models |
| [Chaos Genius](https://github.com/chaos-genius/chaos_genius/) | ML powered analytics engine for outlier/anomaly detection and root cause analysis |
| [Nimblebox](https://nimblebox.ai/) | A full-stack MLOps platform designed to help data scientists and machine learning practitioners around the world discover, create, and launch multi-cloud apps from their web browser. |
| [Towhee](https://github.com/towhee-io/towhee) | A Python library that helps you encode your unstructured data into embeddings. |
| [LineaPy](https://github.com/LineaLabs/lineapy) | Ever been frustrated with cleaning up long, messy Jupyter notebooks? With LineaPy, an open source Python library, it takes as little as two lines of code to transform messy development code into production pipelines. |
| [envd](https://github.com/tensorchord/envd) | 🏕️ machine learning development environment for data science and AI/ML engineering teams |
| [Explore Data Science Libraries](https://kandi.openweaver.com/explore/data-science) | A search engine 🔎 tool to discover & find a curated list of popular & new libraries, top authors, trending project kits, discussions, tutorials & learning resources |
| [MLEM](https://github.com/iterative/mlem) | 🐶 Version and deploy your ML models following GitOps principles |
| [MLflow](https://mlflow.org/) | MLOps framework for managing ML models across their full lifecycle |

## Literature and Media
**[`^        back to top        ^`](#awesome-data-science)**

This section includes some additional reading material, channels to watch, and talks to listen to.

### Books
**[`^        back to top        ^`](#awesome-data-science)**

- [Data Science From Scratch: First Principles with Python](https://www.amazon.com/Data-Science-Scratch-Principles-Python-dp-1492041130/dp/1492041130/ref=dp_ob_title_bk)
- [Artificial Intelligence with Python - Tutorialspoint](https://www.tutorialspoint.com/artificial_intelligence_with_python/artificial_intelligence_with_python_tutorial.pdf)
- [Machine Learning from Scratch](https://dafriedman97.github.io/mlbook/content/introduction.html)
- [Probabilistic Machine Learning: An Introduction](https://probml.github.io/pml-book/book1.html)
- [A Comprehensive Guide to Machine Learning](https://www.eecs189.org/static/resources/comprehensive-guide.pdf)
- [How to Lead in Data Science](https://www.manning.com/books/how-to-lead-in-data-science) - Early access
- [Fighting Churn With Data](https://www.manning.com/books/fighting-churn-with-data)
- [Data Science at Scale with Python and Dask](https://www.manning.com/books/data-science-with-python-and-dask)
- [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)
- [The Data Science Handbook: Advice and Insights from 25 Amazing Data Scientists](https://www.thedatasciencehandbook.com/)
- [Think Like a Data Scientist](https://www.manning.com/books/think-like-a-data-scientist)
- [Introducing Data Science](https://www.manning.com/books/introducing-data-science)
- [Practical Data Science with R](https://www.manning.com/books/practical-data-science-with-r)
- [Everyday Data Science](https://www.amazon.com/dp/B08TZ1MT3W/ref=cm_sw_r_cp_apa_fabc_a0ceGbWECF9A8) & [(cheaper PDF version)](https://gum.co/everydaydata)
- [Exploring Data Science](https://www.manning.com/books/exploring-data-science) - free eBook sampler
- [Exploring the Data Jungle](https://www.manning.com/books/exploring-the-data-jungle) - free eBook sampler
- [Classic Computer Science Problems in Python](https://www.manning.com/books/classic-computer-science-problems-in-python)
- [Math for Programmers](https://www.manning.com/books/math-for-programmers) Early access
- [R in Action, Third Edition](https://www.manning.com/books/r-in-action-third-edition) Early access
- [Data Science Bookcamp](https://www.manning.com/books/data-science-bookcamp) Early access
- [Data Science Thinking: The Next Scientific, Technological and Economic Revolution](https://www.springer.com/gp/book/9783319950914)
- [Applied Data Science: Lessons Learned for the Data-Driven Business](https://www.springer.com/gp/book/9783030118204)
- [The Data Science Handbook](https://www.amazon.com/Data-Science-Handbook-Field-Cady/dp/1119092949)
- [Essential Natural Language Processing](https://www.manning.com/books/getting-started-with-natural-language-processing) - Early access
- [Mining Massive Datasets](https://www.mmds.org/) - free e-book comprehended by an online course
- [Pandas in Action](https://www.manning.com/books/pandas-in-action) - Early access
- [Genetic Algorithms and Genetic Programming](https://www.taylorfrancis.com/books/9780429141973)
- [Advances in Evolutionary Algorithms](https://www.intechopen.com/books/advances_in_evolutionary_algorithms) - Free Download
- [Genetic Programming: New Approaches and Successful Applications](https://www.intechopen.com/books/genetic-programming-new-approaches-and-successful-applications) - Free Download
- [Evolutionary Algorithms](https://www.intechopen.com/books/evolutionary-algorithms) - Free Download
- [Advances in Genetic Programming, Vol. 3](https://www.cs.bham.ac.uk/~wbl/aigp3/) - Free Download
- [Global Optimization Algorithms: Theory and Application](https://www.it-weise.de/projects/book.pdf) - Free Download
- [Genetic Algorithms and Evolutionary Computation](https://www.talkorigins.org/faqs/genalg/genalg.html) - Free Download
- [Convex Optimization](https://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf) - Convex Optimization book by Stephen Boyd - Free Download
- [Data Analysis with Python and PySpark](https://www.manning.com/books/data-analysis-with-python-and-pyspark) - Early access
- [R for Data Science](https://r4ds.had.co.nz/)
- [Build a Career in Data Science](https://www.manning.com/books/build-a-career-in-data-science)
- [Machine Learning Bookcamp](https://mlbookcamp.com/) - Early access
- [Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow, 2nd Edition](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/)
- [Effective Data Science Infrastructure](https://www.manning.com/books/effective-data-science-infrastructure)
- [Practical MLOps: How to Get Ready for Production Models](https://valohai.com/mlops-ebook/)
- [Data Analysis with Python and PySpark](https://www.manning.com/books/data-analysis-with-python-and-pyspark)
- [Regression, a Friendly guide](https://www.manning.com/books/regression-a-friendly-guide) - Early access
- [Streaming Systems: The What, Where, When, and How of Large-Scale Data Processing](https://www.oreilly.com/library/view/streaming-systems/9781491983867/)
- [Data Science at the Command Line: Facing the Future with Time-Tested Tools](https://www.oreilly.com/library/view/data-science-at/9781491947845/)
- [Machine Learning - CIn UFPE](https://www.cin.ufpe.br/~cavmj/Machine%20-%20Learning%20-%20Tom%20Mitchell.pdf)
- [Machine Learning with Python - Tutorialspoint](https://www.tutorialspoint.com/machine_learning_with_python/machine_learning_with_python_tutorial.pdf)
- [Deep Learning](https://www.deeplearningbook.org/)
- [Designing Cloud Data Platforms](https://www.manning.com/books/designing-cloud-data-platforms) - Early access
- [An Introduction to Statistical Learning with Applications in R](https://www.statlearning.com/)
- [The Elements of Statistical Learning: Data Mining, Inference, and Prediction](https://hastie.su.domains/ElemStatLearn/)
- [Deep Learning with PyTorch](https://www.simonandschuster.com/books/Deep-Learning-with-PyTorch/Eli-Stevens/9781617295263)
- [Neural Networks and Deep Learning](https://neuralnetworksanddeeplearning.com)
- [Deep Learning Cookbook](https://www.oreilly.com/library/view/deep-learning-cookbook/9781491995839/)
- [Introduction to Machine Learning with Python](https://www.oreilly.com/library/view/introduction-to-machine/9781449369880/)
- [Artificial Intelligence: Foundations of Computational Agents, 2nd Edition](https://artint.info/index.html) - Free HTML version
- [The Quest for Artificial Intelligence: A History of Ideas and Achievements](https://ai.stanford.edu/~nilsson/QAI/qai.pdf) - Free Download
- [Graph Algorithms for Data Science](https://www.manning.com/books/graph-algorithms-for-data-science) - Early access
- [Data Mesh in Action](https://www.manning.com/books/data-mesh-in-action) - Early access
- [Julia for Data Analysis](https://www.manning.com/books/julia-for-data-analysis) - Early access
- [Casual Inference for Data Science](https://www.manning.com/books/julia-for-data-analysis) - Early access
- [Dive into Deep Learning](https://d2l.ai/)
- [Interpretable Machine Learning: A Guide for Making Black Box Models Explainable](https://christophm.github.io/interpretable-ml-book/) - Free GitHub version
- [Foundations of Data Science](https://www.cs.cornell.edu/jeh/book.pdf) Free Download 
- [Comet for DataScience: Enhance your ability to manage and optimize the life cycle of your data science project](https://www.amazon.com/Comet-Data-Science-Enhance-optimize/dp/1801814430) 

#### Book Deals (Affiliated) 🛍

- [eBook sale - Save up to 45% on eBooks!](https://www.manning.com/?utm_source=mikrobusiness&utm_medium=affiliate&utm_campaign=ebook_sale_8_8_22)

- [Causal Machine Learning](https://www.manning.com/books/causal-machine-learning?utm_source=mikrobusiness&utm_medium=affiliate&utm_campaign=book_ness_causal_7_26_22&a_aid=mikrobusiness&a_bid=43a2198b
)
- [Managing ML Projects](https://www.manning.com/books/managing-machine-learning-projects?utm_source=mikrobusiness&utm_medium=affiliate&utm_campaign=book_thompson_managing_6_14_22)
- [Causal Inference for Data Science](https://www.manning.com/books/causal-inference-for-data-science?utm_source=mikrobusiness&utm_medium=affiliate&utm_campaign=book_ruizdevilla_causal_6_6_22)
- [Data for All](https://www.manning.com/books/data-for-all?utm_source=mikrobusiness&utm_medium=affiliate)

### Journals, Publications and Magazines
**[`^        back to top        ^`](#awesome-data-science)**

- [ICML](https://icml.cc/2015/) - International Conference on Machine Learning
- [GECCO](https://gecco-2019.sigevo.org/index.html/HomePage) - The Genetic and Evolutionary Computation Conference (GECCO)
- [epjdatascience](https://epjdatascience.springeropen.com/)
- [Journal of Data Science](https://jds-online.org/journal/JDS) - an international journal devoted to applications of statistical methods at large
- [Big Data Research](https://www.journals.elsevier.com/big-data-research)
- [Journal of Big Data](https://journalofbigdata.springeropen.com/)
- [Big Data & Society](https://journals.sagepub.com/home/bds)
- [Data Science Journal](https://www.jstage.jst.go.jp/browse/dsj)
- [datatau.com/news](https://www.datatau.com/news) - Like Hacker News, but for data
- [Data Science Trello Board](https://trello.com/b/rbpEfMld/data-science)
- [Medium Data Science Topic](https://medium.com/tag/data-science) - Data Science related publications on medium
- [Towards Data Science Genetic Algorithm Topic](https://towardsdatascience.com/introduction-to-genetic-algorithms-including-example-code-e396e98d8bf3#:~:text=A%20genetic%20algorithm%20is%20a,offspring%20of%20the%20next%20generation.) -Genetic Algorithm related Publications onTowards Data Science
- [all AI news](https://allainews.com/) - The AI/ML/Big Data news aggregator platform

### Newsletters
**[`^        back to top        ^`](#awesome-data-science)**

- [AI Digest](https://aidigest.net/). A weekly newsletter to keep up to date with AI, machine learning, and data science. [Archive](https://aidigest.net/digests).
- [DataTalks.Club](https://datatalks.club). A weekly newsletter about data-related things. [Archive](https://us19.campaign-archive.com/home/?u=0d7822ab98152f5afc118c176&id=97178021aa).
- [The Analytics Engineering Roundup](https://roundup.getdbt.com/about). A newsletter about data science. [Archive](https://roundup.getdbt.com/archive).

### Bloggers
**[`^        back to top        ^`](#awesome-data-science)**

- [Wes McKinney](https://wesmckinney.com/archives.html) - Wes McKinney Archives.
- [Matthew Russell](https://miningthesocialweb.com/) - Mining The Social Web.
- [Greg Reda](https://www.gregreda.com/) - Greg Reda Personal Blog
- [Kevin Davenport](https://kldavenport.com/) - Kevin Davenport Personal Blog
- [Julia Evans](https://jvns.ca/) - Recurse Center alumna
- [Hakan Kardas](https://www.cse.unr.edu/~hkardes/) - Personal Web Page
- [Sean J. Taylor](https://seanjtaylor.com/) - Personal Web Page
- [Drew Conway](https://drewconway.com/) - Personal Web Page
- [Hilary Mason](https://hilarymason.com/) - Personal Web Page
- [Noah Iliinsky](https://complexdiagrams.com/) - Personal Blog
- [Matt Harrison](https://hairysun.com/) - Personal Blog
- [Vamshi Ambati](https://allthingsds.wordpress.com/) - AllThings Data Sciene
- [Prash Chan](https://www.mdmgeek.com/) - Tech Blog on Master Data Management And Every Buzz Surrounding It
- [Clare Corthell](https://datasciencemasters.org/) - The Open Source Data Science Masters
- [Paul Miller](https://cloudofdata.com/) Based in the UK and working globally, Cloud of Data's consultancy services help clients understand the implications of taking data and more to the Cloud.
- [Data Science London](https://datasciencelondon.org/) Data Science London is a non-profit organization dedicated to the free, open, dissemination of data science.
  We are the largest data science community in Europe.
  We are more than 3,190 data scientists and data geeks in our community.
- [Datawrangling](http://www.datawrangling.org) by Peter Skomoroch. MACHINE LEARNING, DATA MINING, AND MORE
- [Quora Data Science](https://www.quora.com/topic/Data-Science) - Data Science Questions and Answers from experts
- [Siah](https://openresearch.wordpress.com/) a PhD student at Berkeley
- [Louis Dorard](https://www.ownml.co/blog/) a technology guy with a penchant for the web and for data, big and small
- [Machine Learning Mastery](https://machinelearningmastery.com/) about helping professional programmers to confidently apply machine learning algorithms to address complex problems.
- [Daniel Forsyth](https://www.danielforsyth.me/) - Personal Blog
- [Data Science Weekly](https://www.datascienceweekly.org/) - Weekly News Blog
- [Revolution Analytics](https://blog.revolutionanalytics.com/) - Data Science Blog
- [R Bloggers](https://www.r-bloggers.com/) - R Bloggers
- [The Practical Quant](https://practicalquant.blogspot.com/) Big data
- [Yet Another Data Blog](https://yet-another-data-blog.blogspot.com/) Yet Another Data Blog
- [Spenczar](https://spenczar.com/) a data scientist at _Twitch_. I handle the whole data pipeline, from tracking to model-building to reporting.
- [KD Nuggets](https://www.kdnuggets.com/) Data Mining, Analytics, Big Data, Data, Science not a blog a portal
- [Meta Brown](https://www.metabrown.com/blog/) - Personal Blog
- [Data Scientist](https://datascientists.net/) is building the data scientist culture.
- [WhatSTheBigData](https://whatsthebigdata.com/) is some of, all of, or much more than the above and this blog explores its impact on information technology, the business world, government agencies, and our lives.
- [Tevfik Kosar](https://magnus-notitia.blogspot.com/) - Magnus Notitia
- [New Data Scientist](https://newdatascientist.blogspot.com/) How a Social Scientist Jumps into the World of Big Data
- [Harvard Data Science](https://harvarddatascience.com/) - Thoughts on Statistical Computing and Visualization
- [Data Science 101](https://ryanswanstrom.com/datascience101/) - Learning To Be A Data Scientist
- [Kaggle Past Solutions](https://www.chioka.in/kaggle-competition-solutions/)
- [DataScientistJourney](https://datascientistjourney.wordpress.com/category/data-science/)
- [NYC Taxi Visualization Blog](https://chriswhong.github.io/nyctaxi/)
- [Learning Lover](https://learninglover.com/blog/)
- [Dataists](https://www.dataists.com/)
- [Data-Mania](https://www.data-mania.com/)
- [Data-Magnum](https://data-magnum.com/)
- [P-value](https://www.p-value.info/) - Musings on data science, machine learning and stats.
- [datascopeanalytics](https://datascopeanalytics.com/blog/)
- [Digital transformation](https://tarrysingh.com/)
- [datascientistjourney](https://datascientistjourney.wordpress.com/category/data-science/)
- [Data Mania Blog](https://www.data-mania.com/blog/) - [The File Drawer](https://chris-said.io/) - Chris Said's science blog
- [Emilio Ferrara's web page](https://www.emilio.ferrara.name/)
- [DataNews](https://datanews.tumblr.com/)
- [Reddit TextMining](https://www.reddit.com/r/textdatamining/)
- [Periscopic](https://periscopic.com/#!/news)
- [Hilary Parker](https://hilaryparker.com/)
- [Data Stories](https://datastori.es/)
- [Data Science Lab](https://datasciencelab.wordpress.com/)
- [Meaning of](https://www.kennybastani.com/)
- [Adventures in Data Land](https://blog.smola.org)
- [DATA MINERS BLOG](https://blog.data-miners.com/)
- [Dataclysm](https://theblog.okcupid.com/)
- [FlowingData](https://flowingdata.com/) - Visualization and Statistics
- [Calculated Risk](https://www.calculatedriskblog.com/)
- [O'reilly Learning Blog](https://www.oreilly.com/content/topics/oreilly-learning/)
- [Dominodatalab](https://blog.dominodatalab.com/)
- [i am trask](https://iamtrask.github.io/) - A Machine Learning Craftsmanship Blog
- [Vademecum of Practical Data Science](https://datasciencevademecum.wordpress.com/) - Handbook and recipes for data-driven solutions of real-world problems
- [Dataconomy](https://dataconomy.com/) - A blog on the new emerging data economy
- [Springboard](https://www.springboard.com/blog/) - A blog with resources for data science learners
- [Analytics Vidhya](https://www.analyticsvidhya.com/) - A full-fledged website about data science and analytics study material.
- [Occam's Razor](https://www.kaushik.net/avinash/) - Focused on Web Analytics.
- [Data School](https://www.dataschool.io/) - Data science tutorials for beginners!
- [Colah's Blog](https://colah.github.io) - Blog for understanding Neural Networks!
- [Sebastian's Blog](https://ruder.io/#open) - Blog for NLP and transfer learning!
- [Distill](https://distill.pub) - Dedicated to clear explanations of machine learning!
- [Chris Albon's Website](https://chrisalbon.com/) - Data Science and AI notes
- [Andrew Carr](https://andrewnc.github.io/blog/blog.html) - Data Science with Esoteric programming languages
- [floydhub](https://blog.floydhub.com/introduction-to-genetic-algorithms/) - Blog for Evolutionary Algorithms
- [Jingles](https://jinglescode.github.io/) - Review and extract key concepts from academic papers
- [nbshare](https://www.nbshare.io/notebooks/data-science/) - Data Science notebooks
- [Deep and Shallow](https://deep-and-shallow.com/) - All things Deep and Shallow in Data Science
- [Loic Tetrel](https://ltetrel.github.io/) - Data science blog
- [Chip Huyen's Blog](https://huyenchip.com/blog/) - ML Engineering, MLOps, and the use of ML in startups
- [Maria Khalusova](https://www.mariakhalusova.com/) - Data science blog
- [Aditi Rastogi](https://medium.com/@aditi2507rastogi) - ML,DL,Data Science blog

### Presentations
**[`^        back to top        ^`](#awesome-data-science)**

- [How to Become a Data Scientist](https://www.slideshare.net/ryanorban/how-to-become-a-data-scientist)
- [Introduction to Data Science](https://www.slideshare.net/NikoVuokko/introduction-to-data-science-25391618)
- [Intro to Data Science for Enterprise Big Data](https://www.slideshare.net/pacoid/intro-to-data-science-for-enterprise-big-data)
- [How to Interview a Data Scientist](https://www.slideshare.net/dtunkelang/how-to-interview-a-data-scientist)
- [How to Share Data with a Statistician](https://github.com/jtleek/datasharing)
- [The Science of a Great Career in Data Science](https://www.slideshare.net/katemats/the-science-of-a-great-career-in-data-science)
- [What Does a Data Scientist Do?](https://www.slideshare.net/datasciencelondon/big-data-sorry-data-science-what-does-a-data-scientist-do)
- [Building Data Start-Ups: Fast, Big, and Focused](https://www.slideshare.net/medriscoll/driscoll-strata-buildingdatastartups25may2011clean)
- [How to win data science competitions with Deep Learning](https://www.slideshare.net/0xdata/how-to-win-data-science-competitions-with-deep-learning)
- [Full-Stack Data Scientist](https://www.slideshare.net/AlexeyGrigorev/fullstack-data-scientist)

### Podcasts
**[`^        back to top        ^`](#awesome-data-science)**

- [AI at Home](https://podcasts.apple.com/us/podcast/data-science-at-home/id1069871378)
- [AI Today](https://www.cognilytica.com/aitoday/)
- [Adversarial Learning](https://adversariallearning.com/)
- [Becoming a Data Scientist](https://www.becomingadatascientist.com/category/podcast/)
- [Chai time Data Science](https://www.youtube.com/playlist?list=PLLvvXm0q8zUbiNdoIazGzlENMXvZ9bd3x)
- [Data Crunch](https://datacrunchcorp.com/data-crunch-podcast/)
- [Data Engineering Podcast](https://www.dataengineeringpodcast.com/)
- [Data Science at Home](https://datascienceathome.com/)
- [Data Science Mixer](https://community.alteryx.com/t5/Data-Science-Mixer/bg-p/mixer)
- [Data Skeptic](https://dataskeptic.com/)
- [Data Stories](https://datastori.es/)
- [Datacast](https://jameskle.com/writes/category/Datacast)
- [DataFramed](https://www.datacamp.com/community/podcast)
- [DataTalks.Club](https://anchor.fm/datatalksclub)
- [Gradient Dissent](https://wandb.ai/fully-connected/gradient-dissent)
- [Learning Machines 101](https://www.learningmachines101.com/)
- [Let's Data (Brazil)](https://www.youtube.com/playlist?list=PLn_z5E4dh_Lj5eogejMxfOiNX3nOhmhmM)
- [Linear Digressions](https://lineardigressions.com/)
- [Not So Standard Deviations](https://nssdeviations.com/)
- [O'Reilly Data Show Podcast](https://www.oreilly.com/radar/topics/oreilly-data-show-podcast/)
- [Partially Derivative](https://partiallyderivative.com/)
- [Superdatascience](https://www.superdatascience.com/podcast/)
- [The Data Engineering Show](https://www.dataengineeringshow.com/)
- [The Radical AI Podcast](https://www.radicalai.org/)
- [The Robot Brains Podcast](https://www.therobotbrains.ai/)
- [What's The Point](https://fivethirtyeight.com/tag/whats-the-point/)
- [How AI Built This](https://how-ai-built-this.captivate.fm/)

### YouTube Videos & Channels
**[`^        back to top        ^`](#awesome-data-science)**

- [What is machine learning?](https://www.youtube.com/watch?v=WXHM_i-fgGo)
- [Andrew Ng: Deep Learning, Self-Taught Learning and Unsupervised Feature Learning](https://www.youtube.com/watch?v=n1ViNeWhC24)
- [Data36 - Data Science for Beginners by Tomi Mester](https://www.youtube.com/c/TomiMesterData36comDataScienceForBeginners)
- [Deep Learning: Intelligence from Big Data](https://www.youtube.com/watch?v=czLI3oLDe8M)
- [Interview with Google's AI and Deep Learning 'Godfather' Geoffrey Hinton](https://www.youtube.com/watch?v=1Wp3IIpssEc)
- [Introduction to Deep Learning with Python](https://www.youtube.com/watch?v=S75EdAcXHKk)
- [What is machine learning, and how does it work?](https://www.youtube.com/watch?v=elojMnjn4kk)
- [Data School](https://www.youtube.com/channel/UCnVzApLJE2ljPZSeQylSEyg) - Data Science Education
- [Neural Nets for Newbies by Melanie Warrick (May 2015)](https://www.youtube.com/watch?v=Cu6A96TUy_o)
- [Neural Networks video series by Hugo Larochelle](https://www.youtube.com/playlist?list=PL6Xpj9I5qXYEcOhn7TqghAJ6NAPrNmUBH)
- [Google DeepMind co-founder Shane Legg - Machine Super Intelligence](https://www.youtube.com/watch?v=evNCyRL3DOU)
- [Data Science Primer](https://www.youtube.com/watch?v=cHzvYxBN9Ls&list=PLPqVjP3T4RIRsjaW07zoGzH-Z4dBACpxY)
- [Data Science with Genetic Algorithms](https://www.youtube.com/watch?v=lpD38NxTOnk)
- [Data Science for Beginners](https://www.youtube.com/playlist?list=PL2zq7klxX5ATMsmyRazei7ZXkP1GHt-vs)
- [DataTalks.Club](https://www.youtube.com/channel/UCDvErgK0j5ur3aLgn6U-LqQ)
- [Mildlyoverfitted - Tutorials on intermediate ML/DL topics](https://www.youtube.com/channel/UCYBSjwkGTK06NnDnFsOcR7g)
- [mlops.community - Interviews of industry experts about production ML](https://www.youtube.com/channel/UCYBSjwkGTK06NnDnFsOcR7g)
- [ML Street Talk - Unabashedly technical and non-commercial, so you will hear no annoying pitches.](https://www.youtube.com/c/machinelearningstreettalk)
- [Neural networks by 3Blue1Brown ](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)
- [Neural networks from scratch by Sentdex](https://www.youtube.com/playlist?list=PLQVvvaa0QuDcjD5BAw2DxE6OF2tius3V3)
- [Manning Publications YouTube channel](https://www.youtube.com/c/ManningPublications/featured)
- [Ask Dr Chong: How to Lead in Data Science - Part 1](https://youtu.be/JYuQZii5o58)
- [Ask Dr Chong: How to Lead in Data Science - Part 2](https://youtu.be/SzqIXV-O-ko)
- [Ask Dr Chong: How to Lead in Data Science - Part 3](https://youtu.be/Ogwm7k_smTA)
- [Ask Dr Chong: How to Lead in Data Science - Part 4](https://youtu.be/a9usjdzTxTU)
- [Ask Dr Chong: How to Lead in Data Science - Part 5](https://youtu.be/MYdQq-F3Ws0)
- [Ask Dr Chong: How to Lead in Data Science - Part 6](https://youtu.be/LOOt4OVC3hY)
- [Regression Models: Applying simple Poisson regression](https://www.youtube.com/watch?v=9Hk8K8jhiOo)
- [Deep Learning Architectures](https://www.youtube.com/playlist?list=PLv8Cp2NvcY8DpVcsmOT71kymgMmcr59Mf)

## Socialize
**[`^        back to top        ^`](#awesome-data-science)**

Below are some Social Media links. Connect with other data scientists!

- [Facebook Accounts](#facebook-accounts)
- [Twitter Accounts](#twitter-accounts)
- [Telegram Channels](#telegram-channels)
- [Slack Communities](#slack-communities)
- [GitHub Groups](#github-groups)
- [Data Science Competitions](#data-science-competitions)


### Facebook Accounts
**[`^        back to top        ^`](#awesome-data-science)**

- [Data](https://www.facebook.com/data)
- [Big Data Scientist](https://www.facebook.com/Bigdatascientist)
- [Data Science Day](https://www.facebook.com/datascienceday/)
- [Data Science Academy](https://www.facebook.com/nycdatascience)
- [Facebook Data Science Page](https://www.facebook.com/pages/Data-science/431299473579193?ref=br_rs)
- [Data Science London](https://www.facebook.com/pages/Data-Science-London/226174337471513)
- [Data Science Technology and Corporation](https://www.facebook.com/DataScienceTechnologyCorporation?ref=br_rs)
- [Data Science - Closed Group](https://www.facebook.com/groups/1394010454157077/?ref=br_rs)
- [Center for Data Science](https://www.facebook.com/centerdatasciences?ref=br_rs)
- [Big data hadoop NOSQL Hive Hbase](https://www.facebook.com/groups/bigdatahadoop/)
- [Analytics, Data Mining, Predictive Modeling, Artificial Intelligence](https://www.facebook.com/groups/data.analytics/)
- [Big Data Analytics using R](https://www.facebook.com/groups/434352233255448/)
- [Big Data Analytics with R and Hadoop](https://www.facebook.com/groups/rhadoop/)
- [Big Data Learnings](https://www.facebook.com/groups/bigdatalearnings/)
- [Big Data, Data Science, Data Mining & Statistics](https://www.facebook.com/groups/bigdatastatistics/)
- [BigData/Hadoop Expert](https://www.facebook.com/groups/BigDataExpert/)
- [Data Mining / Machine Learning / AI](https://www.facebook.com/groups/machinelearningforum/)
- [Data Mining/Big Data - Social Network Ana](https://www.facebook.com/groups/dataminingsocialnetworks/)
- [Vademecum of Practical Data Science](https://www.facebook.com/datasciencevademecum)
- [Veri Bilimi Istanbul](https://www.facebook.com/groups/veribilimiistanbul/)
- [The Data Science Blog](https://www.facebook.com/theDataScienceBlog/)


### Twitter Accounts
**[`^        back to top        ^`](#awesome-data-science)**

| Twitter | Description |
| --- | --- |
| [Big Data Combine](https://twitter.com/BigDataCombine) | Rapid-fire, live tryouts for data scientists seeking to monetize their models as trading strategies |
| Big Data Mania | Data Viz Wiz , Data Journalist , Growth Hacker , Author of Data Science for Dummies (2015) |
| [Big Data Science](https://twitter.com/analyticbridge) | Big Data, Data Science, Predictive Modeling, Business Analytics, Hadoop, Decision and Operations Research. |
| Charlie Greenbacker | Director of Data Science at @ExploreAltamira |
| [Chris Said](https://twitter.com/Chris_Said) | Data scientist at Twitter |
| [Clare Corthell](https://twitter.com/clarecorthell) | Dev, Design, Data Science @mattermark #hackerei |
| [DADI Charles-Abner](https://twitter.com/DadiCharles) | #datascientist @Ekimetrics. , #machinelearning #dataviz #DynamicCharts #Hadoop #R #Python #NLP #Bitcoin #dataenthousiast |
| [Data Science Central](https://twitter.com/DataScienceCtrl) | Data Science Central is the industry's single resource for Big Data practitioners. |
| [Data Science London](https://twitter.com/ds_ldn)  | Data Science. Big Data. Data Hacks. Data Junkies. Data Startups. Open Data |
| [Data Science Renee](https://twitter.com/BecomingDataSci) | Documenting my path from SQL Data Analyst pursuing an Engineering Master's Degree to Data Scientist |
| [Data Science Report](https://twitter.com/TedOBrien93) | Mission is to help guide & advance careers in Data Science & Analytics |
| [Data Science Tips](https://twitter.com/datasciencetips) | Tips and Tricks for Data Scientists around the world! #datascience #bigdata |
| [Data Vizzard](https://twitter.com/DataVisualizati) | DataViz, Security, Military |
| [DataScienceX](https://twitter.com/DataScienceX) |  |
| deeplearning4j | |
| [DJ Patil](https://twitter.com/dpatil) | White House Data Chief, VP @ RelateIQ. |
| [Domino Data Lab](https://twitter.com/DominoDataLab) | |
| [Drew Conway](https://twitter.com/drewconway) | Data nerd, hacker, student of conflict. |
| Emilio Ferrara | #Networks, #MachineLearning and #DataScience. I work on #Social Media. Postdoc at @IndianaUniv |
| [Erin Bartolo](https://twitter.com/erinbartolo) | Running with #BigData--enjoying a love/hate relationship with its hype. @iSchoolSU #DataScience Program Mgr. |
| [Greg Reda](https://twitter.com/gjreda)  | Working @ _GrubHub_ about data and pandas |
| [Gregory Piatetsky](https://twitter.com/kdnuggets) |  KDnuggets President, Analytics/Big Data/Data Mining/Data Science expert, KDD & SIGKDD co-founder, was Chief Scientist at 2 startups, part-time philosopher. |
| [Hadley Wickham](https://twitter.com/hadleywickham) |  Chief Scientist at RStudio, and an Adjunct Professor of Statistics at the University of Auckland, Stanford University, and Rice University. |
| [Hakan Kardas](https://twitter.com/hakan_kardes) | Data Scientist |
| [Hilary Mason](https://twitter.com/hmason) | Data Scientist in Residence at @accel. |
| [Jeff Hammerbacher](https://twitter.com/hackingdata)  | ReTweeting about data science |
| [John Myles White](https://twitter.com/johnmyleswhite)  | Scientist at Facebook and Julia developer. Author of Machine Learning for Hackers and Bandit Algorithms for Website Optimization. Tweets reflect my views only. |
| [Juan Miguel Lavista](https://twitter.com/BDataScientist) | Principal Data Scientist @ Microsoft Data Science Team |
| [Julia Evans](https://twitter.com/b0rk) | Hacker - Pandas - Data Analyze |
| [Kenneth Cukier](https://twitter.com/kncukier) | The Economist's Data Editor and co-author of Big Data (http://www.big-data-book.com/). |
| Kevin Davenport | Organizer of https://www.meetup.com/San-Diego-Data-Science-R-Users-Group/ |
| [Kevin Markham](https://twitter.com/justmarkham) | Data science instructor, and founder of [Data School](https://www.dataschool.io/) |
| [Kim Rees](https://twitter.com/krees) | Interactive data visualization and tools. Data flaneur. |
| [Kirk Borne](https://twitter.com/KirkDBorne) | DataScientist, PhD Astrophysicist, Top #BigData Influencer. |
| Linda Regber | Data story teller, visualizations. |
| [Luis Rei](https://twitter.com/lmrei) | PhD Student. Programming, Mobile, Web. Artificial Intelligence, Intelligent Robotics Machine Learning, Data Mining, Natural Language Processing, Data Science. |
| Mark Stevenson | Data Analytics Recruitment Specialist at Salt (@SaltJobs)  Analytics - Insight - Big Data - Datascience |
| [Matt Harrison](https://twitter.com/__mharrison__) | Opinions of full-stack Python guy, author, instructor, currently playing Data Scientist. Occasional fathering, husbanding, organic gardening. |
| [Matthew Russell](https://twitter.com/ptwobrussell) | Mining the Social Web. |
| [Mert Nuhoğlu](https://twitter.com/mertnuhoglu)  | Data Scientist at BizQualify, Developer |
| [Monica Rogati](https://twitter.com/mrogati) | Data @ Jawbone. Turned data into stories & products at LinkedIn. Text mining, applied machine learning, recommender systems. Ex-gamer, ex-machine coder; namer. |
| [Noah Iliinsky](https://twitter.com/noahi) | Visualization & interaction designer. Practical cyclist. Author of vis books: https://www.oreilly.com/pub/au/4419 |
| [Paul Miller](https://twitter.com/PaulMiller) | Cloud Computing/ Big Data/ Open Data Analyst & Consultant. Writer, Speaker & Moderator. Gigaom Research Analyst. |
| [Peter Skomoroch](https://twitter.com/peteskomoroch) | Creating intelligent systems to automate tasks & improve decisions. Entrepreneur, ex Principal Data Scientist @LinkedIn. Machine Learning, ProductRei, Networks |
| [Prash Chan](https://twitter.com/MDMGeek) | Solution Architect @ IBM, Master Data Management, Data Quality & Data Governance Blogger. Data Science, Hadoop, Big Data & Cloud. |
| [Quora Data Science](https://twitter.com/q_datascience)  | Quora's data science topic |
| [R-Bloggers](https://twitter.com/Rbloggers) | Tweet blog posts from the R blogosphere, data science conferences and (!) open jobs for data scientists. |
| [Rand Hindi](https://twitter.com/randhindi) |  |
| [Randy Olson](https://twitter.com/randal_olson) | Computer scientist researching artificial intelligence. Data tinkerer. Community leader for @DataIsBeautiful. #OpenScience advocate. |
| [Recep Erol](https://twitter.com/EROLRecep) | Data Science geek @ UALR |
| [Ryan Orban](https://twitter.com/ryanorban) | Data scientist, genetic origamist, hardware aficionado |
| [Sean J. Taylor](https://twitter.com/seanjtaylor) | Social Scientist. Hacker. Facebook Data Science Team. Keywords: Experiments, Causal Inference, Statistics, Machine Learning, Economics. |
| [Silvia K. Spiva](https://twitter.com/silviakspiva) | #DataScience at Cisco |
| [Harsh B. Gupta](https://twitter.com/harshbg) | Data Scientist at BBVA Compass |
| [Spencer Nelson](https://twitter.com/spenczar_n) | Data nerd |
| [Talha Oz](https://twitter.com/tozCSS) | Enjoys ABM, SNA, DM, ML, NLP, HI, Python, Java. Top percentile kaggler/data scientist |
| [Tasos Skarlatidis](https://twitter.com/anskarl) | Complex Event Processing, Big Data, Artificial Intelligence and Machine Learning. Passionate about programming and open-source. |
| [Terry Timko](https://twitter.com/Terry_Timko) | InfoGov; Bigdata; Data as a Service; Data Science; Open, Social & Business Data Convergence |
| [Tony Baer](https://twitter.com/TonyBaer) | IT analyst with Ovum covering Big Data & data management with some systems engineering thrown in. |
| [Tony Ojeda](https://twitter.com/tonyojeda3) | Data Scientist , Author , Entrepreneur. Co-founder @DataCommunityDC. Founder @DistrictDataLab. #DataScience #BigData #DataDC |
| [Vamshi Ambati](https://twitter.com/vambati) | Data Science @ PayPal. #NLP, #machinelearning; PhD, Carnegie Mellon alumni (Blog: https://allthingsds.wordpress.com ) |
| [Wes McKinney](https://twitter.com/wesmckinn) | Pandas (Python Data Analysis library). |
| [WileyEd](https://twitter.com/WileyEd) | Senior Manager - @Seagate Big Data Analytics @McKinsey Alum #BigData + #Analytics Evangelist #Hadoop, #Cloud, #Digital, & #R Enthusiast |
| [WNYC Data News Team](https://twitter.com/datanews) | The data news crew at @WNYC. Practicing data-driven journalism, making it visual and showing our work. |
| [Alexey Grigorev](https://twitter.com/Al_Grigor) | Data science author |


### Telegram Channels
**[`^        back to top        ^`](#awesome-data-science)**

- [Open Data Science](https://t.me/opendatascience) – First Telegram Data Science channel. Covering all technical and popular staff about anything related to Data Science: AI, Big Data, Machine Learning, Statistics, general Math and the applications of former.
- [Loss function porn](https://t.me/loss_function_porn) — Beautiful posts on DS/ML theme with video or graphic visualization.
- [Machinelearning](https://t.me/ai_machinelearning_big_data) – Daily ML news.


### Slack Communities
[top](#awesome-data-science)

- [DataTalks.Club](https://datatalks.club)
- [Women Who Code - Data Science](https://www.womenwhocode.com/datascience)

### GitHub Groups
- [Berkeley Institute for Data Science](https://github.com/BIDS)

### Data Science Competitions

Some data mining competition platforms

- [Kaggle](https://www.kaggle.com/)
- [DrivenData](https://www.drivendata.org/)
- [Analytics Vidhya](https://datahack.analyticsvidhya.com/)
- [InnoCentive](https://www.innocentive.com/)
- [Microprediction](https://www.microprediction.com/python-1)

## Fun

- [Infographic](#infographics)
- [Datasets](#datasets)
- [Comics](#comics)


### Infographics
**[`^        back to top        ^`](#awesome-data-science)**

| Preview                                                                                                                                                                                                                                     | Description                                                                                                                                                                                                                                                  |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [<img src="https://i.imgur.com/0OoLaa5.png" width="150" />](https://i.imgur.com/0OoLaa5.png)                                                                                                                                                | [Key differences of a data scientist vs. data engineer](https://searchbusinessanalytics.techtarget.com/feature/Key-differences-of-a-data-scientist-vs-data-engineer)                                                                                         |
| [<img src="https://cloud.githubusercontent.com/assets/182906/19517857/604f88d8-960c-11e6-97d6-16c9738cb824.png" width="150" />](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/DataScienceEightSteps_Full.png)                    | A visual guide to Becoming a Data Scientist in 8 Steps by [DataCamp](https://www.datacamp.com) [(img)](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/DataScienceEightSteps_Full.png)                                                              |
| [<img src="https://i.imgur.com/W2t2Roz.png" width="150" />](https://i.imgur.com/FxsL3b8.png)                                                                                                                                                | Mindmap on required skills ([img](https://i.imgur.com/FxsL3b8.png))                                                                                                                                                                                          |
| [<img src="https://i.imgur.com/rb9ruaa.png" width="150" />](https://nirvacana.com/thoughts/wp-content/uploads/2013/07/RoadToDataScientist1.png)                                                                                              | Swami Chandrasekaran made a [Curriculum via Metro map](http://nirvacana.com/thoughts/2013/07/08/becoming-a-data-scientist/).                                                                                                                                            |
| [<img src="https://i.imgur.com/XBgKF2l.png" width="150" />](https://i.imgur.com/4ZBBvb0.png)                                                                                                                                                | by [@kzawadz](https://twitter.com/kzawadz) via [twitter](https://twitter.com/MktngDistillery/status/538671811991715840)                                                                                                                                      |
| [<img src="https://i.imgur.com/l9ZGtal.jpg" width="150" />](https://i.imgur.com/xLY3XZn.jpg)                                                                                                                                                | By [Data Science Central](https://www.datasciencecentral.com/)                                                                                                                                                                                                |
| [<img src="https://i.imgur.com/TWkB4X6.png" width="150" />](https://i.imgur.com/0TydZ4M.png)                                                                                                                                                | Data Science Wars: R vs Python                                                                                                                                                                                                                               |
| [<img src="https://i.imgur.com/gtTlW5I.png" width="150" />](https://i.imgur.com/HnRwlce.png)                                                                                                                                                | How to select statistical or machine learning techniques                                                                                                                                                                                                     |
| [<img src="https://scikit-learn.org/stable/_static/ml_map.png" width="150" />](https://scikit-learn.org/stable/_static/ml_map.png)                                                                                                           | Choosing the Right Estimator                                                                                                                                                                                                                                 |
| [<img src="https://i.imgur.com/3JSyUq1.png" width="150" />](https://i.imgur.com/uEqMwZa.png)                                                                                                                                                | The Data Science Industry: Who Does What                                                                                                                                                                                                                     |
| [<img src="https://i.imgur.com/DQqFwwy.png" width="150" />](https://i.imgur.com/RsHqY84.png)                                                                                                                                                | Data Science ~~Venn~~ Euler Diagram                                                                                                                                                                                                                          |
| [<img src="https://www.springboard.com/blog/wp-content/uploads/2016/03/20160324_springboard_vennDiagram.png" width="150" height="150" />](https://www.springboard.com/blog/wp-content/uploads/2016/03/20160324_springboard_vennDiagram.png) | Different Data Science Skills and Roles from [this article](https://www.springboard.com/blog/data-science-career-paths-different-roles-industry/) by Springboard                                                                                             |
| [<img src="https://data-literacy.geckoboard.com/assets/img/data-fallacies-to-avoid-preview.jpg" width="150" alt="Data Fallacies To Avoid" />](https://data-literacy.geckoboard.com/poster/)                                                 | A simple and friendly way of teaching your non-data scientist/non-statistician colleagues [how to avoid mistakes with data](https://data-literacy.geckoboard.com/poster/). From Geckoboard's [Data Literacy Lessons](https://data-literacy.geckoboard.com/). |

### Datasets
**[`^        back to top        ^`](#awesome-data-science)**

- [Academic Torrents](https://academictorrents.com/)
- [ADS-B Exchange](https://www.adsbexchange.com/data-samples/) - Specific datasets for aircraft and Automatic Dependent Surveillance-Broadcast (ADS-B) sources.
- [hadoopilluminated.com](https://hadoopilluminated.com/hadoop_illuminated/Public_Bigdata_Sets.html)
- [data.gov](https://catalog.data.gov/dataset) - The home of the U.S. Government's open data
- [United States Census Bureau](https://www.census.gov/)
- [usgovxml.com](https://usgovxml.com/)
- [enigma.com](https://enigma.com/) - Navigate the world of public data - Quickly search and analyze billions of public records published by governments, companies and organizations.
- [datahub.io](https://datahub.io/)
- [aws.amazon.com/datasets](https://aws.amazon.com/datasets/)
- [datacite.org](https://datacite.org/)
- [The official portal for European data](https://data.europa.eu/en)
- [NASDAQ:DATA](https://data.nasdaq.com/) - Nasdaq Data Link A premier source for financial, economic and alternative datasets.
- [figshare.com](https://figshare.com/)
- [GeoLite Legacy Downloadable Databases](https://dev.maxmind.com/geoip)
- [Quora's Big Datasets Answer](https://www.quora.com/Where-can-I-find-large-datasets-open-to-the-public)
- [Public Big Data Sets](https://hadoopilluminated.com/hadoop_illuminated/Public_Bigdata_Sets.html)
- [Kaggle Datasets](https://www.kaggle.com/datasets)
- [A Deep Catalog of Human Genetic Variation](https://www.internationalgenome.org/data)
- [A community-curated database of well-known people, places, and things](https://developers.google.com/freebase/)
- [Google Public Data](https://www.google.com/publicdata/directory)
- [World Bank Data](https://data.worldbank.org/)
- [NYC Taxi data](https://chriswhong.github.io/nyctaxi/)
- [Open Data Philly](https://www.opendataphilly.org/) Connecting people with data for Philadelphia
- [grouplens.org](https://grouplens.org/datasets/) Sample movie (with ratings), book and wiki datasets
- [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/ml/) - contains data sets good for machine learning
- [research-quality data sets](https://web.archive.org/web/20150320022752/https://bitly.com/bundles/hmason/1) by [Hilary Mason](https://web.archive.org/web/20150501033715/https://bitly.com/u/hmason/bundles)
- [National Centers for Environmental Information](https://www.ncei.noaa.gov/)
- [ClimateData.us](https://www.climatedata.us/) (related: [U.S. Climate Resilience Toolkit](https://toolkit.climate.gov/))
- [r/datasets](https://www.reddit.com/r/datasets/)
- [MapLight](https://www.maplight.org/data-series) - provides a variety of data free of charge for uses that are freely available to the general public. Click on a data set below to learn more
- [GHDx](https://ghdx.healthdata.org/) - Institute for Health Metrics and Evaluation - a catalog of health and demographic datasets from around the world and including IHME results
- [St. Louis Federal Reserve Economic Data - FRED](https://fred.stlouisfed.org/)
- [New Zealand Institute of Economic Research – Data1850](https://data1850.nz/)
- [Open Data Sources](https://github.com/datasciencemasters/data)
- [UNICEF Data](https://data.unicef.org/)
- [undata](https://data.un.org/)
- [NASA SocioEconomic Data and Applications Center - SEDAC](https://sedac.ciesin.columbia.edu/)
- [The GDELT Project](https://www.gdeltproject.org/)
- [Sweden, Statistics](https://www.scb.se/en/)
- [StackExchange Data Explorer](https://data.stackexchange.com) - an open source tool for running arbitrary queries against public data from the Stack Exchange network.
- [SocialGrep](https://socialgrep.com/datasets) - a collection of open Reddit datasets.
- [San Fransisco Government Open Data](https://datasf.org/opendata/)
- [IBM Asset Dataset](https://developer.ibm.com/exchanges/data/)
- [Open data Index](https://index.okfn.org/)
- [Public Git Archive](https://github.com/src-d/datasets/tree/master/PublicGitArchive)
- [GHTorrent](https://ghtorrent.org/)
- [Microsoft Research Open Data](https://msropendata.com/)
- [Open Government Data Platform India](https://data.gov.in/)
- [Google Dataset Search (beta)](https://datasetsearch.research.google.com/)
- [NAYN.CO Turkish News with categories](https://github.com/naynco/nayn.data)
- [Covid-19](https://github.com/datasets/covid-19)
- [Covid-19 Google](https://github.com/google-research/open-covid-19-data)
- [Enron Email Dataset](https://www.cs.cmu.edu/~./enron/)
- [5000 Images of Clothes](https://github.com/alexeygrigorev/clothing-dataset)

### Comics
**[`^        back to top        ^`](#awesome-data-science)**

- [Comic compilation](https://medium.com/@nikhil_garg/a-compilation-of-comics-explaining-statistics-data-science-and-machine-learning-eeefbae91277)
- [Cartoons](https://www.kdnuggets.com/websites/cartoons.html)

## Other Awesome Lists

- Other amazingly awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness)
- [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning)
- [lists](https://github.com/jnv/lists)
- [awesome-dataviz](https://github.com/javierluraschi/awesome-dataviz)
- [awesome-python](https://github.com/vinta/awesome-python)
- [Data Science IPython Notebooks.](https://github.com/donnemartin/data-science-ipython-notebooks)
- [awesome-r](https://github.com/qinwf/awesome-R)
- [awesome-datasets](https://github.com/awesomedata/awesome-public-datasets)
- [awesome-Machine Learning & Deep Learning Tutorials](https://github.com/ujjwalkarn/Machine-Learning-Tutorials/blob/master/README.md)
- [Awesome Data Science Ideas](https://github.com/JosPolfliet/awesome-ai-usecases)
- [Machine Learning for Software Engineers](https://github.com/ZuzooVn/machine-learning-for-software-engineers)
- [Community Curated Data Science Resources](https://hackr.io/tutorials/learn-data-science)
- [Awesome Machine Learning On Source Code](https://github.com/src-d/awesome-machine-learning-on-source-code)
- [Awesome Community Detection](https://github.com/benedekrozemberczki/awesome-community-detection)
- [Awesome Graph Classification](https://github.com/benedekrozemberczki/awesome-graph-classification)
- [Awesome Decision Tree Papers](https://github.com/benedekrozemberczki/awesome-decision-tree-papers)
- [Awesome Fraud Detection Papers](https://github.com/benedekrozemberczki/awesome-fraud-detection-papers)
- [Awesome Gradient Boosting Papers](https://github.com/benedekrozemberczki/awesome-gradient-boosting-papers)
- [Awesome Computer Vision Models](https://github.com/nerox8664/awesome-computer-vision-models)
- [Awesome Monte Carlo Tree Search](https://github.com/benedekrozemberczki/awesome-monte-carlo-tree-search-papers)
- [Glossary of common statistics and ML terms](https://www.analyticsvidhya.com/glossary-of-common-statistics-and-machine-learning-terms/)
- [100 NLP Papers](https://github.com/mhagiwara/100-nlp-papers)
- [Awesome Game Datasets](https://github.com/leomaurodesenv/game-datasets#readme)
- [Data Science Interviews Questions](https://github.com/alexeygrigorev/data-science-interviews)
- [Awesome Explainable Graph Reasoning](https://github.com/AstraZeneca/awesome-explainable-graph-reasoning)
- [Top Data Science Interview Questions](https://www.interviewbit.com/data-science-interview-questions/)
- [Awesome Drug Synergy, Interaction and Polypharmacy Prediction](https://github.com/AstraZeneca/awesome-drug-pair-scoring)

### Hobby
- [Awesome Music Production](https://github.com/ad-si/awesome-music-production)

<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-YL0RV0E5XZ"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-YL0RV0E5XZ');
</script>
