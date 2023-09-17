# ebpf的helloworld

使用的操作系统opencloudos，内核版本6.1.11-2302.1.0

下载依赖
``` bash
yum install libbpf-devel make clang llvm elfutils-libelf-devel bpftool bcc-tools bcc-devel
```

运行程序
```
python3 hello.py
```