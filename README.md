### 笑看风雨淡，坐看云起时。

### day 1:

1. 什么是单页 app应用
2. React技术的基本原理
3. 创建第一个React应用

#### 基本原理：

1. 自动化的UI 状态管理
2. 快速的DoM操作
3. 创建可重用的UI组件
4. UI的纯js开发
5. React 是MVC 模式中的V

#### 开发第一个React 程序

1. 引入JSX 的基本概念
2. 搭建一个React程序的基本框架
3. 程序界面的样式化

#### 基本概念

##### 单页模型：

优点：
1. 不同的视图页面展示在一个单一的页面中，新页面不用频繁的访问服务器，只需数据。
2. 减少了 C 与 S 之间的交互延迟，更多的利用了本地的计算能力，及时的响应，优化体验。
3. 提供自动化的UI管理，数据的变化可以写成一个个事件，根据事件改变 也可以对界面进行变化。
4. 更高效的DOM 操作。 内存中 存了 DOM 虚拟DOM的缓冲机制，不段和浏览器去对比，可以告诉浏览器 提交的改变
5. UI组件化设计， 小的组件 可以组成大的 复杂的组件。每个小的组件都是独立的，可以相互组合。

缺点：
1. 数据页面的同步问题。 数据与UI的同步更新。 必须快速，高效的才能保证用户体验。
2. 如何提高DOM 操作的效率。
3. 使用HTML 开发UI界面异常的复杂

6. 依赖JS 开发UI 界面。 JSX 
7. React 是MVC 中的V 开发单页的APP 简单，

### day 2：

1. React组件化思维
 - 面向对象的思想
 - 组件分解  组件可以一直分解，分解到不可分解
 - 组件与函数
 - hello world 组件
 - 组件可重用

 2. 组件样式设计
  - 组件中 class名 为 `className = "xxx"`
  - css tyle 可封装到 json格式 放到自定义组件 内部  属性名需要修改

 3. 设计复合控件

 4. 组建的属性传递机制
   - `...` 属性的扩展操作符     `...this.props`  意义深远 逐个 解析 json里面的对象  react 特用的
   - 减少了工作量 及 bug

   7-2 end




