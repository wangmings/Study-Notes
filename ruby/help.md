# ruby版本管理工具使用

### 安装rbenv工具
> **rbenv** 是Ruby版本管理工具


```sh
git clone https://github.com/rbenv/rbenv.git ~/.rbenv
echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc
echo 'eval "$(rbenv init --no-rehash -)"' >> ~/.bashrc
```


### rbenv

```sh
# 查看安装的所有rbenv版本
rbenv versions

# 查看ruby支持的所有版本
rbenv install -l

# 安装ruby版本
rbenv install 2.6.3

# 切换ruby版本
rbenv global 2.6.3

# 查看ruby版本
ruby -v
```

### bundle
> **bundle** 是一个用于管理 Ruby 项目依赖关系的工具
> 通常与 **rbenv** 和 **gem** 一起使用

```sh
# 查看 bundle 依赖列表
bundle list

# 安装 bundle 依赖
bundle install

# 更新 bundle 依赖
bundle update
```


### gem
> **gem** 是一个用于管理 Ruby 项目的包的工具
> 通常与 **rbenv** 和 **bundle** 一起使用

```sh
# 查看安装的所有依赖包列表
gem list
# 安装依赖包
gem install plist
# 更新 gem 依赖
gem update
```