{
	"info": {
		"_postman_id": "135bfd76-83b2-4b19-9e92-d0ed34011f01",
		"name": "Postman HW_1",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json"
	},
	"item": [
		{
			"name": "EP_1",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "http://162.55.220.72:5005/get_method?name=dmitriy&age=30",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"get_method"
					],
					"query": [
						{
							"key": "name",
							"value": "dmitriy"
						},
						{
							"key": "age",
							"value": "30"
						}
					]
				}
			},
			"response": []
		},
		{
			"name": "EP_2",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "name",
							"value": "dmitriy",
							"type": "text"
						},
						{
							"key": "age",
							"value": "30",
							"type": "text"
						},
						{
							"key": "salary",
							"value": "1000",
							"type": "text"
						}
					]
				},
				"url": {
					"raw": "http://162.55.220.72:5005/user_info_3",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"user_info_3"
					]
				}
			},
			"response": []
		},
		{
			"name": "EP_3",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "http://162.55.220.72:5005/object_info_1?name=dmitriy&age=30&weight=76",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"object_info_1"
					],
					"query": [
						{
							"key": "name",
							"value": "dmitriy"
						},
						{
							"key": "age",
							"value": "30"
						},
						{
							"key": "weight",
							"value": "76"
						}
					]
				}
			},
			"response": []
		},
		{
			"name": "EP_4",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "http://162.55.220.72:5005/object_info_2?name=dmitriy&age=30&salary=1000",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"object_info_2"
					],
					"query": [
						{
							"key": "name",
							"value": "dmitriy"
						},
						{
							"key": "age",
							"value": "30"
						},
						{
							"key": "salary",
							"value": "1000"
						}
					]
				}
			},
			"response": []
		},
		{
			"name": "EP_5",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "http://162.55.220.72:5005/object_info_3?name=dmitriy&age=30&salary=1000",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"object_info_3"
					],
					"query": [
						{
							"key": "name",
							"value": "dmitriy"
						},
						{
							"key": "age",
							"value": "30"
						},
						{
							"key": "salary",
							"value": "1000"
						}
					]
				}
			},
			"response": []
		},
		{
			"name": "EP_6",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "http://162.55.220.72:5005/object_info_4?name=dmitriy&age=30&salary=1000",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"object_info_4"
					],
					"query": [
						{
							"key": "name",
							"value": "dmitriy"
						},
						{
							"key": "age",
							"value": "30"
						},
						{
							"key": "salary",
							"value": "1000"
						}
					]
				}
			},
			"response": []
		},
		{
			"name": "EP_7",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "name",
							"value": "dmitriy",
							"type": "text"
						},
						{
							"key": "age",
							"value": "30",
							"type": "text"
						},
						{
							"key": "salary",
							"value": "1000",
							"type": "text"
						}
					]
				},
				"url": {
					"raw": "http://162.55.220.72:5005/user_info_2",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"user_info_2"
					]
				}
			},
			"response": []
		}
	]
}
