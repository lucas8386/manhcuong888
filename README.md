# manhcuong888
CNPM
def calculate_S(N):
    S = sum(int(f"{i}{i}") for i in range(1, N + 1))
    return S

# Test với N = 10 và N = 11
print("S(10) =", calculate_S(10))  # Output: 11 + 22 + ... + 1010
print("S(11) =", calculate_S(11))  # Output: 11 + 22 + ... + 1111
