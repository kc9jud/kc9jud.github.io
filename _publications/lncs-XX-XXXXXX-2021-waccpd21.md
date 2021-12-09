---
title: "Accelerating quantum many-body configuration interaction with directives"
collection: publications
# permalink: publications/lncs-XX-XXXXXX-2021-waccpd21
date: 2021-10-21
venue: 'Lecture Notes in Computer Science'
arxiv: 2110.10765
# doi:
# paperurl: 'https://www.patrickfasano.com/files/lncs-XX-XXXXXX-2021-waccpd21_PREPRINT.pdf'
citation: 'B. G. Cook, P. J. Fasano, P. Maris, C. Yang, and D. Oryspayev, arXiv:2110.10765 [cs.DC]'
status: submitted
---
Many-Fermion Dynamics-nuclear, or MFDn, is a configuration interaction (CI) code
for nuclear structure calculations. It is a platform-independent Fortran 90 code
using a hybrid MPI+X programming model. For CPU platforms the application has a
robust and optimized OpenMP implementation for shared memory parallelism. As
part of the NESAP application readiness program for NERSC's latest Perlmutter
system, MFDn has been updated to take advantage of accelerators. The current
mainline GPU port is based on OpenACC. In this work we describe some of the key
challenges of creating an efficient GPU implementation. Additionally, we compare
the support of OpenMP and OpenACC on AMD and NVIDIA GPUs.