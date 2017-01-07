# 生命周期

* 初始化阶段
* 运行中阶段
* 销毁阶段

我们在使用的时候无非就是用很多钩子函数
其实组件的本质就是一个状态机，如果输入一定，输出就一定

state，prop

用事件的方式来理解状态，但是状态之间有关系

实例是被组件初始化出来的

初始化--》运行中--》销毁

## 初始化阶段对应五个钩子：
* getDefaultProps(第一个实例的时候调用)
* getInitialState
* compentWillMount
* render
* compentDidMount

## 运行中对应的五个钩子:
* comopnentWillReceiveProps (传送给组件之前，有机会可以修改属性)
* shouldCompentUpdate (组件是否要更新，认为控制是否需要更新，提高性能return)
* comopnentWillUpdate(不能修改属性和状态)
* render(只能访问this.state和this.props)
* CompentDidUpdate

## 销毁阶段对应的五个钩子
* compentWillUnmount(做一些清理)

