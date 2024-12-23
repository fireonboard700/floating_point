# Floating-point pipelined multiplier

This paper first looked at the IEEE 754 standard for floating point numbers and the properties that made it convenient to use in processors. We then looked at the floating-point multiplication algorithm and how each of the special cases of multiplication were dealt with. Finally, we looked at the hardware pipelined implementation of the multiplier and the various improvements made at each stage to reduce latency such as the implementation of the Booth modified radix-4 algorithm that generated partial products that were passed through a compression tree constructed out of several rows of carry-save adders. We also looked at the rounding and normalizing algorithms employed to obtain the final product. 
Further research involves looking at the binary fused-multiply add operator, which implements the binary operation A*B + C, and first implemented in the IBM RS/6000[1].

![image](https://github.com/user-attachments/assets/22b63b2f-bfe4-4217-a62e-a19d06b8ecb8)
