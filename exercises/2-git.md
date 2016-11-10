---
layout: default
title:  '2. git and GitHub'
---

# <a name="begin"></a> Version control

## Preparations

If you haven't done so already, make sure that you do all preparatory steps described in [Preparations]({{site.url}}/preparations.html)
<br />

## Working with git in SourceTree

#### :computer: Add your project directory to SourceTree
<details markdown="1">
<summary>:key: Click to see hints</summary>

* _Clone / New_ -> _Create New Repository_ tab
	* **Repository Type**: Git
	* **Destination path**: path to your directory (can be selected by using the ... button)
	* Check the _Bookmark this repository_ option
	* **Name**: directory name (or what you want)
* At the next dialog, add your name and email address (preferable the same that you used when you registered your GitHub account)
	* Check the _Use these details for all repositories_ option@
</details>  
<br />

#### :computer: Do an initial commit of your files
<details markdown="1">
<summary>:key: Click to see hints</summary>

* Open your project repository in SourceTree
* On the lefthand panel of your project, select FILE STATUS - Working Copy
* Select the files listed under 'Unstaged files' and click _Stage selected_
* Type an short and informative message in the commit message text field at the bottom, e.g. `Initial commit`
* Hit commit button
* (Expand the BRANCHES tab on the left, and select the master branch to see what was committed)

</details>  
<br />

#### :computer: Edit one of the files, and commit the change
<details markdown="1">
<summary>:key: Click to see hints</summary>
* Select the changed file listed under 'Unstaged files', and view the changes that has been made
* Type an short and informative message in the commit message text field at the bottom, e.g. `Added more information about this or that`
* Hit commit button
* (Expand the Branches tab on the left, and select the master branch to see what was committed)
</details>  
<br />

#### :computer: Add a file to your project that you don't want to commit to git.
For example, this could be a dataset file that you don't want to make public yet, e.g. `my_project/data/raw/2016-11-16/bryceveg.R`. Make git ignore this file.
<details markdown="1">
<summary>:key: Click to see hints</summary>
* Add a file somewhere in your project directory
* Right-click the recently added file (listed under 'Unstaged files'), and select the _Ignore..._ choice.
	* Select an appropriate available option, and click OK
* Notice that a new file _.gitignore_ has appeared. Add and commit that file to your repository.
</details>  
<br />
