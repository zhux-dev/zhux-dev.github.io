# 博客搭建教程

博客模板引用来源：[qiubaiying](https://github.com/qiubaiying/qiubaiying.github.io/wiki/%E5%8D%9A%E5%AE%A2%E6%90%AD%E5%BB%BA%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B)

## 本地开发环境

- 安装 chruby 和 ruby-install
```shell
brew install chruby ruby-install
```

- 安装 Ruby
```shell
ruby-install ruby 3.4.1
```

- 配置 chruby
```shell
echo "source $(brew --prefix)/opt/chruby/share/chruby/chruby.sh" >> ~/.zprofile
echo "source $(brew --prefix)/opt/chruby/share/chruby/auto.sh" >> ~/.zprofile
echo "chruby ruby-3.4.1" >> ~/.zprofile 
```

- 安装 jekyll
```shell
gem install jekyll
```

- 安装 jekyll-paginate
```shell
gem install jekyll-paginate
```