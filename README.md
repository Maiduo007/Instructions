# Instructions


### 使用方法
#### 安装node环境
下载地址：https://nodejs.org/dist/v8.11.3/node-v8.11.3-x64.msi
正常安装，安装完成后测试一下是否成功，打开cmd，输入
```
node -v
//v8.11.3

npm -v
//5.3.0
```
输出版本号说明安装成功。

#### 下载代码（前提安装过git）
+ 前端： `git clone https://github.com/Maiduo007/FrontERMS.git`

安装依赖：（可以使用cnpm）
```
cd FrontERMS

npm install
```
启动：`npm start`


+ 后端：`git clone https://github.com/Maiduo007/BackendERMS.git`

安装依赖：（可以使用cnpm）
```
cd BackendERMS

npm install

```

启动数据库（MySQL）并创建一个新数据库

修改数据库配置：
`utils/config.js中按照自己实际配置填写`

数据库初始化： `npm init_sql`

启动：`npm run dev`

输入管理员用户名密码登陆
账号：admin
密码：admin


### 未完成功能：
* 管理员导入实验、老师、学生等信息，目前都是模拟数据
