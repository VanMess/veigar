# Veigar

## 开发流程

1. git clone git@github.com:Pochodaydayup/veigar.git
2. cd veigar
3. yarn
4. yarn dev
5. cd veigar/packages/veigar && yarn link
6. cd veigar/packages/veigar-cli && yarn link
7. git clone git@github.com:Pochodaydayup/veigar-demo.git
8. cd veigar-demo
9. yarn
10. yarn link veigar && yarn link veigar-cli
11. yarn dev

## TODO

- [ ] veigar-cli 的开发
  - [x] 接入 webpack webpack-chain
    - [x] build 命令的开发
  - [ ] 完成 veigar-loader
    - [x] compile .vue 文件
    - [ ] compile .tsx 文件
  - [ ] 完成 veigar-webpack-plugin 插件
    - [ ] typescript(tsx) 友好支持
    - [x] 将每个 page 分别打包，将每个 js 文件分别打包

- [ ] veigar 的开发
  - [ ] comment 的优化，目前是会创建一个空节点
  - [ ] patch props
  - [ ] setData queue
  - [ ] 把 page 都当做组件来渲染，放在 main.js 里面渲染，而不是每个单独一个组件

- [x] 开发流程的优化
