# Meteor React Outpost

### for my own sanity I need to document the stop by step of getting the bare bones app set up

* Base Creation
	* `meteor create outpost-01`
	* `cd outpost-01`
* Common modules and tasks
	* `meteor npm install --save babel-runtime`
	* `meteor npm install --save bcrypt`
	* `meteor remove insecure`
	* `meteor remove autopublish`
	* `meteor update --all-packages`
* That should get us to a point boot up the meteor server
	* `meteor`

* Added some meta details to the **package.json** file.

* Adding React packages
	* `meteor npm install --save react react-dom`

* Adding back in the base files
	* **main.html**
	* **main.js**
	*
