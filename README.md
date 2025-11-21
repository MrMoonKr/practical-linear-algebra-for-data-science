# 책 부록 소스 프로젝트 입니다

- 직무 교육( OJT, On the job Training )을 위해서 생성.  
- 진행중( WIP, Work on Progress ).  
  + ...


## 책 관련 링크  

<img src="https://www.oreilly.com/covers/urn:orm:book:9781098120603/400w/" alt="" height="256px" align="right">

- [Practical Linear Algebra for Data Science [ 원서 ]](https://www.oreilly.com/library/view/practical-linear-algebra/9781098120603/)  

- [개발자를 위한 실전 선형대수학 [ 번역서 ]](https://www.aladin.co.kr/shop/wproduct.aspx?ItemId=325100604&start=pcsearch_recen)  


## 시스템 환경  

- 시스템 ( Computer System )  

  - AMD Ryzen 9 7900X 12-Core Processor
  - 32G RAM
  - NVIDIA Geforce RTX 3060 12GB
  - SSD 2TB
  - Windows 11 64bit Korean

- 파이썬 ( Python 3.12 )  

  - [Python Download](https://www.python.org/downloads/)  
    - [v3.12.0 for Windows](https://www.python.org/ftp/python/3.12.0/python-3.12.0-amd64.exe)  
    - [v3.11.9 for Windows](https://www.python.org/ftp/python/3.11.9/python-3.11.9-amd64.exe)  

- 파이썬 가상환경 ( venv )

  > 윈도우즈 파워쉘 실행 정책 변경 필요할 수 있음
    ```
    $ Get-ExecutionPolicy
    $ Set-ExecutionPolicy -Scope CurrentUser RemoteSigned
    $ Get-ExecutionPolicy
    ```
  > venv 환경 실행
    ```
    $ python -m venv .venv
    $ .venv/Scripts/Activate.ps1 
    $ (.venv) python --version
    $ (.venv) pip --version
    ```



## 의존 패키지

**다음과 같은 순서로 설치하세요.**
  
```
$ (.venv) pip install ipykernel numpy matplotlib scipy  
$ (.venv) pip install torch torchvision --index-url https://download.pytorch.org/whl/cu128
$ (.venv) pip install lightning
```

**모듈정보**
- numpy
  - [pypi](https://pypi.org/project/numpy/)  
    ```
    $ (.venv) pip install numpy
    ```
  - Fundamental Package for Array Computing in Python

- matplotlib
  - [pypi](https://pypi.org/project/matplotlib/)  
    ```
    $ (.venv) pip install matplotlib
    ```
  - Python Plotting Package

- scipy  
  - [pypi](https://pypi.org/project/scipy/)  
    ```
    $ (.venv) pip install scipy
    ```
  - Fundamental algorithms for scientific computing in Python

- scikit-learn
  - [pypi](https://pypi.org/project/scikit-learn/)  
    ```
    $ (.venv) pip install matplotlib
    ```
  - A set of python modules for machine learning and data mining

- ipykernel
  - [pypi](https://pypi.org/project/ipykernel/)  
    ```
    $ (.venv) pip install ipykernel
    ```
  - [ipykernel](https://github.com/ipython/ipykernel)  
  - IPython Kernel for Jupyter

- PyTorch
  - [pypi](https://pypi.org/project/torch/)  
    ```
    $ (.venv) pip install torch torchvision --index-url https://download.pytorch.org/whl/cu128
    ```
  - [PyTorch](https://pytorch.org/)  
  - Tensors and Dynamic neural networks in Python with strong GPU acceleration
  - nvidia-smi v531.15
  - cuda-toolkit v12.8

- PyTorch Lightning
  - [pypi](https://pypi.org/project/lightning/)  
    ```
    $ (.venv) pip install lightning
    ```
  - [PyTorch Lightning](https://lightning.ai/docs/pytorch/stable/)  
  - The deep learning framework to pretrain, finetune and deploy AI models  
  - PyTorch Lightning is just organized PyTorch - Lightning disentangles PyTorch code to decouple the science from the engineering.
  - ...  

- ...
  - [pypi]()  
    ```
    $ (.venv) pip install ...
    ```
  - [...]()
  - ...  


## 기타

- ...  

- ...  


---
---
---



# LinAlg4DataScience
Code that accompanies the book "Linear Algebra for Data Science"

Check out the table of contents ("_TOC.pdf" file)

Link to the book on amazon:
https://www.amazon.com/Practical-Linear-Algebra-Data-Science/dp/1098120612/

E-version viewable for O'Reilly members:
https://www.oreilly.com/library/view/practical-linear-algebra/9781098120603/


This repository contains all the Python code that accompanies the book. The code probably isn't useful without the book.


### All of the exercises have accompanying YT videos!
The videos provide more explanation and context for the problems, their solutions, and the code. Check it out!
https://www.youtube.com/watch?v=Vpei9S9mFyM&list=PLn0OLiymPak3REyB3XNqqqsRAhZ3LSEH8
