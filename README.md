Angular Seed
---

  
### Features:

* Angular AMD support
* Single require.js app/tests config
* Require.js optimization support (r.js)
* Karma test runner support
* Mocha/Chai support


### 1. Resolving dependencies

	bower install
	npm install
	
	
### 2. Grunt tasks


#### 2.1. Running the app in dev mode	
	
	grunt express:dev
	http://localhost:9000

	
#### 2.2. Running the app in prod mode

	grunt requirejs
	grunt express:prod
	http://localhost:9000
	
Note: If r.js raises a bad syntax error, use the following command:
	
	grunt requirejs --force
	 


#### 2.3. Running unit tests

	grunt karma:unit


