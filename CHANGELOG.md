### 0.1.2-pre
* Move proxy environment variable handling to bag.http.requuest and bag.http.proxy

### 0.1.1
* Move status colouring to cli so that when lib/jenkins is used programatically then it gets plain uncoloured text
* JENKINS_URL is now handled by lib/jenkins

### 0.1.0
* Move commands setup to conf/commands.json, cli handling to bag.cli.command
* Move request handling to bag.http.request
* Change unit tests from Mocha to Buster
* Add irc command
* Modify Jenkins constructor, proxy is now part of opts

### 0.0.10
* Add stop command
* Colourise build status display
* Add -c/--console flag to build command

### 0.0.9
* Add proxy support
* Add console command

### 0.0.8
* Fix unexpected status code 405 on parameterised build
* Display error message when parameterised build is triggered without parameters

### 0.0.7
* Set max node engine to < 0.9.0

### 0.0.6
* Fix error message for status code 401 (authentication failed, instead of authentication required)
* Add sample usage commands to help info nestor -h

### 0.0.5
* Another rewrite lib (move to bagofholding, mocha, request)
* Fix undefined job status display
* Replace version command with ver (version is reserved by visionmedia/commander.js)

### 0.0.4
* Display usage on arg-less comamand
* Add support for Jenkins URL containing path e.g. http://host:port/path

### 0.0.3
* Rewrite lib

### 0.0.2
* Add Jenkins discovery feature
* Upgrade nomnom to 1.0.0
* Fix commands-flags association
* Add multiple job names support for job command

### 0.0.1
* Initial version
