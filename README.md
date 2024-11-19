
# ⚠️ ERROR

### ❌ Ctrl+Alt+N của Code-Runner không chạy python

### 👉 Thiết lập link executer cho Code-Runner:

1. Tại thanh Extensions thực hiện
   > *Extensions icon > Code Runner > Setting (gear icon)*
2. Tại trang mới thực hiện
   > *Code-runner: Executor Map > Edit in setting json*
3. Tại trang JSON thực hiện chèn link:
   > *"code-runner.executorMap" > "python": > [python.exe link] "C:/Users/TUAN/AppData/.../python.exe"*

# ⬇️ Installation

### Cài đặt gym

1. Kiểm tra đã cài python chưa, mở cmd (run as Administrator) và thực hiện lệnh
```bash
python -V
```

2. Nếu cài python rồi thì kiểm tra đã thêm đường dẫn vào PATH chưa. Search ***PATH*** để tìm ***Edit the system enviroment variables*** và dán vào cả ***User*** và ***System*** hai đường dẫn sau (Phiên bản python khác có thể tên đường dẫn khác)

```bash
C:\Users\TUAN\AppData\Local\Programs\Python\Python311
```
```bash
C:\Users\TUAN\AppData\Local\Programs\Python\Python311\Scripts
```
3. Reboot máy để hiệu lực (có thể thử với không Reboot)

4. Mở cmd (run as Administrator) và thực hiện lệnh:
```bash
python -m pip install gym
```

5. Có thể nâng cấp lệnh ***pip*** bằng lệnh:
```bash
python.exe -m pip install --upgrade pip
```
