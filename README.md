# CodeIgniter_Chinese
## CI框架中文语言包
===================

> CodeIgniter框架(http://codeigniter.org/) 中文语言包(支持CI2和CI3)

#### 安装步骤

1. 进入 CodeIgniter框架/application/language/ 目录;

2. 将本仓库中chinese_s文件夹拷贝至此;(目录结构为: ./application/language/chinese_s/)

3. 然后在`applicaion/config/config.php`文件中找到：

```
    $config['language'] = 'english';
```
改成：
```
    $config['language'] = 'chinese_s';
```
