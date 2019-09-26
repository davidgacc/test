# test

  Example:
  
	| User 	 | Status-Card |
	| ------ | ------ |
	| user-1 | {"account": {"active-card": true, "available-limit": 80}, "violations": []} |
	| user-2 | {"account": {"active-card": true, "available-limit": 80}, "violations": ["insufficient-limit"]} |
	| user-3 |  {"account": {"active-card": true, "available-limit": 100}, "violations": ["account-already-initialized" ]} |
	| user-4 | {"account": {"active-card": true, "available-limit": 12}, "violations": []} |
	| user-(n-1)| {"account": {"active-card": true, "available-limit": 2}, "violations": []} |
	| user-n | {"account": {"active-card": true, "available-limit": 10}, "violations": []} |
