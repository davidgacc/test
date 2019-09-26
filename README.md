# test

  Example:
  
|			User Id             |		Status Card       		|
| :---------------------------: |-------------------------------|
|		user-1			 		|`{"account": {"active-card": true, "available-limit": 80}, "violations": []}`|
|		user-2         			|`{"account": {"active-card": true, "available-limit": 10}, "violations": ["insufficient-limit"]}`|           
|		user-3					|`{"account": {"active-card": true, "available-limit": 12}, "violations": ["account-already-initialized"]}`|
|		user-4					|`{"account": {"active-card": true, "available-limit": 15}, "violations": ["card-not-active"]}`|
|								|`{"account": {"active-card": true, "available-limit": 14}, "violations": []}`|
|		user-n					|`{"account": {"active-card": true, "available-limit": 9}, "violations": []}`|
