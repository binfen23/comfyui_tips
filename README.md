> GPU：RTX 4060 8G
> 
> CUDA UMD Version: 13.3
> 
> ComfyUI_windows_portable_nvidia.7z
> 
> ComfyUI version: 0.37.0
> 
> Python version: 3.13.14
> 
> Torch 2.13.0+cu130



在 comfyui 的 python_embeded 文件夹 cmd 打开命令行窗口，输入以下：

```CMD
.\python.exe -m pip install "triton-windows==3.7.1.post27"
```

```CMD
 .\python.exe -m pip install "https://github.com/woct0rdho/SageAttention/releases/download/v2.2.0-windows.post6/sageattention-2.2.0%2Bcu130torch2.10.0andhigher.post6-cp310-abi3-win_amd64.whl"
 ```

接着正常安装 ：  

> https://github.com/kijai/ComfyUI-KJNodes

> https://github.com/Saganaki22/ComfyUI-sol-attn


OK，重启comfyui

Patch Sage Attention KJ

Sol-Attn (sparse attention)

这两个节点即可正常使用。

后续可能会因失效而删除  
