# Vue实例
    1.所有配置对象的data对象都会绑给Vue实例对象
    2.一个Vue实例就是一个组件对象
    
### 属性
    vm.$root(只读)
        当前组件树的根 Vue 实例。如果当前实例没有父实例，此实例将会是其自己
    vm.$el(只读)
        Vue 实例使用的根 DOM 元素。
    vm.$options(只读)
        用于当前 Vue 实例的初始化选项。需要在选项中包含自定义属性时会有用处  
    vm.$data
       Vue 实例观察的数据对象。Vue 实例代理了对其 data 对象属性的访问。  
 
### 方法
    vm.$mount( [elementOrSelector] )       
     如果 Vue 实例在实例化时没有收到 el 选项，则它处于“未挂载”状态，
     没有关联的 DOM 元素。可以使用 vm.$mount() 手动地挂载一个未挂载的实例。

### 事件
     vm.$on
        监听当前实例上的自定义事件。事件可以由vm.$emit触发。回调函数会接收所有传入事件触发函数的额外参数。
     vm.$emit
        触发当前实例上的事件。附加参数都会传给监听器回调
     vm.$once
        监听一个自定义事件，但是只触发一次，在第一次触发之后移除监听器
     vm.$off
         移除自定义事件监听器。
             如果没有提供参数，则移除所有的事件监听器；
             如果只提供了事件，则移除该事件所有的监听器；
             如果同时提供了事件与回调，则只移除这个回调的监听器。
   
     
  
  
   







