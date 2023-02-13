# Deep-Learning-Tutorial
:floppy_disk: 
[Dataset](https://drive.google.com/file/d/12bM74Z-ZJNpJpRoQ8OZmdtF11Shs9dZY/view?usp=sharing)

:blush:
[ดาวน์โหลด WinRAR for Windows](https://www.win-rar.com/fileadmin/winrar-versions/winrar/winrar-x64-611.exe)

## สร้าง Python Virtual Environment
### 1. ติดตั้ง [Python 3.xx](https://www.python.org/ftp/python/3.10.0/python-3.10.0-amd64.exe)
ตรวจสอบเวอร์ชั่นของ Python 
```ruby
python --version
```
### 2. ติดตั้ง [Anaconda](https://repo.anaconda.com/archive/Anaconda3-2022.10-Windows-x86_64.exe)
### 3. พิมพ์ cmd ในช่อง Search (Windows 1x) เลือก Command Prompt:
  3.1 สร้าง Directory โดยใช้คำสั่ง 
  ```ruby
  mkdir [directory]
  ```
  3.2 เข้าสู่ Directory โดยใช้คำสั่ง 
  ```ruby
  cd [directory]
  ```
  3.3 สร้าง Virtual Environment โดยใช้คำสั่ง 
  ```ruby
  python -m venv [virtualname]
  ```
  3.4 Activate Environment  โดยใช้คำสั่ง
  ```ruby
  .\[directory]\Scripts\activate.bat
  ```
  3.5 ติดตั้ง Pip
  ```ruby
  python -m pip install --upgrade pip
  ```
  3.6 ติดตั้ง Jupyter Notebook
  ```ruby
  pip install ipykernel
  ```
  3.7 เพิ่ม Virtual Environment ใน Jupyter Notebook
  ```ruby
  python -m ipykernel install --user --name=[virtualname] 
  ```
  3.8 เริ่มใช้งาน Jupyter Notebook
  ```ruby
  jupyter notebook 
  ```
