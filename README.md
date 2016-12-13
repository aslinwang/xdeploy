xdeploy
======

A tool to push files to remote server

Install
-------
* `npm install xdeploy -g`


Usage
-----
* create xdeploy.json file at root of the directory that you will push from
```
{
  "receiver" : "http://deploy.city.qq.com/receiver.php",
  "to" : "/usr/local/qqcom_app/proj",
  "retry" : 5
}
```
files will be pushed to `to`
* `xdeploy -a`
start to push
