---
title: CHEOPS Workshop at EuroSys 2022
---

# Workshop on Challenges and Opportunities of Efficient and Performant Storage Systems (CHEOPS)

The second workshop on “Challenges and Opportunities of Efficient and Performant Storage Systems” (CHEOPS) is aimed at researchers, developers of scientific applications, engineers and everyone interested in the evolution of storage systems. As the developments of computing power, storage and network technologies continue to diverge, the bandwidth performance gap between them widens. This trend, combined with the ever growing data volumes and data-driven computing such as machine learning, results in I/O and storage limitations, impacting the scalability and efficiency of current and future computing systems. Some of these challenges are quantitative, such as scale to match exascale system requirements, or latency reduction of the software stack  to efficiently integrate new generations of hardware like storage class memory (SCM). Some other issues are more subtle and arise with the increased complexity of the storage solutions, like new smarter and more potent data management tools, monitoring systems or interoperability between I/O components or data formats.

The main objective of this workshop is to present state-of-the-art research, innovative ideas and experiences that focus on the design and implementation of storage systems in both academic and industrial worlds.

## Important Dates

- Abstract Submission: ~~January 15~~ February 7, 2022 (Anywhere on Earth)
- Paper Submission: ~~January 22~~ February 7, 2022 (Anywhere on Earth)
- Notification to Authors: March 5, 2022
- Camera-Ready Deadline: March 13, 2022
- Workshop Date: April 5, 2022

## Submission Guidelines

In order to guarantee the quality of the submissions, we have formed a globally distributed, diverse program committee. All submissions will be reviewed by the program committee. We will use [HotCRP to manage the submissions](https://cheops22.hotcrp.com/). The reviewing process will be double blind with at least 3 reviews for each submission. An online discussion will determine which papers to accept.

Only original and novel work not currently under review in other venues will be considered for publication. Submissions can either be full papers (6 pages) or short papers (4 pages). The page count includes the title, text, figures, appendices but excludes the references. They must be submitted electronically as PDF files formatted according to the [submission rules of EuroSys](https://2022.eurosys.org/calls/call-for-papers/#submission_instructions). Accepted submissions will have to comply with the EuroSys proceedings format. One author of each accepted paper is required to register for the workshop and present the paper. Extended versions of selected papers will be considered for publication in the ACM SIGOPS Operating Systems Review journal.

Presentations can be given either in-person or via pre-recorded videos. In the latter case, the organizers will collect questions during the presentation and perform a live Q&A session with the presenter, who should be available via video conference.

### Rights Forms

You will find a link to the ACM copyright form on your paper's [HotCRP page](https://cheops22.hotcrp.com/).
Once completed, ACM will send out the information and LaTeX directives (DOI, ISBN etc.) needed to complete the camera-ready version of your paper.

### Camera-Ready Format

You should use the `acmart` document class (<https://www.acm.org/publications/proceedings-template>, the same as for submission), as follows: `\documentclass[sigplan,10pt]{acmart}`

As mentioned above, you will receive the instruction regarding some LaTeX directives (`\setcopyright`, `\acmConference`, `\acmDOI` etc.) after completing the copyright form.

All accepted papers can use up to 2 additional pages for the camera-ready version, for a final limit of 8 (full papers) or 6 (short papers) pages, references not included.

Note that Type 1 fonts (scalable) should be used, not Type 3 (bitmapped), and that all fonts must be embedded.
Type and embedding of fonts can be checked with various tools including `pdffonts`.
Page numbers should be suppressed.
Make also sure that the PDF is searchable by testing the search function in a PDF reader.

### Uploading Final Versions

The camera-ready version of your paper and its LaTeX sources have to be uploaded via [HotCRP](https://cheops22.hotcrp.com/).
As a reminder, the camera-ready deadline for all papers is March 13, 2022.

## Topics of Interest

Submissions may be more hands-on than research papers and we therefore explicitly encourage submissions in the early stages of research. Topics of interest include, but are not limited to:

- Operating system optimizations
- Kernel and user space file/storage systems
  - Including virtual file systems
- Cloud, parallel and distributed file/storage systems
  - Network challenges, such as scalability, QoS and partitionability
- Approaches for low-latency and heterogeneous storage systems
  - Such as SCM and NVRAM combined with HDDs
- Metadata management
- Machine Learning and Artificial Intelligence
  - Storage requirements of ML and AI applications
  - Using ML and AI within storage systems (e.g., to replace heuristics)
- Hybrid solutions using file systems and databases
  - Approaches using query and database interfaces, including key-value stores
  - Optimized indexing techniques
- Data organizations to support online workflows
- Domain-specific data management solutions
  - Application I/O characterization
- Storage systems modeling and analysis tools
- Data reduction techniques
  - Lossless and lossy compression, deduplication
- UI/UX for storage systems
- Related experiences from users: what worked, what didn't?
  - Feedback and empirical evaluation of storage systems

## Agenda (to be finalized)

The workshop will take place in a hybrid format, that is, attendance will be possible in-person in Rennes or via video conferencing and a chat.

| Time        | Content                                                       |
|------------:|:--------------------------------------------------------------|
| 13:40-13:50 | Welcome                                                       |
| 13:50-14:40 | Keynote by **Darrell Long (University of California, Santa Cruz): Lethe: Learning how to forget** ([Abstract](#lethe-learning-how-to-forget-darrell-long)) |
| 14:40-15:00 | **SLRL: A Simple Least Remaining Lifetime File Eviction policy for HPC multi-tier storage systems** by Louis-Marie Nicolas (ENSTA Bretagne), Luis Thomas (ENSTA Bretagne), Yassine Hadjadj-Aoul (Univ. Rennes), Jalil Boukhobza (ENSTA Bretagne) |
| 15:00-15:20 | **Data-Aware Compression for HPC using Machine Learning** by Julius Plehn (Universität Hamburg), Anna Fuchs (Universität Hamburg), Michael Kuhn (Otto von Guericke University Magdeburg), Jakob Lüttgau (University of Tennessee Knoxville), Thomas Ludwig (Deutsches Klimarechenzentrum GmbH) |
| 15:20-15:40 | **TONE: Cutting Tail-Latency in Learned Indexes** by Yong Zhang (McGill University), Xinran Xiong (McGill University), Oana Balmau (McGill University) |
| 15:40-16:00 | **Understanding the Performance of Erasure Codes in Hadoop Distributed File System** by Jad Darrous (Inria, IMT Atlantique, LS2N), Shadi Ibrahim (Inria, Univ. Rennes, CNRS, IRISA) |
| 16:00-16:30 | Coffee break |
| 16:30-16:50 | **Analysis and Workload Characterization of the CERN EOS Storage System** by Devashish R. Purandare (UC Santa Cruz), Daniel Bittman (UC Santa Cruz), Ethan L. Miller (UC Santa Cruz) |
| 16:50-17:10 | Invited Talk by **Houjun Tang (Berkeley Lab, USA): Accelerating HPC Applications with Asynchronous I/O** ([Abstract](#accelerating-hpc-applications-with-asynchronous-io-houjun-tang)) |
| 17:10-17:30 | Invited talk by **Tanzima Islam (Texas State University, USA): Scalability challenges and opportunities for I/O bound applications** ([Abstract](#scalability-challenges-and-opportunities-for-io-bound-applications-tanzima-islam)) |
| 17:30-17:50 | Invited talk by **Jay Lofstead (Sandia National Laboratories, USA): pMEMCPY: Effectively Leveraging Persistent Memory as a Storage Device** ([Abstract](#pmemcpy-effectively-leveraging-persistent-memory-as-a-storage-device-jay-lofstead)) |
| 17:50-18:10 | Invited talk by **Kaoutar El Maghraoui (IBM Research AI, USA): AI Hardware Accelerators and Composable Infrastructure** ([Abstract](#ai-hardware-accelerators-and-composable-infrastructure-kaoutar-el-maghraoui)) |
| 18:10-18:20 | Discussion |
| 18:20-18:30 | Farewell |

### Lethe: Learning how to forget (Darrell Long)

Current data privacy regulations empower people to request that data be deleted without undue delay. Existing storage systems are poorly suited to handle secure deletes and leave traces of deleted data for indeterminate periods. Current approaches to secure deletion, including multiple overwrites and encryption, are also unsatisfactory. Flash media makes the former especially difficult. SSDs typically allocate new blocks for data, providing logical overwrite but not overwriting physical flash pages. In-place overwrites on flash are costly and negatively impact endurance.

Encryption is an alternative to provide secure deletion. Data is securely deleted if the encryption key used to encrypt the data is destroyed. Such systems typically entail at least one key per file for a file system. Key management is problematic when block modifications occur, as any change requires a complete re-encryption of the entire file with a new key. To provide finer granularity, per block encryption keys can be used as well but quickly turn into a more significant key management problem. To address these shortcomings, we propose Lethe, a new system designed to provide efficient key management and secure deletion in file systems, regardless of storage medium, by utilizing keyed hash trees. Using keyed hash trees, Lethe can provide secure deletion at a block-level granularity, only requiring that exactly one key needs to be remembered and able to be securely forgotten.

### Accelerating HPC Applications with Asynchronous I/O (Houjun Tang)

Moving toward exascale computing, the size of data stored and accessed by applications is ever increasing. However, traditional disk-based storage has not seen improvements that keep up with the explosion of data volume or the speed of processors. Asynchronous I/O can reduce the impact of I/O latency as it allows applications to schedule I/O early and to check their status later. I/O is thus overlapped with application computation and communication, effectively hiding some or all of the I/O latency. I will present an asynchronous I/O framework for HDF5 applications that supports all types of I/O operations, manages data dependencies transparently and automatically, provides implicit and explicit modes for application flexibility, and error information retrieval. The evaluation of several benchmarks and application workloads demonstrates its effectiveness in hiding the I/O cost from the application.

### Scalability challenges and opportunities for I/O bound applications (Tanzima Islam)

Scaling a scientific application involves scaling the computation, communication, and the I/O phases of that application. My research identifies inefficiencies and bottlenecks for both the compute and I/O phases of applications at scale, and designs scalable end-to-end systems. Specifically, I am interested about learning the challenges faced by scientific applications that generate and analyze large volume of data. This talk will present a novel data aggregation and compression technique developed for scaling checkpointing —an I/O bound operation—on HPC systems. A similar approach can be leveraged to reduce data movement through network for scaling scientific applications. 

### pMEMCPY: Effectively Leveraging Persistent Memory as a Storage Device (Jay Lofstead)

Persistent memory devices offer a dual use technology that can either extend DRAM capacity by offering lower cost load/store access or as persistent storage devices accessible via the memory bus. As NVMe devices have proven, attaining promised performance for persistent memory devices for storage purposes requires special care. Out of the box library and solutions lack proper tuning leaving at least 50% of the potential performance behind. This talk explores some of the special potential for PMEM devices and shows how to effectively use them for high performance storage.

### AI Hardware Accelerators and Composable Infrastructure (Kaoutar El Maghraoui)

AI and especially deep learning have achieved incredible performances in numerous fields including Computer Vision, Speech Recognition, Natural Language Processing etc. However, with this huge success, comes the increased size and complexity of AI models which both translate into high computational and increased carbon footprint. To address these challenges, there is Cambrian explosion of innovative AI hardware-accelerator architectures optimized for deep learning and machine learning across cloud and edge platforms. Purpose-built hardware will shift the traditional balances between cloud and edge, structured and unstructured data, and training and inference. This talk uncovers the evolving landscape of specialized AI hardware accelerators. It also highlights IBM Research suite of techniques towards the design & build of optimized deep learning hardware as part of IBM’s AI hardware Center initiative. We are making further strides in AI hardware-software co-design using approximate computing principals and Analog non-Von-Neumann approaches to unlock exponential gains of AI computations making AI faster, more efficient, and sustainable. This talk introduces also our composable infrastructure and how we are using it to evaluate various trade-offs among accelerators, networks, storage early in the design cycle, thus avoiding costly errors that can lead to bottlenecks and hinder key applications’ performance.

## Organization

- [Michael Kuhn](https://parcio.ovgu.de/People/Michael+Kuhn.html) - Otto von Guericke University Magdeburg (OVGU), Germany
- [Kira Duwe](https://parcio.ovgu.de/People/Kira+Duwe.html) - Otto von Guericke University Magdeburg (OVGU), Germany
- Jean-Thomas Acquaviva - DDN, France
- Konstantinos Chasapis - DDN, France
- Jalil Boukhobza - National Institute of Advanced Technologies of Brittany (ENSTA Bretagne), France

## Program Committee

- Suren Byna - Lawrence Berkeley National Lab, USA
- Yuan-Hao Chang - Academia Sinica, Taiwan
- Stefano Cozzini - Area Science Park, Italy
- Philippe Deniel - French Alternative Energies and Atomic Energy Commission (CEA), France
- Andreas Dilger - Whamcloud, USA
- Anna Fuchs - Universität Hamburg, Germany
- Shadi Ibrahim - INRIA, France
- Tanzima Islam - Texas State University, USA
- Christos Kozanitis - Foundation for Research and Technology Hellas (FORTH), Greece
- Jay Lofstead - Sandia National Laboratories (SNL), USA
- Sebastian Lührs - Jülich Supercomputing Centre (JSC), Germany
- Jakob Lüttgau - GCLab, USA
- George Markomanolis - IT Center for Science Ltd. (CSC), Finland
- Ramon Nou - Barcelona Supercomputing Center (BSC), Spain
- Anastasios Papagiannis - Isovalent, USA
- Marcus Paradies - DLR, Germany
- Marc-André Vef - Johannes Gutenberg University Mainz, Germany
