# PMACS - Performance Monitoring and Analysis of Cluster Systems
The workshop will take place in conjunction with the [Euro-Par](https://2020.euro-par.org) conference in Warsaw, Poland, from August 24 to August 28, 2020.

## About this workshop
For a long time, hardware performance monitoring was used on a small scale to measure and analyze data of single application runs in order to detect performance limitations caused by hardware and/or software. Monitoring the whole cluster system for observing hardware failures has been the duty of system administrators with emphasis on operating the system and changes in the system parameters. In recent years, many HPC providers have extended or replaced their monitoring system to additionally track performance data from hardware monitoring facilities and even from the applications. The analysis of the data provides deeper insight in resource utilization and the quality of software. In addition, system administrators use performance data to track the causes of system instabilities to specific user codes. Due to the diversity of HPC centers, many tailored solutions for collection, storage, evaluation and visualization exist today. The workshop wants to bring together developers and users of such infrastructure in order to find ways of collaboration and exchange ideas for further developments.

The workshop covers multiple topics of interests for the Euro-Par conference like support environments, performance evaluation, data management and analytics.

This is the second PMACS workshop in conjunction with the EuroPar conference series. Here is the link to the website from last year: [PMACS 2019](README-2019.md)


## Call for papers
Performance monitoring and analysis are widely used in data center operations. Depending on particular area of operation it includes tracking activities at hard- and/or software level. HPC centers use system monitoring for ensuring system stability and avoiding resource contention. In recent years, many centers have enhanced their monitoring infrastructure to gather more detailed data from all entities in the system including background services and even user applications. The inherent challenges are diverse: Hardware and software parameters need to be collected with low overhead at all nodes. Gathered metrics need to be transferred to data storage without causing congestion and inference on the network. The whole or just excerpts of the data need to be visualized for further understanding. Furthermore, results of interest and management actions might be derived through data analytics.

Paper contributions for this workshop should address at least one of the following topics:
* Data collection on all entities of a cluster system (compute nodes, management nodes, infrastructure nodes as well as network components)
* Efficient transferring of the gathered metrics to intermediate systems (storage, direct visualization, …)
* Storage of metrics for later use (databases, data management systems, …)
* Visualization of system monitoring metrics
* Derived results and event triggering based on data analytics (machine learning, stream analysis, statistics, event management systems, ...)

The page limit is 12 pages, including all references and appendices, and the formatting must follow the LNCS guidelines. Please note that papers with less than 10 pages will not be published in the workshop proceedings according to ruling of the Euro-Par workshop organization. At least one author of each accepted paper must present the paper at the workshop (25m talk and 5m for discussion).

There is a blind review process for each submitted paper with at least three reviewers from the programme committee. The review process will use [EasyChair](https://easychair.org/) for organization.

EasyChair submission page for the PMACS workshop: [https://easychair.org/conferences/?conf=europar2020workshop](https://easychair.org/conferences/?conf=europar2020workshop)



## Workshop dates
* Papers submission deadline: May 8, 2020
* Author notification: June 30, 2020
* Registration of at least one author per paper: July 15, 2020
* Workshop dates: August 24-25, 2020
* Camera-ready paper (including LaTeX sources) deadline: September 11, 2020

## Workshop agenda
**Keynote**: Dr. (Ph.D.) Dmitry Nikitenko, Senior Scientist at the [Research Computing Center of Lomonosov Moscow State University (RCC MSU)](https://rcc.msu.ru/en):<br>
Key professional activities:  Co-leader of the “Top50 ranking of the most powerful supercomputers in Russia” project (since 2004), co-leader of the [Octoshell](http://octoshell.ru/) (HPC Center Support and Management toolkit) Project (since 2010), efficiency of parallel applications and supercomputer application dynamics analysis (initial development of [JobDigest tool](http://russianscdays.org/files/pdf17/185.pdf) based on system monitoring data), managing and administering of the largest in Russia HPC center at MSU (3000+ users, 400 research projects). PI of a number of projects related to resource utilization efficiency. "Supercomputing Frontiers and Innovations" ([http://superfri.org](http://superfri.org)) International Journal Editorial Board Member (since 2015).


The remaining agenda will be published as soon as the number of papers is finalized.


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
