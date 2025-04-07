LỆNH SETUP TERMUX
### Dán cái này lúc mới vào Termux (lưu ý phải cấp quyền truy cập file cho Termux)
- ```
  apt update && apt upgrade -y && apt install proot-distro -y && proot-distro install ubuntu && proot-distro login ubuntu
  ```
### sau khi đã vào root@localhost#:~# 
- ```
  pkg i git
  pkg i npm
  apt update
  apt upgrade -y
  apt-get install -y git curl sudo
  curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
  sudo apt-get install -y nodejs
  ```
### Đối với lần chạy bot tiếp theo
```
proot-distro login ubuntu
```
- Sau đó
  ```
  cd
  ```

   vào file bot của bạn và nhập
  ```
  npm start
  ```
 là được
thay ad và appstate.json
```
nano + tên tệp
```

