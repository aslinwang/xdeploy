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
  "retry" : 5,
  "ignores" : ['.svn']
}
```
files will be pushed to `to`;
the path contains any item of `ignores` array will be ignored
* `xdeploy -a`
start to push


Default ignore string list
-----
* `.svn`
* `xdeploy`
* `.DS_Store`
* `.git`