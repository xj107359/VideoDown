# 命令行方式运行video_down.py

## 安装python-3.7.3.exe

安装时请勾选"Add Python 3.7 to PATH"

![](https://raw.githubusercontent.com/xj107359/VideoDown/master/Picutres/AddPyToPath.png)

## 安装依赖包

需要安装requests和pyquery，打开cmd

安装requests

	C:\Users\SophoDev>pip install requests
	Collecting requests
	  Downloading https://files.pythonhosted.org/packages/51/bd/23c926cd341ea6b7dd0b2a00aba99ae0f828be89d72b2190f27c11d4b7fb/requests-2.22.0-py2.py3-none-any.whl (57kB)
	    100% |████████████████████████████████| 61kB 236kB/s
	Collecting certifi>=2017.4.17 (from requests)
	  Downloading https://files.pythonhosted.org/packages/60/75/f692a584e85b7eaba0e03827b3d51f45f571c2e793dd731e598828d380aa/certifi-2019.3.9-py2.py3-none-any.whl (158kB)
	    100% |████████████████████████████████| 163kB 17kB/s
	Collecting idna<2.9,>=2.5 (from requests)
	  Downloading https://files.pythonhosted.org/packages/14/2c/cd551d81dbe15200be1cf41cd03869a46fe7226e7450af7a6545bfc474c9/idna-2.8-py2.py3-none-any.whl (58kB)
	    100% |████████████████████████████████| 61kB 63kB/s
	Collecting urllib3!=1.25.0,!=1.25.1,<1.26,>=1.21.1 (from requests)
	  Downloading https://files.pythonhosted.org/packages/e6/60/247f23a7121ae632d62811ba7f273d0e58972d75e58a94d329d51550a47d/urllib3-1.25.3-py2.py3-none-any.whl (150kB)
	    100% |████████████████████████████████| 153kB 18kB/s
	Collecting chardet<3.1.0,>=3.0.2 (from requests)
	  Downloading https://files.pythonhosted.org/packages/bc/a9/01ffebfb562e4274b6487b4bb1ddec7ca55ec7510b22e4c51f14098443b8/chardet-3.0.4-py2.py3-none-any.whl (133kB)
	    100% |████████████████████████████████| 143kB 1.3kB/s
	Installing collected packages: certifi, idna, urllib3, chardet, requests
	Successfully installed certifi-2019.3.9 chardet-3.0.4 idna-2.8 requests-2.22.0 urllib3-1.25.3
	You are using pip version 19.0.3, however version 19.1.1 is available.
	You should consider upgrading via the 'python -m pip install --upgrade pip' command.

安装pyquery

	C:\Users\SophoDev>pip install pyquery
	Collecting pyquery
	  Downloading https://files.pythonhosted.org/packages/09/c7/ce8c9c37ab8ff8337faad3335c088d60bed4a35a4bed33a64f0e64fbcf29/pyquery-1.4.0-py2.py3-none-any.whl
	Collecting lxml>=2.1 (from pyquery)
	  Downloading https://files.pythonhosted.org/packages/5c/da/ca09ea03677a9f7f9c8c7f290990792a5ee340f6c88460dca9333c58124e/lxml-4.3.3-cp37-cp37m-win32.whl (3.2MB)
	    100% |████████████████████████████████| 3.3MB 381kB/s
	Collecting cssselect>0.7.9 (from pyquery)
	  Downloading https://files.pythonhosted.org/packages/7b/44/25b7283e50585f0b4156960691d951b05d061abf4a714078393e51929b30/cssselect-1.0.3-py2.py3-none-any.whl
	Installing collected packages: lxml, cssselect, pyquery
	Successfully installed cssselect-1.0.3 lxml-4.3.3 pyquery-1.4.0
	You are using pip version 19.0.3, however version 19.1.1 is available.
	You should consider upgrading via the 'python -m pip install --upgrade pip' command.

## 运行video_down.py

	C:\Users\SophoDev>d:
	D:\>cd videodown
	D:\videodown>python video_down.py
	正在请求目标网页.... https://jx.618g.com/?url=https://v.qq.com/x/cover/rzuinvatj34ekz7.html
	请求目标网页完成....n 准备解析....
	目标信息正在解析........
	夏目友人帐第六季 第1集
	获取ts文件成功，准备提取信息
	https://youku.com-www-163.com/20180708/18337_a7b6cc4b/1000k/hls/index.m3u8
	解析完成，获取缓存ts文件.........
	获取ts文件成功，准备提取信息
	信息提取完成......n准备下载...
	经计算需要下载357个文件
	正在下载...所需时间较长，请耐心等待..
	当前进度1/357
	...
	下载完成
	ts文件正在进行转录mp4......
	夏目友人帐第六季 第1集
	copy /b "夏目友人帐第六季 第1集\*.ts" "夏目友人帐第六季 第1集.mp4"
	夏目友人帐第六季 第1集\4d23e0cc6f1000.ts
	...
	已复制         1 个文件。
	转换完成，祝你观影愉快
