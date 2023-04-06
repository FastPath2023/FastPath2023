## [Akanksha Jain](https://www.cs.utexas.edu/users/akanksha/)
### software engineer -- Google

<img src="https://pbs.twimg.com/profile_images/1137846223950557184/J0Ur6pHG_400x400.png" width="250">

### Invited Talk:  *Faster Learning on Slow Hardware*

### [Slides]()

### [Video]()

**Abstract:**
Hardware predictors, such as, prefetchers, are critical for single-threaded performance, but further improvements to these prediction mechanisms have become increasingly difficult. In this talk, I will present Voyager, a novel neural network for data prefetching that provides significant prediction benefits over current data prefetchers. For example, for a set of irregular programs from the SPEC 2006 and GAP benchmark suites, Voyager sees an average IPC improvement of 41.6% over a system with no prefetcher, compared with 28.2% for prior art. As another example, for two of Google's warehouse-scale workloads, current data prefetchers see very little benefit, but Voyager dramatically improves both accuracy and coverage. The key to Voyager's superior performance are (1) its ability to learn address correlations, which are important for prefetching irregular sequences of memory accesses, and (2) its novel hierarchical network architecture that is customized to handle the unique constraints and properties of data prefetching.

At present, slow training and prediction preclude neural models from being practically used in hardware, but Voyager’s overheads are significantly lower—in every dimension—than those of previous neural models. Towards the end of the talk, I will discuss our ongoing research in making Voyager---and more generally, neural models---practical for hardware deployment.

**Biography:**
Akanksha Jain is a software engineer at Google, where she works on cross-stack solutions to improve datacenter efficiency. Her research interests are in computer architecture, with a particular focus on the memory system and on using machine learning techniques to improve the design of memory system optimizations.  She received her Ph.D. in Computer Science from The University of Texas.

----
**[FastPath 2023 Program](https://fastpath2023.github.io/FastPath2023/)**
