The repository is moved to https://github.com/HipaccVX/HipaccVX

# HipaccVX

An OpenVX implementation that achieves high performance for a wide variety of target platforms, namely GPUs, CPUs, and FPGAs.

**Abstract**   
Writing programs for heterogeneous platforms optimized for high performance is hard since this requires the code to be tuned at a low level with architecture-specific optimizations that are most times based on fundamentally differing programming paradigms and languages. OpenVX promises to solve this issue for computer vision applications with a royalty-free industry standard that is based on a graph-execution model. Yet, the OpenVX ’ algorithm space is constrained to a small set of vision functions. This hinders accelerating computations that are not included in the standard.  

In this paper, we analyze OpenVX vision functions to find an orthogonal set of computational abstractions. Based on these abstractions, we couple an existing domain-specific language (DSL) back end to the OpenVX environment and provide language constructs to the programmer for the definition of user-defined nodes. In this way, we enable optimizations that are not possible to detect with OpenVX graph implementations using the standard computer vision functions. These optimizations can double the throughput on an Nvidia GTX GPU and decrease the resource usage of a Xilinx Zynq FPGA by 50% for our benchmarks. Finally, we show that our proposed compiler framework, called HipaccVX, can achieve better results than the state-of-the-art approaches Nvidia VisionWorks and Halide-HLS.

## Publication

Özkan, M.A., Ok, B., Qiao, B., Teich, J., & Hannig, F. (2020). HipaccVX: Wedding of OpenVX and DSL-based Code Generation. Journal of Real-Time Image Processing, 18 (2021): 765–777. https://dx.doi.org/10.1007/s11554-020-01015-5

**(Springer) Open Access Link:** https://rdcu.be/cl8KK  
**Arxiv:** https://arxiv.org/pdf/2008.11476.pdf

**Bibtex:**  
@article{
 author = {Özkan, Mehmet Akif and Ok, Burak and Qiao, Bo and Teich, Jürgen and Hannig, Frank},  
 doi = {10.1007/s11554-020-01015-5},  
 journal = {Journal of Real-Time Image Processing},  
 pages = {765 - 777},  
 title = {{HipaccVX}: {Wedding} of {OpenVX} and {DSL}-based {Code} {Generation}},  
 url = {http://link.springer.com/article/10.1007/s11554-020-01015-5},  
 volume = {18},  
 year = {2021}  
}
