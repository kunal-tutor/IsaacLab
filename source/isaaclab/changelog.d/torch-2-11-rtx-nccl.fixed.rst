* Pinned PyTorch to 2.11 and torchvision to 0.26 with CUDA 12.8 on Linux x86 and Windows,
  retaining CUDA 13.0 on Linux ARM, to avoid RTX collective initialization failures while
  preserving compatibility with existing CUDA 12 graphics drivers.
