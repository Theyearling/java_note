# java_note

### component
    可视化用户界面（GUI）应用程序中的可重用元素，用于构建用户界面的各个部分。可以包含其他组件，具有自己的属性、行为和绘制方式。

    常见Component类型：
    1. JButton：点击按钮，可以触发动作事件
    2. JTextField：文本输入框，可以输入和编辑单行文本
    3. JLable：文本或图像，显示静态文本或图像，通常用于显示标题、说明或图像等信息。
    4. JComboBox：下拉列表组件，在用户选择后触发相应的事件
    5. JCheckBox：复选框组件，可以选择一个或多个选项，并在选择后触发相应的事件
    6. JRadioButton：单选按钮组件，用户选择后触发相应的事件

### @Component
    用于标识一个类为Spring组件，使得Spring能够扫描并将其实例化为可管理的Bean

### Bean
    表示在软件开发中符合规范的可重用的软件组件

### DAO
    Data Access Object（数据访问对象），是一种设计模式，将数据访问逻辑和业务逻辑分离
    通常包含了与数据访问相关的类和接口，封装了与数据存储的交互，提供了对数据的持久化、检索、更新和删除等操作

### Domain
    表示问题领域中的概念和业务规则的模型
    通常包含了业务实体、业务逻辑和业务规则，用于解决特定的业务问题

### VO
    Vaule Object（值对象），表示一个不可变的值或简单的数据结构

### @Repository
    用于标识一个类为数据访问对象（DAO）或存储库（Repository），用于在Spring应用程序中定义和管理数据访问对象

### @ApiModelProperty
    为API接口的模型属性进行描述和注释

    常用属性：
    value：属性的说明或描述信息
    name：属性的名称
    dataType：属性的数据类型
    example：属性的示例值
    required：指定属性是否为必须的，默认为false
    hidden：指定属性是否在生产的文档中隐藏，默认为false

### extends
    实现类之间的继承

### implements
    实现接口

### implements Serializable
    实现Serializable接口，需要实现一个特定的方法以支持对象的序列化和反序列化

### super
    用于引用父类的成员变量、方法和构造函数
    也可以访问外部类

    super.成员变量名 super.方法名() ——> 访问父类的成员变量和方法
    super()  super(参数) ——> 调用父类的无参 带参构造函数

### autowired
    当一个类依赖于其他类的实例时，通常需要手动创建这些实例并将它们注入到依赖类中，使用@Autowired注解可以自动完成这个过程

### @SpringBootApplication
    用于标识一个主程序类，表示是Spring Boot应用程序的入口点

### @PostMapping
    当客户端发送一个POST请求到该方法映射的URL时，Spring将会调用该方法来处理请求，并返回相应的结果

### LinkedHashMap
    按照键值对的插入顺序来排序，维护其插入的先后顺序，并按照这个顺序进行迭代和访问
