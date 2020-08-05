

### git     
>git commit -m        
- -m 后面，可以不写引号直接加描述     
- 加引号的话，必须是双引号，单引号不行     

<br />

>中文乱码         
- VScode 输入：      
    + git config --global core.quotepath false         

- 其他 Windows cmd 编辑器       
    + 进入setting            
	+ 找到 environment       
	+ 添加：set LANG=zh_CN.UTF-8           
     
- 不懂中文的病治好了       


## 上传至远程仓库  


### GitHub 
- 网址: https://github.com/          
- 太慢... 整个VPN后，没问题了     

- 创建完 repository 后，分别需要执行：        
    + 先生成密钥         

```bash
ssh-keygen -t rsa -C "123@163.com"
```
- 在 github 上添加公钥          
    + 个人中心 -> 设置 -> ssh -> 添加            

+ git remote add origin git@github.com:hotpointchina/GitStady.git           
+ git push -u origin master           


<br /><br /><hr /><br /><br />




- gitee : https://gitee.com/           
    - 码云 - 国内速度快       


<br /><br /><hr /><br /><br />


- https://coding.net/      