- v1.1.2(2017-04-22)
  - 新增了zealot加载完成时的banner显示
  - 新增或升级了一些pom文件中的插件，如：pmd、reports等
  - 其他代码小细节修改
- v1.1.1(2017-04-16)
  - 新增了ZealotKhala和xml标签的常用API，如：大于、小于、大于等于、小于等于等功能。
  - 新增了Zealot中xml的text标签，使灵活性SQL拼接灵活性更强
  - 新增了ZealotKhala的`ICustomAction`接口，使自定义的逻辑也能够通过链式写法完成，使SQL拼接逻辑更紧凑
  - 标记`Khala.java为推荐使用，即`@Deprecated`。推荐使用`ZealotKhala.java`，使SQL的动态性、灵活性更强。
- v1.1.0(2017-04-04)
  - 新增了`ZealotKhala`，使ZealotKhala用Java也可以链式的书写动态SQL，和Zealot的XML标签相互应
- v1.0.7(2017-03-31)
  - 使用`Google CheckStyle`来规范Java代码风格,重构了部分代码,使代码更整洁
  - Khala字符串的链式拼接去掉了手动`newInstance`的方式，直接调用`start()`方法即可
- v1.0.6(2016-12-31)
  - 新增灵活强大的流程逻辑控制标签
  - 新增自定义标签的示例和单元测试
- v1.0.5(2016-12-29)
  - 新增Zealot基本功能的单元测试
  - 重构Zealot缓存加载的代码
  - 新增了Khala的获取实例的方法
- v1.0.4(2016-11-12)
  - 新增了SQL字符串链式拼接工具类`Khala.java`
- v1.0.3(2016-11-11)
  - 修复了区间查询大于或等于情况下的bug
  - XmlNodeHelper中新增`getNodeAttrText()`方法
- v1.0.2(2016-11-10)
  - 将缓存文档改为缓存Zealot节点，使生成sql效率更快
  - 代码细节重构调整
- v1.0.1(2016-11-08)
  - 新增日志功能，替换System.out
  - 新增自定义异常
  - 完善文档注释
- v1.0.0(2016-11-04)
  - 核心功能完成