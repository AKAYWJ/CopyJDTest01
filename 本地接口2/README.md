## json-server

	### 1,目录创建

### 2,   cd进入目录,cmd窗口

### 3， json-server --watch db.json --port 3001

### 4,   创建package.json  ,

​		{

 			 "scripts": {

​    			"dev": "json-server db.json"

  			}

​		}

### 5 ，  get请求  ：

​				?id=&name=

### 6 , 分页

​				localhost:3000/getDtaList?_page=2&_limit=2

​				_page : 自定义页数 ； _limit ： 自定义每页数据数量

### 7 ， 排序

​				localhost:3000/getDataList?_sort=id&_order=desc

​				_sort=id : 根据id排序  ；  _order ：规定排序规则（ asc | desc），正排序 | 逆排序

### 8 , 模糊查询

​		localhost:3000/getDataList?name_like=Apple

​		***_like=***

### 9 , 全文检索

​		localhost:3000/getDataList?q=*

​				q=*

### 10 ， PUT请求更新数据

​		var props = {

​			name : "yyyy"

​		}

​		axios.put('localhost:3000/getDataList/id',props)

		#### 注意：若无数据则会创建，未给出的字段会清空，所以建议采用PATCH

###  11 , DELETE请求删除数据

​		axios.delete('localhost:3000/getDataList/id')