# 《Metasploit 渗透测试指南》
## 第2章 Metasploit基础

+ 渗透攻击（exploit）
+ 攻击载荷（payload）：渗透攻击之后去执行的代码
+ shellcode：payload中运行的一组机器指令（多为汇编）

### Metasploit用户接口
+ MSF终端
	
    	msfconsole
+ MSF命令行(在kali2.0已经没有了。。）
[Msfcli is no longer available in Metasploit](https://community.rapid7.com/community/metasploit/blog/2015/07/10/msfcli-is-no-longer-available-in-metasploit)

		msfcli
+ Armitage
	
    图形化用户接口
    
    
### Metasploit功能程序
###### （KALI 2.0用msfvennow集成了msfpayload和msfencode）

+ MSF攻击载荷生成器
		
        msfpayload
+ MSF编码器
	
    	msfencode 
+ Nasm Shell

		
