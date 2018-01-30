# TaxiMap
Map for showing the taxi traces as homework of Data Structure;

用一个例子的操作顺序来说明运行框架：
  ①数据清洗：
  下载下来的原TXT文件有很多字符，例如横杠- 冒号： 以及空格 等等。
  
  
  先全部统一，方便到时候对不同属性的字符串进行分类。我的例子是把所有字符换成了制表符'\t'。
  
  ②构建页面：
  先引入百度地图api接口作为src
  
