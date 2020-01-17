目的
	用于web页面回归测试的自动化测试演示

对象
	www.nzhg.co.nz在Firefox下的运行

TestSuit
	登录->选购->购物车->购买

TestCase
	登录： 使用已有账户登录网站，测试相关功能正确性
	选购： 选购商品，测试相关功能正确性
	购物车： 测试选购商品信息显示功能的正确性
	购买： 测试购买功能的正确性（不测试实际付款流程）
	
测试方面
	功能性
	
测试方法（目前支持firefox）
	方法： web-based UI自动化测试
	技术： java（jdk1.8）+eclipse+selenium+testng

测试运行及报告
	方法 java -jar jar包名称(或直接双击)
  报告 output文件夹下 emailable-report.html和index.html


---------------------------------------------------------------
信息： 0224079642/oraclepro9
