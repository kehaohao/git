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

	5.vim  文件.vimrc


##git 

	1.git diff ;查看修改

	2.git reset --hard HEAD; 重置到上一个版本的状态

	3.还要注意.gitconfig    

	4.:sh 不关闭vim ，退出操作

	5.Ctrl +d 或 exit   回到vim

	6.在:sh 前加:w 将vim中的内容保存到硬盘

	7.echo $? 测试系统返回值

	8.gcc -S +文件 ： 生成汇编

 
# Install 下载

	1.sudo apt-get install git-core 

	2.sudo apt-get install tig

	3.git clone + 网页 only-read 地址 

	4.git pull 更新网页内容

	查看用 tig 看加入的内容 d



