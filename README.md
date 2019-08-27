# PMACS - Performance Monitoring and Analysis of Cluster Systems
The workshop will take place in conjunction with the [Euro-Par](http://www.europar.org/) conference in Göttingen, Germany, from August 26 to August 27, 2019.

## About this workshop
For a long time, hardware performance monitoring was used on a small scale to measure and analyze data of single application runs in order to detect performance limitations caused by hardware and/or software. Monitoring the whole cluster system for observing hardware failures has been the duty of system administrators with emphasis on operating the system and changes in the system parameters. In recent years, many HPC providers have extended or replaced their monitoring system to additionally track performance data from hardware monitoring facilities and even from the applications. The analysis of the data provides deeper insight in resource utilization and the quality of software. In addition, system administrators use performance data to track the causes of system instabilities to specific user codes. Due to the diversity of HPC centers, many tailored solutions for collection, storage, evaluation and visualization exist today. The workshop wants to bring together developers and users of such infrastructure in order to find ways of collaboration and exchange ideas for further developments.
The workshop covers multiple topics of interests for the Euro-Par conference like support environments, performance evaluation, data management and analytics.

## Call for papers
Performance monitoring and analysis are widely used in data center operations. Depending on particular area of operation it includes tracking activities at hard- and/or software level. HPC centers use system monitoring for ensuring system stability and avoiding resource contention. In recent years, many centers have enhanced their monitoring infrastructure to gather more detailed data from all entities in the system including background services and even user applications. The inherent challenges are diverse: Hardware and software parameters need to be collected with low overhead at all nodes. Gathered metrics need to be transferred to data storage without causing congestion and inference on the network. The whole or just excerpts of the data need to be visualized for further understanding. Furthermore, results of interest and management actions might be derived through data analytics.

Paper contributions for this workshop should address at least one of the following topics:
* Data collection on all entities of a cluster system (compute nodes, management nodes, infrastructure nodes as well as network components)
* Efficient transferring of the gathered metrics to intermediate systems (storage, direct visualization, …)
* Storage of metrics for later use (databases, data management systems, …)
* Visualization of system monitoring metrics
* Derived results and event triggering based on data analytics (machine learning, stream analysis, statistics, event management systems, ...)

The page limit is 12 pages, including all references and appendices, and the formatting must follow the [LNCS](http://2019.euro-par.org/contributors/author-instructions/) guidelines. Please note that papers with less than 10 pages will not be published in the workshop proceedings according to ruling of the Euro-Par workshop organization. At least one author of each accepted paper must present the paper at the workshop (25m talk and 5m for discussion).

There is a blind review process for each submitted paper with at least three reviewers from the programme committee. The review process will use [EasyChair](https://easychair.org/) for organization.

[EasyChair website of the workshop](https://easychair.org/conferences/conference_info.cgi?a=21382832)

## Workshop dates
* ~~Papers submission deadline: May 10, 2019~~
* **UPDATE: Extended paper submission deadline: May 24, 2019**
* Author notification: June 28, 2019
* Registration of at least one author per paper: July 15, 2019
* ~~Workshop dates: August 26-27, 2019~~
* **UPDATE: Workshop date: August 26, 2019**
* Camera-ready paper (including LaTeX sources) deadline: October 7, 2019 

## Workshop agenda

|Time|Title and authors|PDF|
|---|----|---|
|14:00 - 14:45| Keynote by Stephane Eranian (Google LLC, USA)||
|14:45 - 15:15| MPCDF HPC Performance Monitoring System: Enabling Insight via Job-Specific Analysis by Luka Stanisic and Klaus Reuter (Max Planck Computing and Data Facility (MPCDF)) |[PDF](slides/Lua_Stanisic.pdf)|
| 15:15 - 15:30 | Survey with the workshop attendees |[PDF](slides/PMACS-Intro.pdf)|
| 15:30 - 16:00 | Coffee Break||
|16:00 - 16:30| Sparse Grid Regression for Performance Prediction Using High-Dimensional Run Time Data by Philipp Neumann (DKRZ, German Climate Computing Center)|[PDF](slides/Philipp_Neumann.pdf)|
|16:30 - 17:00|Towards a Predictive Energy Model for HPC Runtime Systems Using Supervised Learning by Gence Ozer, Sarthak Garg, Neda Davoudi, Gabrielle Poerwawinata, Matthias Maiterth, Alessio Netti and Daniele Tafani (TU Munich, LRZ Munich, Intel Corp.)|[PDF](slides/Matthias_Maiterth.pdf)|
|17:00 - 17:30|Resource Aware Scheduling for EDARegression Jobs by Saurav Nanda, Ganapathy Parthasarathy, Parivesh Choudhary and Arun Venkatachar (Synopsys Inc.)|

### Paper
Get the papers from [here](https://owncloud.gwdg.de/index.php/s/9WVlVyocQYuTJ9F) (PW:EPGoe2019). You need a seperate password for unpacking the ZIP archive of the PMACS workshop: PMACS_EP2019

## Chairs
### Thomas Gruber
During his apprenticeship at the Erlangen Regional Computing Center [(RRZE)](https://www.rrze.fau.de/), the IT service provider for the Friedrich-Alexander-University Erlangen-Nuernberg [(FAU)](https://www.fau.de/), Thomas Gruber (né Röhl) collected experience with all kinds of clustering approaches. Afterwards, he studied Computer Science at RWTH Aachen University with emphasis on parallel programming and operating system kernel development. At the same time, he worked as a research assistant for the HPC group of the RWTH IT center. After receiving his M. Sc. degree, he went back to RRZE to work for the HPC group. Thomas Gruber leads the development of the performance tool suite [LIKWID](https://github.com/RRZE-HPC/likwid/wiki), which comprises easy-to-use tools for hardware performance monitoring, affinity control and micro-benchmarking. He also works on projects involving monitoring and analysis of hardware performance data.
### Anthony Danalis
The research interests of Anthony Danalis span several topics within the broad domain of performance, ranging from performance measurement and evaluation, to compiler optimization, to novel programming paradigms that enable better utilization of modern hardware. His PhD research focused on compiler optimizations for improving the performance of MPI applications. Later, as a research associate at the Oak Ridge National Lab [(ORNL)](https://www.ornl.gov/) and the University of Tennessee Knoxville [(UTK)](https://www.utk.edu/) he was a founding member of the GPU Benchmark suite [SHOC](https://github.com/vetter/shoc/wiki), the CPU benchmark suite [BlackjackBench](http://www.icl.utk.edu/~luszczek/pubs/Blackjackbench_acmper.pdf), and the task scheduling runtime [PaRSEC](http://icl.utk.edu/parsec/). Currently, Anthony Danalis is a research director with the Innovative Computing Laboratory [(ICL)](https://www.icl.utk.edu/) at the University of Tennessee and his research focuses on various extensions of the Performance Application Programming Interface [(PAPI)](https://icl.utk.edu/papi/index.html), which aim to (a) improve understanding of hardware counters, and (b) extend the notion of performance events to include not only hardware but also software-based information—all through one consistent interface.

## Programme committee
* __Ann Gentile__ (Sandia National Laboratories (SNL), Albuquerque, New Mexico, USA)
* __Michael Klemm__ (Intel, Germany)
* __Sameer Shende__ (Univesity of Oregon, Oregon, USA)
* __Julian Kunkel__ (University of Reading, Great Britain)
* __Heike Jagode__ (University of Tennessee, Tennessee, USA)
* __Zhang Yang__ (Institute of Applied Physics and Computational Mathematics, Beijing, China)
* __Josef Weidendorfer__ (Technische Universität München, Leibniz Rechenzentrum der Bayerischen Akademie der Wissenschaften, Garching, Germany)
* __Robert Dietrich__ (Technische Universität Dresden, Germany)
* __Jack Deslippe__ (National Energy Research Scientific Computing Center, Berkeley, California, USA)
* __Jonas Hahnfeld__ (ITC, RWTH Aachen, Germany)
* __Erich Focht__ (NEC, Germany)
* __Axel Auweter__ (Megware, Germany)
* __Stephane Eranian__ (Google LLC, USA)
* __Dmitry Nikitenko__ (Lomonosov Moscow State University, Russia)

## Contact
If you want to contact us, please write to Thomas _DOT_ Gruber _AT_ fau _DOT_ de
