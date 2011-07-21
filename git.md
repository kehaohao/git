  #Set up git

	   1.

	      first create a dir

	      mkdir ggg

	   2.

	      now you MUST cd to this dir

	      cd ggg

	   3.

	      initializing this git dir

	      git init

	      now you can see a .git in this dir

	      ls -a

	   4.

	      now create a file

	      vim hello.c



	    5.

	      let git knows about this file

	      git add hello.c

	    6. git commit -m '+留言信息'
	    
	    7.git remote add origin git@github.com:sept/sept-note.git 

	    8.git push -u origin master





#vim 文件内容处理
   
	 1.shift + v


	 2.d 剪切

	 3.p 粘贴

	 4.shift + >

	 5.shift + <

         6.u  返回上一次

 ##vim处理多个文件
	 1.ls;
	 2.bn    回到上次;
	 3.e   +（ 文件名） ;
	 4.wa 保存所有 ;
	 5.bd 关闭buffer缓冲区；

 ###vim中切换格式

	1 .“现在不用保存bn”

	2. set hidden 删除行号
	3. set number

	4. set nonumber ;

	5.vim  文件.vimrc  修改排列次序

#在vim中

若非正常关闭或文件正在打开状态中，则此文件的目录下会多出隐藏文件
（如：note.md.swp）即以.swp格式的隐藏文件
关闭后若还有，可rm -rf 强制删除；


##git 

	1.git diff ;查看修改

	2.git reset --hard HEAD; 重置到上一个版本的状态

        2.2 git reset --hard HEAD^;  在生成文本后回到上一个版本的状态

	3.还要注意.gitconfig    

	4.:sh 不关闭vim ，退出操作

	5.Ctrl +d 或 exit   回到vim

	6.在:sh 前加:w 将vim中的内容保存到硬盘

	7.echo $? 测试系统返回值

	8.gcc -S +文件 ： 生成汇编

        9.git commit -a ; 留言信息

 
# Install 下载

	1.sudo apt-get install git-core 

	2.sudo apt-get install tig

	3.git clone + 网页 only-read 地址 

	4.git pull 更新网页内容

	查看用 tig 看加入的内容 d

#rm  cp 与 mv   如何将h.c 中的内容拷贝到h1.c中

	1. rm .* ；删除垃圾文件

	2.cp  + 文件1/目录  + 文件2/目录；

	3. mv + 文件1/目录  + 文件2/目录； 

       
        4.cat h.c >> h1.c  将h.c 中的内容拷贝到h1.c中；

        5.使用复制

          即 cp 目录名的时候 必须加 -r（cp -r ** **）
 


#软件下载和文件下载 

	1.sudo apt-get install + 软件名；

	2.wget -r + 文件包；
        
        3.wget + 文件名 ；

##tips

	1.clear screen :ctrl + l;

	2.copy and paste : select -> middle button ;

##diff 与 patch 

	1.cp h.c h1.c ; 备份h.c

	2.diff -u h.c h1.c >h1.diff ;得出h.c与h1.c的不同

	3.vim h.diff  

打补丁：

	1.patch h1.c < h1.diff;

	2.patch -R h.c < h.diff ；将h.c 中的diff删除；

#安装插件
  
  unzip snipMate.zip -d ~/.vim；将压缩包解压到根目录下的.vim中
        
   即插件安装成功
  
