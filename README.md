# npm
npm 相关
## npx
npx espress 除了环境变量里包含的全局包目录，还可以找到 ./node_modules/bin/express.cmd
## 包支持cli
package.json里增加bin: {'cmd': 可执行文件路径}
private设为ture
可执行文件声明使用node执行
使用npm link提升为全局包
执行cmd

## npm 发布
文件夹包含package.json
npm login
npm publish
