# tar -xjvf x11vnc-0.9.13.tar.gz

# cd x11vnc-0.9.13

# mkdir -p _INSTALL

# ./configure --host=arm-linux --without-x --prefix=./_INSTALL/  CC=arm-linux-gnueabihf-gcc CFLAGS=-O2 

# make

# make install


��Ŀ������ֵ�ŵ�   _INSTALL/  �ļ������棬����ʹ�÷������£�

_INSTALL/bin/x11vnc -noipv6 -rawfb /dev/fb0 -pipeinput UINPUT:touch,tslib_cal=/etc/pointercal,direct_abs=/dev/input/event0,nouinput,dragskip=4 -clip 1280x800

���У�/dev/fb0 ��ӦΪLCD��Ļ�豸
tslib_cal=/etc/pointercal,��Ӧtslib����У׼���ɵ��ļ�
direct_abs=/dev/input/event0 ��Ӧ��������event
-clip 1280x800 ������Ļ�ֱ���

���н����
Ĭ�ϻ���5900�˿�������VNC�ӿڣ�ʹ��VNC Viewer֮��Ĺ��ߣ��������IP��5900���ɹۿ�������˳����ӣ�������ϵ�VNC ServerҲ���˳����ٴ��迪����

