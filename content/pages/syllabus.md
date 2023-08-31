---
content_type: page
description: This syllabus provides information on location, prerequisites, grading,
  algorithmic challenges, and references.
learning_resource_types: []
ocw_type: CourseSection
title: Syllabus
uid: bf58d94b-f76e-95f6-9ee9-1c206feb10e1
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

Course Meeting Times
--------------------

Lectures: 1 session / week, 1.5 hours / session

Location
--------

Lectures will be held weekly for 1.5 hours each session. This term, 6.096 is being taught in conjunction with 6.046J. Students are encouraged to enroll in both courses simultaneously and learn both the foundations of algorithms, together with Computational Biology. In addition, tutorials and office hours will be held weekly.

Prerequisites
-------------

6.001 (Structure and Interpretation of Computer Programs), 7.01

Grading
-------

Grading will be calculated based on the following formula:

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
activities
{{< thclose >}}
{{< thopen >}}
percentages
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
Four Problem Sets
{{< tdclose >}}
{{< tdopen >}}
60%
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Final Exam
{{< tdclose >}}
{{< tdopen >}}
30%
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Attendance
{{< tdclose >}}
{{< tdopen >}}
10%
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Algorithmic Challenges
----------------------

The field of computational biology is rich in algorithmic challenges, stemming from the sheer size of massive datasets, and also the noisy nature of biological signals. For example, the human genome contains 3 billion letters, 25 thousand genes, and several thousand regulatory signals governing the gene usage. The genes themselves interact in complex ways, forming dense regulatory networks, shaped by relentless evolutionary forces.

In this course, we will address several algorithmic challenges in computational biology. We will study the principles of algorithmic design for biological datasets, analyze existing algorithms, and apply these to real datasets. The lectures will cover:

### Challenge Number 1: Assembly of Complete Genomes from Short Reads

Genomes are several billion letters long, and yet sequencing technologies only read a few hundred nucleotides at a time. Assembling the pieces into a complete genome is especially challenging, given the highly repetitive nature of the human genome, and the error-prone nature of sequencing reads.

### Challenge Number 2: Gene Identification in Vast Genomic Regions

The cell recognizes several biological signals guiding the processes of transcription, splicing, and translation. We will see how to map these signals onto the genome, and recognize complete gene structures in presence of vast non-coding regions.

### Challenge Number 3: Regulatory Motif Discovery

In response to environmental changes, the cell reads a complex code of regulatory signals which dictate gene usage. These sequence patterns are extremely short (10 nucleotides), often degenerate, and occur at varying distances from the gene start. We will develop algorithms for detecting these elements amidst oceans of non-functional nucleotides.

### Challenge Number 4: Genome Alignment and Comparison

The forces of natural selection and random mutation have shaped genome evolution and the modern species. Comparison of related genomes can yield insights into their evolutionary constraints, and reveal the functional elements within them. We will study algorithms for sequence alignment, both at the nucleotide level, and at the genome level.

### Challenge Number 5: Reconstruction of Regulatory Networks

The genes of a species rarely act in isolation. Complex regulatory networks govern their usage, and complex interaction networks govern their cooperation patterns. We will study algorithms to infer modules of cooperating genes, reconstruct regulatory networks, and study their emerging properties.

### Challenge Number 6: Inference of Evolutionary Mechanisms

Perhaps the most intriguing aspect of biological systems is their ability to evolve. We will study algorithms for inferring evolutionary events, understanding the ancestry of species, and their evolutionary relationships.

References
----------

References will be taken from:

Gusfield, Dan. _Algorithms on Strings, Trees and Sequences: Computer Science and Computational Biology_. Cambridge, UK: Cambridge University Press, 1997. ISBN: 0521585198.

Waterman, Michael. _Introduction to Computational Biology: Maps, Sequences, and Genomes_. Boca Raton, FL: CRC Press, 1995. ISBN: 0412993910.

Durbin, Richard, Graeme Mitchison, S. Eddy, A. Krogh, and G. Mitchison. _Biological Sequence Analysis: Probabilistic Models of Proteins and Nucleic Acids_. Cambridge, UK: Cambridge University Press, 1997. ISBN: 0521629713.

[![Buy at MIT Press](/images/mp_logo.gif)](https://mitpress.mit.edu/books/introduction-bioinformatics-algorithms) Jones, Neil, and Pavel Pevzner. [_An Introduction to Bioinformatics Algorithms_](https://mitpress.mit.edu/books/introduction-bioinformatics-algorithms). Cambridge, MA: [MIT Press](https://mitpress.mit.edu/books/introduction-bioinformatics-algorithms) , 2004. ISBN: 0262101068.