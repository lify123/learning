此仓库只是为了学习git操作，进行本地与远程的互传


1：使用git push实现本地上传文件“hit.txt”到github
问题：出现SSL certificate problem: unable to get local issuer certificate

解决：安全密钥连接不上，可能是使用了steam++加速器，关闭后即可顺利连接；
    但是有时关闭后仍会报错Failed to connect to github.com port 443 after 21071 ms: Could not connect to server
    应该是网络不稳定或者DNS解析问题，尝试修改了网络DNS为公共DNS服务器（不知道是哪个方法最终成功的）
      
