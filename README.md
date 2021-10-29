# HACKTHEBOX
## RE
### Bài 1: 
[baby_ransom.zip](https://github.com/Peteraad/HACKTHEBOX/files/7438103/baby_ransom.zip)

#### ***Cách giải:***
Bước 1: Tải file về, dùng phần mềm IDA để decompile ta thấy được flag =3
>**HTB{n0t_s0_h1dd3n_p4ssw0rd}**
>![image](https://user-images.githubusercontent.com/90112096/139355349-c065dfc2-5f6d-4a71-b962-426a0b4b688e.png)

### Bài 2:
[gate.zip](https://github.com/Peteraad/HACKTHEBOX/files/7438110/gate.zip)

#### ***Cách giải:***
Bước 1: Tải file về, dùng phần mềm IDA để decompile. Ta thấy có gì bất thường trong doạn code 
>![image](https://user-images.githubusercontent.com/90112096/139355546-d4471be9-e763-4b29-ada5-b49c24a75e42.png)

Bước 2: Ta thử kiểm tra dưới dạng Hex View và như dự đoán ta tìm được flag trong này
>**HTB{s3cr3t_p455w0rd_1n_str1ngs}**
>![image](https://user-images.githubusercontent.com/90112096/139355624-b95029f2-0573-47c3-9cea-2bad7f44bb5a.png)
