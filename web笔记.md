
# web笔记

在了解前端，后端的过程中

一，学习的前端架构在node.js上，运用node.js自带的npm包管理工具，管理库，如react、angular、vue等。
    Node.js 库通过 Node.js 包管理器 npm 维护，它可以帮助安装各种开源库。Node重要的 Node.js 库，这些库使网页开发变得更加简单。
    Node.js 是一个开源的、用于 JavaScript 编程的服务器端运行环境。
    在这个运行环境中，它只管前端的服务挂起，后端的服务由其他在承担。
    Node.js是开发平台，Nginx是HTTP基础设施。这两个同处一组，一个用与开发，另一个用于部署和使用。
    原则上说Nodejs的http包可以替代nginx，开发阶段也是这样做的，但实际部署都是nodejs作为逻辑层，位于nginx之后。原因在于Nginx的成熟的反向代理和高性能，高可配置，高稳定性。

    可以选择使用集成开发环境（如WebStorm、Sublime Text）或使用命令行工具（如npm、yarn）来安装各种前端框架。
    拿vue这个前端框架举例，在npm install命令后面加上vue -S，后，在从vue框架里安装需要的组件，如vue-router、vuex、vue-cli等，再创建一个项目，就可以使用这些组件了。样式组件如 element-plus

    注：npm install命令的不同选项，如-S(-save)用于添加生产环境依赖，-D(-save-dev)用于添加开发环境依赖，-g表示全局安装。同时解释了dependencies和devDependencies的区别，前者用于生产环境，后者用于开发环境。还提到了npm模块的安装与移除方法。

    npm作为Node.js的包管理器，可以安装各种开源库，如react、angular、vue等。vue作为前端框架，可以安装各种组件，如element-plus、element-ui、ant-design-vue等。




    Deno。它是 Node.js 的替代品，（Deno可能会成为下一代 Node.js-----https://www.ruanyifeng.com/blog/2020/01/deno-intro.html）
    Deno 只支持 ES 模块，跟浏览器的模块加载规则一致。没有 npm，没有 npm_modules 目录，没有require()命令（即不支持 CommonJS 模块），也不需要package.json文件。
    所有模块通过 URL 加载，比如import { bar } from "https://foo.com/bar.ts"（绝对 URL）或import { bar } from './foo/bar.ts'（相对 URL）。因此，Deno 不需要一个中心化的模块储存系统，可以从任何地方加载模块。
    Deno的官网：https://deno.land/      https://www.denojs.cn/manual/basics/standard_library












二，学习后端架构在Spring（STS 一个集成开发环境）上，
    运用Spring自带的maven包管理工具，管理库，如Spring MVC、Spring Boot、MyBatis等。
    Spring是一个开源的、用于Java开发的应用框架，它提供了一系列框架和工具，可以简化开发过程。
    Spring Boot是一个快速开发框架，它可以帮助开发者快速搭建基于Spring的应用。
    Spring MVC是一个基于Servlet的MVC框架，它可以帮助开发者构建基于Web的应用。
    MyBatis是一个持久层框架，它可以帮助开发者构建灵活的、可扩展的数据库应用。        

    可以选择使用集成开发环境（如IntelliJ IDEA、Eclipse）或使用命令行工具（如mvn、gradle）来安装各种后端框架。





