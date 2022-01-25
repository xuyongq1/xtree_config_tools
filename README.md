# xtree_config_tools
一个根据规则可以随意定制树形结构，并将数据导出为json文件。

1、在程序开始时按“alt”键能打开分辨率对话框

2、xtree_template目录下的tree_type.json控制：配置路径（"data_path"是绝对路径）、树形数据表结构类型（"tree_template_path"）和树形数据表结构模板类型（"template_type_path"）

3、示例包含当前版本所有数据类型，有：BOOL、INT32、FLOAT、STRING、VECTOR2、VECTOR3、VECTOR4、ARRAY、FIXED_DICT、UNION、ENUME、MUL_SELECT、FIXED_ARRAY
     其中有的可以嵌套和互相嵌套（注意避免死循环），例如：ARRAY里有FIXED_DICT、FIXED_DICT又有ARRAY。

4、具体的配置方法可以参考提供的示例

5、其中<describe> 描述 </describe>  是鼠标悬浮在字段名上显示描述的字段。可自行决定是否配置。

6、<Default>默认值</Default>   默认值也可自行决定是否配置。

7、其中"data_path"是绝对路径可以配置在其他文件路径，"tree_template_path"和"template_type_path"是相对exe目录的路径
