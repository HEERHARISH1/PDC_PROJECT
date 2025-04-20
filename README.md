
# PDC_PROJECT


# Parallel Algorithm for Updating SSSP in Dynamic Networks

## 📋 Team Members
- [Heer i222371]
- [M.Fawaz i222340]
- [Fazal I222362] 

## 📄 Research Paper Reference
**Title**: A Parallel Algorithm Template for Updating Single-Source Shortest Paths in Large-Scale Dynamic Networks  
**Authors**: Arindam Khanda, Sriram Srinivasan, Sanjukta Bhowmick, Boyana Norris, Sajal K. Das  
**Published In**: IEEE Transactions on Parallel and Distributed Systems, 2022

## 🧠 Summary of Phase 1 Presentation
This presentation explores a parallel algorithmic framework for efficiently updating Single-Source Shortest Paths (SSSP) in dynamic networks. Instead of recomputing shortest paths from scratch after each network change, the proposed method identifies affected subgraphs and updates them selectively.

Key points:
- Supports both **CPU (OpenMP)** and **GPU (OpenCL)** parallelism.
- Uses **MPI** for distributed execution.
- Employs **METIS** for graph partitioning across MPI processes.
- Introduces **Vertex-Marking Functional Blocks (VMFB)** for GPU efficiency.
- Achieves up to **8.5x GPU** and **5x CPU** speedups over traditional recomputation methods.

## 🛠 Tools and Technologies
- **Languages**: C++, CUDA/OpenCL
- **Libraries**: MPI, OpenMP, METIS
- **Platforms**: Shared-memory multicore systems, NVIDIA GPUs
- **Version Control**: GitHub

## 📌 Next Steps
-  implementation of the proposed algorithm using MPI and OpenMP/OpenCL.
- Evaluate performance on public graph datasets.
- Analyze scalability and document Phase 2 findings.

