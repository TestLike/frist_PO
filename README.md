# frist_PO
this is my frist page object model （python + pytest ）

文件内封装了部分webdriver进行移动端UI自动化的方法
包括：
1.self.driver.find_element_by_xpath
2.self.driver.find_element_by_id
3.self.driver.find_element_by_class_name

分离了：
公共部分抽取在base文件夹
参考：base_driver.py
抽取公共方法：
参考：base_action.py


页面主体抽取page类目下
测试用例1：
display_page.py
测试用例2：
network_page.py

执行脚本抽取scripts类目下
测试用例1的执行脚本：
test_display.py
测试用例1的执行脚本：
test_display.py
测试用例2的脚本：
test_network.py

pytest执行文件
pytest.ini


