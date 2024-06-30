# Edge-AI-NYCU-CSIC30166-
Edge AI 邊緣人工智慧 [NYCU CSIC30166]


## Course Description and Goals

In this course, we focus on the concept of efficiency, especially relevant to those on the periphery of the CS field. The ultimate expression of efficiency in the CS domain is being able to achieve tasks with minimal effort, aligning perfectly with the nature of Edge AI. This course is essential for anyone interested in AI who prefers not to engage in extensive parameter tuning and model building.

As AI becomes more prevalent, many AI services will be decentralized, or "edged," relying on edge devices to operate independently without needing to connect to large cloud servers or data centers. This decentralization offers several advantages:
1. High privacy with no concerns about sensitive data leakage.
2. Low to no network dependency, unaffected by bandwidth limitations.
3. Reduced need for cloud servers or data centers.

However, achieving the benefits of Edge AI requires local, non-cloud edge devices to handle everything. These devices often lack large-scale computing power, ample memory resources, and stable power sources, sometimes relying solely on battery power. Therefore, the operation of Edge AI must be highly efficient, meaning the software (AI model) must be compact yet accurate, and the hardware (devices running the AI) must be fast and energy-efficient.

This course explores a series of technologies aimed at realizing Edge AI. Below is the detailed schedule.

### Semester Assignments, Exams, and Evaluations:
- **Lab 0**: Running MobileNet on the cloud (with GPU)
- **Lab 1**: Running MobileNet at the edge (without GPU)
- **Lab 2**: Compressing (pruning/sparsifying) MobileNet
- **Lab 3**: Optimizing Lab 2 with TinyML
- **Lab 4**: Running Vision Transformer at the edge
- **Lab 5**: Quantizing Vision Transformer
- **Lab 6**: Optimizing Lab 5 with FlashAttention
- **Lab 7**: Running Vision Transformer on a cluster of multiple edge devices
- **Lab 8**: Training (fine-tuning) Vision Transformer at the edge

### Lab Assignments

Our lab assignments predominantly deal with the CIFAR dataset and MobileNet optimization. The sequence of activities includes:
1. Running MobileNet on the cloud using PyTorch.
2. Pruning and sparsifying using XNNPACK and graph mode in PyTorch.
3. Compressing and pruning DEIT.
4. Implementing kernel FlashAttention for speed-up.
5. Utilizing four Raspberry Pi devices for PyTorch model parallelism with Triton and PiPy.

Each lab assignment received scores between 90 and 100.
