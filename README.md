此仓库只是为了学习git操作，进行本地与远程的互传


1：使用git push实现本地上传文件“hit.txt”到github

问题：出现SSL certificate problem: unable to get local issuer certificate

解决：安全密钥连接不上，可能是使用了steam++加速器，使用了网络代理，代理服务器可能会修改或拦截 SSL/TLS 连接，导致证书验证失败。关闭后即可顺利连接；
    但是关闭后报错Failed to connect to github.com port 443 after 21071 ms: Could not connect to server
    应该不加速后网络不稳定或者DNS解析问题，尝试修改了网络DNS为github的DNS服务器。最终解决可能是DNS配置合适，也有可能是网络质量在某次尝试时好了（不稳定）
      
