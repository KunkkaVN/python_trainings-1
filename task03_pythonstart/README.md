#Mục lục

[1.Pip là gì?](#Pip)

[2.Cài đặt Pip.](#setup)

[3.Khái niệm thông dịch và biên dịch.](#khainiem)

[4.Chương trình "Hello World".](#hello)

<a name="Pip"></a>

#1.Pip là gì?

`Pip` là một trình quản lý gói (**package manager**), thư viện cho `Python`. giống như *Composer* cho `PHP` hay *Bower* cho `Javascript`.
Với `Pip` bạn có thể dễ dang cài đặt các **package** cho `Python` chỉ với 1 dòng lệnh đơn giản: 
    
    pip install <package_name>  

<a name="setup"></a>

#2.Cài đặt Pip.

Sử dụng lệnh:
    
    sudo easy_install pip

![](http://i.imgur.com/SUQ44Z8.png)

<a name="khainiem"></a>

#3.Khái niệm thông dịch và biên dịch.

`Thông dịch` (*interpreter*): dịch từng lệnh 1 thông qua chương trình ta gọi là **trình thông dịch** (*interpreter*). Lần sau chạy lại thì phải trình thông dịch lại file.

`Biên dịch` (*compiler*): dịch toàn bộ thông qua chương trình ta gọi là **trình biên dịch** (*compiler*), dịch 1 lần và sử dụng mãi mãi không cần biên dịch nữa. 

<a name="hello"></a>

#4.Chương trình "Hello World".

**Thông dịch**

![](http://i.imgur.com/zPkBlat.png)

**Biên dịch**

Tạo một file có tên `hello_world.py` chứa nội dung:

    #!/usr/bin/python3
    print("Hello World");
    
Sau đó vào **Terminal** chạy lệnh

    python hello_worrld.py
    
Ta được kết quả:

![](http://i.imgur.com/tpJuH7x.png)




