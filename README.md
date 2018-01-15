# inputnumber计数器
### 此组件时基于vue前端框架，安装成功后在入口文件中添加一下代码，就可以在全站使用

`import Inputnumber from './components/customcomponents/inputnumber'`
`Vue.use(Inputnumber)`

### 在组件中一下代码可以引入
`<inputnumber></inputnumber>`


### 可接收的参数
| 参数名称        | 说明           | 默认值  |
| ------------- |:-------------:| -----:|
| step      | 计数器步长 | 1 |
| max      | 允许设置的最大值      |   infinity |
| min       | 允许设置的最小值      |    0 |
| value     | 设置值      |    - |
| attr     | 传入数组 可在值改变时返回这些数组      |    - |

### 事件
| 事件名称        | 说明           | 返回值  |
| ------------- |:-------------:| -----:|
| change      | 绑定值被改变时触发 | 新值，旧值，传入的数组 |
