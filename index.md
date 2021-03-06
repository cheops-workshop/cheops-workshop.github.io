# Workshop on Challenges and Opportunities of Efficient and Performant Storage Systems (CHEOPS)

The first workshop on “Challenges and Opportunities of Efficient and Performant Storage Systems” (CHEOPS) is aimed at researchers, developers of scientific applications, engineers and everyone interested in the evolution of storage systems. As the developments of computing power, storage and network technologies continue to diverge, the bandwidth performance gap between them widens. This trend, combined with the ever growing data volumes and data-driven computing such as machine learning, results in I/O and storage limitations, impacting the scalability and efficiency of current and future computing systems. Some of these challenges are quantitative, such as scale to match Exascale system requirements, or latency reduction of the software stack  to efficiently integrate new generations of hardware like storage class memory (SCM). Some other issues are more subtle and arise with the increased complexity of the storage solutions, like new smarter and more potent data management tools, monitoring systems or interoperability between I/O components or data formats.

The main objective of this workshop is to present state-of-the-art research, innovative ideas and experiences that focus on the design and implementation of storage systems in both academic and industrial worlds.

## Important Dates

- Abstract Submission: February 10, 2021 (Anywhere on Earth)
- Paper Submission: February ~~17~~ 24, 2021 (Anywhere on Earth)
- Notification to Authors: March 22, 2021
- Camera-Ready Deadline: April 2, 2021
- Workshop Date: April 26, 2021

## Submission Guidelines

In order to guarantee the quality of the submissions, we have formed a globally distributed, diverse program committee. All submissions will be reviewed by the program committee. We will use [EasyChair to manage the submissions](https://easychair.org/conferences/?conf=cheops21). The reviewing process will be double blind with at least 3 reviews for each submission. An online discussion will determine which papers to accept.

Only original and novel work not currently under review in other venues will be considered for publication. Submissions can either be full papers (8 pages) or short papers (4 pages). The page count includes the title, text, figures, appendices but excludes the references. They must be submitted electronically as PDF files formatted according to the [submission rules of EuroSys](https://2021.eurosys.org/cfp.html#cfp). Accepted submissions will have to comply with the EuroSys proceedings format. One author of each accepted paper is required to register for the workshop and present the paper. Extended versions of selected papers will be considered for publication in the ACM SIGOPS Operating Systems Review journal.

Since the workshop will take place virtually, attendance will by done via video conferencing and a chat. Attendees can watch the workshop using a video conferencing solution such as Zoom or a video streaming solution such as YouTube. Questions can be asked via a chat system such as Slack. Presentations have to be given either via pre-recorded video or live stream. In both cases, the organizers will collect questions during the workshop and perform a live Q&A session with the presenter. More details will be published closer to the workshop.

### Rights Forms

The corresponding author(s) will be contacted by the ACM to complete a copyright transfer form.
Once completed, ACM will send out the information and LaTeX directives (DOI, ISBN etc.) needed to complete the camera-ready version of your paper.

### Camera-Ready Format

You should use the `acmart` document class (<https://www.acm.org/publications/proceedings-template>, the same as for submission), as follows: `\documentclass[sigplan,10pt]{acmart}`

As mentioned above, you will receive the instruction regarding some LaTeX directives (`\setcopyright`, `\acmConference`, `\acmDOI` etc.) after completing the copyright form.

All accepted papers can use up to 2 additional pages for the camera-ready version, for a final limit of 10 (full papers) or 6 (short papers) pages, references not included.

Note that Type 1 fonts (scalable) should be used, not Type 3 (bitmapped), and that all fonts must be embedded.
Type and embedding of fonts can be checked with various tools including `pdffonts`.
Page numbers should be suppressed.
Make also sure that the PDF is searchable by testing the search function in a PDF reader.

### Uploading Final Versions

The camera-ready version of your paper and its LaTeX sources have to be uploaded via [EasyChair](https://easychair.org/conferences/?conf=cheops21).
As a reminder, the camera-ready deadline for all papers is April 2, 2021.

## Topics of Interest

Submissions may be more hands-on than research papers and we therefore explicitly encourage submissions in the early stages of research. Topics of interest include, but are not limited to:

- Operating system optimizations
- Kernel and user space file/storage systems
  - Including virtual file systems
- Cloud, parallel and distributed file/storage systems
  - Network challenges, such as scalability, QoS and partitionability
- Approaches for low-latency and heterogeneous storage systems
- Non-volatile memory technology and integration
- Metadata management
- Machine Learning and AI
  - Storage requirements of ML and AI applications
  - Using ML and AI within storage systems (e.g., to replace heuristics)
- Hybrid solutions using file systems and databases
  - Approaches using query and database interfaces
  - Optimized indexing techniques
- Data organizations to support online workflows
- Domain-specific data management solutions
  - Application I/O characterization
- Storage systems modeling and analysis tools
- Data reduction techniques such as compression and deduplication
- Security approaches for storage systems
  - Encryption on different levels of the storage stack
- UI/UX for storage systems
- Related experiences from users: what worked, what didn't?
  - Feedback and empirical evaluation of storage systems

## Agenda

Please note that the workshop is following British Summer Time, that is, UTC+1.
The proceedings are available in the [ACM Digital Library](https://dl.acm.org/citation.cfm?id=3439839).

| Time        | Content                                                       |
|------------:|:--------------------------------------------------------------|
|   8:00-8:05 | Welcome                                                       |
|   8:05-8:50 | Keynote by **Suren Byna (Lawrence Berkeley National Lab, USA): Parallel I/O at Exascale with HDF5 and Proactive Data Containers** |
|   8:50-9:20 | **A Unified Storage Layer for Supporting Distributed Workflows in Kubernetes** -- Antony Chazapis (Foundation for Research and Technology - Hellas), Christian Pinto (IBM Research Europe), Yiannis Gkoufas (IBM Research Europe), Christos Kozanitis (Foundation for Research and Technology - Hellas), Angelos Bilas (Foundation for Research and Technology - Hellas) |
|   9:20-9:50 | **Predicting file lifetimes for data placement in multi-tiered storage systems for HPC** -- Luis Thomas (ENSTA Bretagne / Lab-STICC), Sebastien Gougeaud (CEA), Stéphane Rubini (Univ. Brest / Lab-STICC), Philippe Deniel (CEA), Jalil Boukhobza (ENSTA Bretagne / Lab-STICC) |
|  9:50-10:15 | Break                                                         |
| 10:15-10:35 | **Using Ceph's BlueStore as Object Storage in HPC Storage Framework** -- Kira Duwe (Otto von Guericke University Magdeburg), Michael Kuhn (Otto von Guericke University Magdeburg) |
| 10:35-10:55 | **Design for Computational Storage Simulation Platform** -- Peter Wilcox (University of California, Santa Cruz), Heiner Litz (University of California, Santa Cruz) |
| 10:55-11:25 | **EZIOTracer: Unifying Kernel, User Space I/O Tracing for Data-Intensive Applications** -- Mohammed Islam Naas (University of Western Brittany), François Trahay (Telecom SudParis, Polytechnic Institute of Paris), Alexis Colin (Telecom SudParis, Polytechnic Institute of Paris), Pierre Olivier (The University of Manchester), Stéphane Rubini (The University of Manchester), Frank Singhoff (The University of Manchester), Jalil Boukhobza (ENSTA Bretagne / Lab-STICC) |
| 11:25-11:55 | **Evaluation of Flash Storage Integration (SIONlib with IME)** -- Konstantinos Chasapis (DataDirect Networks Storage), Jean-Thomas Acquaviva (DataDirect Networks Storage), Sebastian Lührs (Jülich Supercomputing Centre) |
| 11:55-12:00 | Farewell |

## Organization

- [Michael Kuhn](https://parcio.ovgu.de/People/Michael+Kuhn.html) - Otto von Guericke University Magdeburg (OVGU), Germany
- [Kira Duwe](https://parcio.ovgu.de/People/Kira+Duwe.html) - Otto von Guericke University Magdeburg (OVGU), Germany
- Jean-Thomas Acquaviva - DDN, France
- Konstantinos Chasapis - DDN, France
- Jalil Boukhobza - National Institute of Advanced Technologies of Brittany (ENSTA Bretagne), France

## Program Committee

- Marco Aldinucci - University of Turin, Italy
- Julien Bigot - French Alternative Energies and Atomic Energy Commission (CEA), France
- Philippe Deniel - French Alternative Energies and Atomic Energy Commission (CEA), France
- Andreas Dilger - Whamcloud, USA
- Leonardo Bautista Gomez - Barcelona Supercomputing Center (BSC), Spain
- Christos Kozanitis - Foundation for Research and Technology Hellas (FORTH), Greece
- Julian Kunkel - University of Reading, UK
- Jay Lofstead - Sandia National Laboratories (SNL), USA
- Johann Lombardi - Intel, France
- Sebastian Lührs - Jülich Supercomputing Centre (JSC), Germany
- Jakob Lüttgau - German Climate Computing Center (DKRZ), Germany
- George Markomanolis - IT Center for Science Ltd. (CSC), Finland
- Ramon Nou - Barcelona Supercomputing Center (BSC), Spain
- Anastasios Papagiannis - Facebook, UK
