##Session 6: Security Testing

The aim of this session is to help tester to kick start the Security Testing journey.

####Agenda:

1. Security Testing in daily work
	- Dedicated security tester
	- Per task assigned
	- QA on Security Test result
	- ...
	
2. Type of Security Testing
	- Whitebox
	- Blackbox
	- Graybox
	
3. Tools for using
	- Web - browser (Chrome, Firefox, IE)
	- Burbsuite
	- OWASP ZAP
	- ...
	
4. Important note before hands-on

5. Hands-on Test Lab

####Installation Instruction
######Prerequisite packages:
- <a href="https://www.virtualbox.org/wiki/Downloads" target="_blank">Install Virtualbox</a><br>
- <a href="http://rubyinstaller.org/downloads" targe="_blank">Install DevKit (Windows user only)</a><br>
This package is to support Ruby to build native package (for gem installation).<br>
You should choose a non-space in full path as the destination for the kit. i.e C:\DevKit<br>
Then go to the DevKit folder to run devkitvars.bat

######Important time saving note
Since creating first virtual machine would trigger downloading (~ 1.7GB) and compiling gems, please run below command prior coming to the session

For VirtualBox user:
```
sh
http://sourceforge.net/projects/owaspbwa/files/1.1.1/OWASP_Broken_Web_Apps_VM_1.1.1.ova/download
```
For VMWare Player user:
```sh
http://sourceforge.net/projects/owaspbwa/files/1.1.1/OWASP_Broken_Web_Apps_VM_1.1.1.zip/download
```

######Ruby and related Gems
- For Unix:
```sh
curl -sSL https://get.rvm.io | bash -s stable --ruby
```
- For Windows: download and install <a href="http://rubyinstaller.org/downloads/" target="_blank">Ruby</a>

```sh
sudo gem install bundler
bundle install
```

######Checkout project from GitHub
- If you don't have git, you can find it <a href="http://git-scm.com/downloads" target="_blank">here</a>.
```sh
git clone https://github.com/SydneyTestersBootcamp/sydneyTestersBootcamp.git
```

For Windows, you will need an <a href="http://the.earth.li/~sgtatham/putty/latest/x86/putty.zip" target="_blank">SSH client</a><br>
Port: 22<br>
Host: 33.33.33.10 (the ip address in your Vagrantfile)<br>

####Common issues

####Reading Material

