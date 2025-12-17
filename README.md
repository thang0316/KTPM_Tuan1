# Bài Tập Kiểm Thử Phần Mềm - DCT122C4

## Giải Phương Trình Trùng Phương
Chương trình giải phương trình: **ax⁴ + bx² + c = 0**

## Hướng dẫn sử dụng

### Biên dịch và chạy
```bash
cd Baitap
g++ -o phuongtrinhtrungphuong.exe phuongtrinhtrungphuong.cpp
./phuongtrinhtrungphuong.exe
```

**Input**: Nhập 3 số a, b, c
```
1 -5 4
```

**Output**: 
```
The equation has 4 real solution(s): 2 -2 1 -1
```

### Test tự động
Mở `test.ipynb` và chạy các cells để test tự động.

## Test Cases

| Test Case | Input | Mô tả | Kết quả mong đợi |
|-----------|-------|-------|------------------|
| 1 | 0 0 0 | Vô số nghiệm | Infinite solutions |
| 2 | 0 0 5 | a=b=0, c≠0 | No solution |
| 3 | 0 1 -4 | a=0, có nghiệm | 2 real solution(s): 2 -2 |
| 4 | 0 1 4 | a=0, vô nghiệm | No solution |
| 5 | 1 0 1 | Delta < 0 | No solution |
| 6 | 1 -2 1 | Delta = 0 | 2 real solution(s): 1 -1 |
| 7 | 1 -5 4 | 4 nghiệm thực | 4 real solution(s) |
| 8 | 1 0 -1 | 2 nghiệm thực | 2 real solution(s): 1 -1 |
