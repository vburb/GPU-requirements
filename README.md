# GPU-requirements

Excel that has calculations for the GPU requirements for serving a specific LLM model

The Core Formula
To determine the GPU memory required for a given model, you can use the following formula:

formula:

![image](https://github.com/user-attachments/assets/46cfde6b-d906-4169-a072-4c0e3fcc66e8)

M is the GPU memory required in Gigabytes (GB).
P is the number of parameters in the model. For example, a 7B model has 7 billion parameters.
4B represents 4 bytes, which is the typical size of each parameter.
32 is the number of bits in 4 bytes.
Q is the number of bits used for loading the model (e.g., 16 bits, 8 bits, or 4 bits).
1.2 accounts for a 20% overhead due to additional memory usage in GPU, beyond just the parameters.
