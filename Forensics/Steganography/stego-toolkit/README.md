# Stego-toolkit
Trong bài hướng dẫn cài bộ [stego-tookit](https://github.com/DominicBreuker/stego-toolkit) người ta hướng dẫn dùng docker container, nhưng mình chỉ chủ yếu dùng lệnh `sudo apt install` hoặc hướng dãn cài mỗi tool từ chính trang web ấy.
# Cài đặt và Demmo từng tool
Trước khi dùng `sudo apt íntall` thì hãy nhớ `sudo apt update` để chắc chắn rằng phiên bản `apt` đang là mới nhất.<br/>
Sau đó thì cài lần lượt từng tool.
Ở đây mình chỉ trình bày cách mình cài trên Máy ảo Kali và Windows10
## stegoVeritas
```
$ sudo -i
$ pip3 install stegoveritas
$ stegoveritas_install_deps
```
![image](https://user-images.githubusercontent.com/88471003/178874711-b37fa702-0768-42ca-aac6-8a680787b507.png)
## zsteg
```
$ gem install zsteg
```
![image](https://user-images.githubusercontent.com/88471003/178878011-342219c9-eaf9-4203-8063-2f0b8a90373b.png)
## stegdetect
Tải [package](http://old-releases.ubuntu.com/ubuntu/pool/universe/s/stegdetect/stegdetect_0.6-6_amd64.deb) này về và dùng lệnh
```
$ sudo dpkg -i stegdetect_0.6-6_amd64.deb
```
![image](https://user-images.githubusercontent.com/88471003/178884181-f1d38ae4-b8e9-4b98-a987-b4467c438ab1.png)
## stegbreak
## AudioStego
```
$ sudo apt-get install libboost-all-dev
$ git clone https://github.com/danielcardeenas/AudioStego.git
$ cd AudioStego
$ mkdir build
$ cd build
$ cmake ..
$ make 
```
Sau đó một file tên `hideme` được tạo ra.<br/>
![image](https://user-images.githubusercontent.com/88471003/178886870-2ca74a88-8107-47b4-bb3b-1b51c1e3c963.png)
## jphide/jpseek
```
$ wget -O /usr/bin/jphide https://github.com/mmayfield1/SSAK/raw/master/programs/64/jphide
$ chmod +x /usr/bin/jphide

$ wget -O /usr/bin/jpseek https://github.com/mmayfield1/SSAK/raw/master/programs/64/jpseek
$ chmod +x /usr/bin/jpseek
```
## jsteg
```
$ wget -O /usr/bin/jsteg https://github.com/lukechampine/jsteg/releases/download/v0.1.0/jsteg-linux-amd64
$ chmod +x /usr/bin/jsteg
```
![image](https://user-images.githubusercontent.com/88471003/178890980-90b2617e-f76d-49e5-a8cd-b89871fdd927.png)
