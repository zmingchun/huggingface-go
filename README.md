# huggingface-go
huggingface-go : 加速下载 huggingface 的模型和数据集

下载地址：[https://github.com/xieincz/huggingface-go/releases](https://github.com/xieincz/huggingface-go/releases)

使用教程：[huggingface-go : 加速下载huggingface的模型和数据集](https://xieincz.github.io/post/huggingface-go-jia-su-xia-zai-huggingface-de-mo-xing-he-shu-ju-ji/)

# 操作指南
```
wget https://mirror.ghproxy.com/https://github.com/xieincz/huggingface-go/releases/latest/download/huggingface_go_linux_amd64
mv huggingface_go_linux_amd64 huggingface_go
chmod +x huggingface_go

#使用方法： huggingface_go -u huggingface的模型/数据集链接 -f （可选）要保存的位置，可以是文件夹名字也可以是路径 -p （可选）代理链接
#例如：
./huggingface_go -u https://huggingface.co/NousResearch/Llama-2-13b-hf -f /path/to/your/folder -p https://worker-share-proxy-01f5.xieincz.tk/
```
