# Incremental SVM
  - http://cbcl.mit.edu/cbcl/publications/ps/cauwenberghs-nips00.pdf: Based on maintaining the KKT condition. The
  largest implementation here seems to be 10K data points.
  
# LSH & ML

There has been efforts that try to use LSH to speed up SVM or deep learning models. Most of them are related to active learning.

  - https://www.robots.ox.ac.uk/~vgg/rg/papers/jain_etal_NIPS10.pdf
  - http://www.ifp.illinois.edu/~qi4/papers/2011_CVPR_LSSVM-gjqi.pdf
  - http://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Mu_Hash-SVM_Scalable_Kernel_2014_CVPR_paper.pdf
  - https://www.robots.ox.ac.uk/~vgg/rg/slides/karen_Hash-Based-SVM-Approximation.pdf
  - http://arxiv.org/pdf/1411.4199.pdf
  - http://www.cs.utexas.edu/~grauman/papers/iccv2009_klsh.pdf

# Importance sampling & SGD

We will end up doing importance sampling for other loss I guess. In this case, you do not uniformly sample SGD, instead, has some prior distribution.

  - https://arxiv.org/abs/1401.2753

# Concept Drift

  - https://arxiv.org/pdf/1504.01044.pdf
  - https://arxiv.org/pdf/1010.4784.pdf
  - http://www.win.tue.nl/~mpechen/publications/pubs/Gama_ACMCS_AdaptationCD_accepted.pdf
