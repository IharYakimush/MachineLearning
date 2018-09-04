# MachineLearning
Getting started with machine learning

# install environment
1. Install Python tools in visual studio installer. Go to `C:\ProgramData\Microsoft\VisualStudio\Packages\CPython3.Exe.x64,version=3.6.6,chip=x64\python-3.6.6-amd64.exe` run installer and modify installation by setting python to PATH

2. Open https://github.com/Microsoft/vs-tools-for-ai/blob/master/docs/quickstart-02-project-from-template.md and follow steps to install NVIDIA GPU driver, CUDA and cuDNN 
-   To install CUDA
    Visit this site, download CUDA and install it.
    Make sure to install the CUDA runtime libraries, and then add CUDA binary path to the %PATH% or $PATH environment variable.
    On Windows, this path is "C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v9.0\bin" by default.
    
-   To install cuDNN
    Visit here to download and install v7.0.5 for CUDA 9.0 package.
    Ensure to add the directory containing cuDNN binary to the %PATH% or $PATH environment variable.
    On Windows, you can copy cudnn64_7.dll to "C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v9.0\bin".

3. Use installer instructions from https://github.com/Microsoft/samples-for-ai/#using-a-one-click-installer-to-setup-deep-learning-frameworks
```
git clone https://github.com/Microsoft/samples-for-ai.git
cd samples-for-ai
cd installer
- Windows:
    python.exe install.py
- Non-Windows:
    python3 install.py
```

4. ipython notebook
