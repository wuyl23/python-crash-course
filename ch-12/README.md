# 第12章 武装飞船


**pip 安装**

	https://pip.pypa.io/en/stable/installing/
	
**pygame 安装**

	pip install pygame
	
	
**Docker运行**

`XQuartz`

	ip=192.168.0.11
	xhost +
	docker run -e DISPLAY=$ip:0 -v /tmp/.X11-unix:/tmp/.X11-unix -v code:/usr/src/app