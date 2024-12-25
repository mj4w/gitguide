# Version-Control (GIT)

<p>These are the compilation of <strong>git command</strong>. </p>

<h3>Brief Description:</h3>
<p>* Version Control System falls in two categories: Centralized and Distributed</p>
<p>* To interact with <strong>git</strong> you need > "The Command Line"</p>

<hr>

### Starter Pack
 
 Install: [git](https://git-scm.com/)

<hr>

> NOTE
> If you are first time to install git, you need to introduce > yourself in the terminal.

```git
git config --global user.name "your name"
git config --global user.email youremail.com
```
<hr>

### To assign default editor in the terminal: 

```git
git config --global core.editor "code --wait"
git config --global -e
```

> Note
> To prevent issue from carriage return 

If you are on Windows you should set as to *True*
```git
git config --global core.autocrlf true
```
If you are on Mac/Linux you should set as to *Input*
```git
git config --global core.autocrlf input
```
