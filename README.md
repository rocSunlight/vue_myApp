### npm run dll (打包一次变不在需要打包了)
### npm run dev 本地开发
### npm run build 打包
### 在线访问：https://rocSunlight.github.io/vue_myApp/.

## 目录结构
- build  -- webpack配置
    - build.js  -- 配置全局压缩包
    - webpakc.base.conf.js -- webpack基本配置
    - webpack.dev.conf.js -- 启动配置
    - webpack.dll.conf.js -- 打包一个DllPlugin处理
- config -- 项目配置
- src 项目包
    - components   -- 存放常用组件
    - directive    -- 常用指令封装
    - store        -- 状态管理vuex
    - utils        -- 常用的缓存和请求封装
    - views        -- 视图

