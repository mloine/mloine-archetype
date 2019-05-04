# mloine-archetype
maven 自定义脚手架 生成项目


 1.脚手架测试项目
   mvn clean
 2. mvn archetype:create-from-project
 3. cd target/generated-sources/archetype
 4. mvn install
 
 配置参数可以快速创建 避免下载速度过慢
 1.mvn archetype:generate -DarchetypeCatalog=local
