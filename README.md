<div align=center>
 
# KARMA DDoS
 <p>
 <img src="https://img.shields.io/github/stars/HyukIsBack/KARMA-DDoS?color=%23DF0067&style=for-the-badge"/> &nbsp;
 <img src="https://img.shields.io/github/forks/HyukIsBack/KARMA-DDoS?color=%239999FF&style=for-the-badge"/> &nbsp;
 <img src="https://img.shields.io/github/license/HyukIsBack/KARMA-DDoS?color=%23E8E8E8&style=for-the-badge"/> &nbsp;
 
</p>
 Tập lệnh DDoS (Bảng điều khiển DDoS) với Nhiều Bypass<br>( Cloudflare UAM,CAPTCHA,BFM,NOSEC / DDoS Guard / Google Shield / V Shield / Amazon / etc.. )<br/><br/>
 Không tấn công bất kỳ trang web nào mà không phải của bạn<br/>
Công cụ này được tạo ra cho mục đích giáo dục<br/>
 Mọi trách nhiệm và bất lợi của việc sử dụng chương trình này là của người dùng.
 

## Ngôn ngữ</br>

 <img src="https://img.shields.io/badge/Python-FFDD00?style=for-the-badge&logo=python&logoColor=blue"/></br>
</div>

## Menu
![karma](https://user-images.githubusercontent.com/87601386/165147097-7f6f4f6d-f9fd-4a53-b3fa-a16fe739e963.png)

## Phương pháp

```sh
  [Layer 7]
 - cfb     | Bỏ qua cuộc tấn công CF
 - pxcfb   | Vượt qua cuộc tấn công CF với proxy
 - cfreq   | Bỏ qua CF UAM, CAPTCHA, BFM, v.v. với yêu cầu
 - cfsoc   | Bỏ qua CF UAM, CAPTCHA, BFM, v.v. với ổ cắm
 - pxsky   | Bỏ qua Google Project Shield, Vshield, DDoS Guard Free, CF NoSec Với Proxy
 - sky     | Phương pháp Sky không có proxy
 - http2   | Tấn công yêu cầu HTTP 2.0
 - pxhttp2 | Tấn công yêu cầu HTTP 2.0 với Proxy
 - spoof   | Tấn công giả mạo
 - pxspoof | Tấn công giả mạo với Proxy
 - get     | Get  Request Attack
 - post    | Post Request Attack
 - head    | Head Request Attack
 - soc     | Socket Attack
 - pxraw   | Proxy Request Attack
 - pxsoc   | Proxy Socket Attack
 
  [Layer 4]
  -udp     | UDP Attack
  -tcp     | TCP Attack
  
  [Tools]
 - Dns     | Tra cứu DNS cổ điển
 - Geoip   | Tra cứu địa chỉ IP địa lý
 - Subnet  | Tra cứu địa chỉ IP mạng con
```

## Videos
[![](https://user-images.githubusercontent.com/87601386/161339371-b6dfaa8f-1cf2-41d1-85c1-d82cdd98def1.png)](https://www.youtube.com/watch?v=MPKdfhPeLeE)

## Sử dụng trên Linux

- Bạn phải sử dụng Python 3.9 trở lên
```
git clone https://github.com/DauDau432/KARMA-DDoS.git
```
- Cài đặt các mô-đun Python3
```
pip3 install -r requirements.txt  
```
***Hoặc*** 
```
pip install -r requirements.txt
```
- Cài đặt Chrome (hoặc cập nhật phiên bản mới nhất)
```
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
```
```
apt-get install ./google-chrome-stable_current_amd64.deb
```
***Hoặc***
```
 python3 setup.py
```

## Thí dụ
```sh
Sử dụng Bảng điều khiển DDoS   : python3 main.py
Sử dụng dòng lệnh : python3 main.py <method> <target> <thread> <time>
      └──────────> python3 main.py cfb https://example.com 100 30
```
## Nguồn
(https://github.com/HyukIsBack/KARMA-DDoS)[https://github.com/HyukIsBack/KARMA-DDoS]
