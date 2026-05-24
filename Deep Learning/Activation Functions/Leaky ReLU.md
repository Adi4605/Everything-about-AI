- Introduced to solve [[Dying ReLU Problem]]
- Allows a small non-zero output for negative values instead of making them completely zero
- Better gradient flow
- Computationally efficient
- Can outperform ReLU in some networks
- Fixed negative slope
- Not fully zero-centered
- Helps prevent dying neurons

Formula:
![[Pasted image 20260524184125.png]]
where:
- x = input
- a = small constant (Typically a=0.01)

![[Pasted image 20260524184252.png|404]]
