# manhcuong888
CNPM
def calculate_S(N):
    S = sum(int(f"{i}{i}") for i in range(1, N + 1))
    return S

print("S(10) =", calculate_S(10))
print("S(11) =", calculate_S(11))
