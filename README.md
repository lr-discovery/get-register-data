Ruby restful interface to stub in json files
=======================

This is a VM to run which other services can can access the API of stubbed JSON formatted titles from the data migration team

### Prerequisite

* Vagrant (https://www.vagrantup.com)
* Virtual Box (https://www.virtualbox.org)
* Git (http://git-scm.com)

### Step 1

Clone the repo:

```
git clone https://github.com/lr-discovery/get-register-data.git
```

### Step 2

Access the sinatra web server on:
```
http://localhost:4567/
```
### Step 3

To start the sinatra web server as needed navigate to

/vagrant/register-stub

run 
```
ruby run.rb
```
