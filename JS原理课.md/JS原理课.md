# JS原理课

# JavaScript 中的 this

在绝大多数情况下，函数的调用方式决定了 this 的值（运行时绑定）。this 不能在执行期间被赋值，并且在每次函数被 调用时 this 的值也可能会不同。

## 1. 如何确认this的值

在非严格模式下，总是指向一个对象，在严格模式下可以是任意值。

- 全局执行环境中，严格模式和非严格模式指向全局对象(window)

  ```js
  // 'use strict' 为全局开启严格模式
  console.log(this)	// 无论是否开启严格模式，this 都为 window对象
  ```

- 函数内部，取决于函数被调用的方式

  1. 直接调用的 this 值

      ① 非严格模式：全局对象(window)

      ```js
      function funb() {
      	console.log(this)	
      }
      ```

      ② 严格模式：undefined

      ```js
      function func() {
      	'use strict'
      	console.log(this)	
      }
      ```

  2. 对象方法调用的this值

      严格模式和非严格模式都为调用者

      ```js
      const food = {
      	name: '猪脚饭'
      	eat: function() {
      		'use strict'
      		console.log(this)	// 无论是否开启严格模式，this 都为 food 对象
      	}
      }
      food.eat() 	// 调用对象里的方法打印 this
      ```

## 2. 如何指定this的值

1. 调用时指定

    - call方法

    - apply方法
2. 创建时指定

    - bind方法

    - 箭头函数

## 3. 手写call、apply 、 bind:

‍
