# gvim
step:<br>
* 1.在vim for windows安装包中安装vim74<br>
* 2.在安装后的vim74文件夹中的vim74目录中放入ctags.exe和cscope.exe<br>
* 3.将vim for windows配置文件文件夹中的所有文件拷贝到安装vim的根目录下面<br>
* 4.配置windows的path环境变量(右击计算机->打开系统设置(->高级)->环境变量->系统变量->新建(变量名:path,变量值:vim74文件的路径))<br>
* 5.将vim for windows(c/c++补全)中的WTHtags放到安装vim74的vimfiles目录下<br>
* 6.用vim 打开安装vim74根目录下的_vimrc,在末尾加入(set tags+=WTHtags的路径)"如: set tags+=f:\vim\vimfiles\WTHtags"<br>
* 7.打开vim后就可以实现c/c++补全(如要实现其他语言的补全或者项目中各个头文件的补全"则需要到包含该语言的头文件目录下或者该项目的根目录下执行catgs语句生成相应的tags")
