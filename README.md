### >_ Hỗ trợ
```bash
root@bibo318:$ bash 403-bypass.sh -h
```

### >_ Sử dụng/Modes

- Quét với các trọng tải cụ thể:
  * [ `--header` ] Hỗ trợ bỏ qua / tải trọng dựa trên Phương phápHEADER 
    ```bash
    root@bibo318:$ bash 403-bypass.sh -u https://target.com/secret --header
    ```
  * [ `--protocol` ]  Hỗ trợ bỏ qua / tải trọng dựa trên Phương pháp protocol
    ```bash
    root@bibo318:$ bash 403-bypass.sh -u https://target.com/secret --protocol
    ```
  * [ `--port` ] Hỗ trợ bỏ qua / tải trọng dựa trên Phương pháp PORT
    ```bash
    root@bibo318:$ bash 403-bypass.sh -u https://target.com/secret --port
    ```
  * [ `--HTTPmethod` ] Hỗ trợ bỏ qua / tải trọng dựa trên Phương pháp HTTP
    ```bash
    root@bibo318:$ bash 403-bypass.sh -u https://target.com/secret --HTTPmethod
    ```
  * [ `--encode` ] Hỗ trợ bỏ qua / tải trọng được mã hóa URL
    ```bash
    root@bibo318:$ bash 403-bypass.sh -u https://target.com/secret --encode
    ```
  * [ `--SQLi` ] Hỗ trợ MySQL mod_Security & libinjection bypasses/payloads 
    ```bash
    root@bibo318:$ bash 403-bypass.sh -u https://target.com/secret --SQLi
    ```
- Quét toàn bộ {bao gồm tất cả khai thác / tải trọng} [--exploit]
```bash
root@bibo318:$ bash 403-bypass.sh -u https://target.com/secret --exploit
```

##### Điều kiện cần
- apt install curl [Debian]

