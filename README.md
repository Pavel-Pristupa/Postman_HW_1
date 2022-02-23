# Postman_HW_1

__Create requests via Postman__  
  
Protocol: http  
IP: 162.55.220.72  
Port: 5005  
____
### EP_1  
Method: __GET__  
EndPoint: `/get_method`  
request url params:  
 name: str  
 age: int  
  
response:   
```json
[
    “Str”,
    “Str”
]
```
____
  
### EP_2  
Method: __POST__  
EndPoint: `/user_info_3`  
request form data:  
 name: str  
 age: int  
 salary: int  
  
response:   
```js
{
	'name': name,
	'age': age,
	'salary': salary,
	'family': {
		'children': [['Alex', 24], ['Kate', 12]],
		'u_salary_1_5_year': salary * 4
	}
}
```
  
____
  
### EP_3  
Method: __GET__  
EndPoint: `/object_info_1`  
request url params:  
 name: str  
 age: int  
 weight: int  
  
response:   
```js
{
	'name': name,
	'age': age,
	'daily_food': weight * 0.012,
	'daily_sleep': weight * 2.5
}
```
  
____
### EP_4  
Method: __GET__  
EndPoint: `/object_info_2`  
request url params:  
 name: str  
 age: int  
 salary: int  
  
response:  
```js
{
	'start_qa_salary': salary,
	'qa_salary_after_6_months': salary * 2,
	'qa_salary_after_12_months': salary * 2.7,
	'qa_salary_after_1.5_year': salary * 3.3,
	'qa_salary_after_3.5_years': salary * 3.8,
	'person': {
		'u_name': [user_name, salary, age],
		'u_age': age,
		'u_salary_5_years': salary * 4.2
	}
}
```
  
____
### EP_5  
Method: __GET__  
EndPoint: `/object_info_3`  
request url params:  
 name: str  
 age: int  
 salary: int  
  
response:   
```js
{
	'name': name,
	'age': age,
	'salary': salary,
	'family': {
		'children': [['Alex', 24], ['Kate', 12]],
		'pets': {
			'cat':{
				'name':'Sunny',
				'age': 3
			},
			'dog':{
				'name':'Luky',
				'age': 4
			}
		},
		'u_salary_1_5_year': salary * 4
	}
}
```
  
____
### EP_6  
Method: __GET__  
EndPoint: `/object_info_4`  
request url params:  
 name: str  
 age: int  
 salary: int  
  
response:   
```js
{
	'name': name,
	'age': int(age),
	'salary': [salary, str(salary * 2), str(salary * 3)]
}
```
____
### EP_7  
Method: __POST__ 
EndPoint: `/user_info_2`  
request form data:  
 name: str  
 age: int  
 salary: int  
  
response:   
```js
{
	'start_qa_salary': salary,
	'qa_salary_after_6_months': salary * 2,
	'qa_salary_after_12_months': salary * 2.7,
	'qa_salary_after_1.5_year': salary * 3.3,
	'qa_salary_after_3.5_years': salary * 3.8,
	'person': {
		'u_name': [user_name, salary, age],
		'u_age': age,
		'u_salary_5_years': salary * 4.2
	}
}
```