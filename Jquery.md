# Ajax

## 1	ajax基本属性

### URL  				String 				请求的地址

###  type				String 				请求的方式,默认GET

### Timeout		  number			请求超时时间(毫秒)

### data 				  object 			发送到服务器的数据

### datatype 		 String 			服务器返回的数据类型:text,html,xml,json,script

### beforeSend     Function 		发送请求之前要执行的函数,返回false则取消发送

### complete		 Function 		请求完成后调用的回调函数(无论成功与否)

### success			 Function 		请求成功后调用的回调函数

### Error 				 Function 		请求失败时调用的回调函数

### Global 			  Boolean   		默认为True,表示是否出发全局ajax



## 2	$.get()/$.post()方法  //参数

### url 					String 				请求的地址

### data 				object 				发送至服务器的数据

### callback 		Function 			成功的回调函数

### type 				String 				服务器返沪的数据类型



# 一般处理程序添加	Session

## 学会这三步 直接去天禄

> 引用类:		using System.Web.SessionState
>
> 实现接口:	IRequiresSessionState
>
> 访问和赋值:	context.Session[Value]





# Ajax 	全局事件

## ajaxStart	请求开始前

## ajaxSend	请求时

## ajaxSuccess	请求完成后

## ajaxComplete	请求完成时

## ajaxError	请求发送错误后

## ajaxStop	请求停止后

