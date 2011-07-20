# basics

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

   6.

      create the first version

      git commit -a -m "my first version"

#####
1.shift + v
2.d 
3.p
4.shift + >
5.shift + < 
##vim处理多个文件
1.ls    
2.bn    回到上次
3.e   +（ 文件名）
4.wa 保存所有
5.bd 关闭buffer缓冲区；

###vim中切换格式
1.“现在不用保存bn”
2.set hidden 保存 
3.set number

##gcc
1.gcc -wall +文件

2../a.out 执行

3.echo $: 测试系统返回值

 
