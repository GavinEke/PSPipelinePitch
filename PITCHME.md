@title[Introduction]

## Creating a PowerShell Release Pipeline

---

@title[Who Am I?]

### Who Am I?
![Avatar](images/avatar.jpg)
* Gavin Eke
* Infrastructure Administrator for Daracon
* Author of [Scripting.Rocks](http://scripting.rocks/)

---

@title[The Release Pipeline Model]

### The Release Pipeline Model

![Pipeline](images/pipeline.jpg)

[http://aka.ms/thereleasepipelinemodel](http://aka.ms/thereleasepipelinemodel)

Note: The release pipeline model is a whitepaper by Michael Greene and Steven Murawski of Microsoft (Steven Murawski was at Chef when the whitepaper was published) which was published in April 2016.

---

@title[Source]

### Source
![Source](images/source.jpg)
#### Single path for changes

* Who made the change?
* What did they change?
* When did the change happen?

Note: Why use source control? Single source of truth and versioning

---

@title[Source2]

### Source
![Source](images/source.jpg)
#### Single path for changes

* Git
* TFVC

Note: What tools can we use? GitHub, GitLab, BitBucket, Team Foundation Server, Visual Studio Team Services

---

@title[Build]

### Build
![Build](images/build.jpg)
#### Run scripts when changes are checked in

* Orchestrate tasks
* Create isolated environment
* Notify results

Note: What does the build system provide for me?

---

@title[Build2]

### Build
![Build](images/build.jpg)
#### Run scripts when changes are checked in

* PSake
* Invoke-Build
* AppVeyor
* Travis CI

Note: What tools are avalible for a build system?

---

@title[Testing]

### Testing
![Testing](images/testing.jpg)
#### Run scripts to evaluate the quality of changes

* Check for issues
* Test on different environments

Note: I don't think anyone needs to ask why is testing important

---

@title[Testing2]

### Testing
![Testing](images/testing.jpg)
#### Run scripts to evaluate the quality of changes

* Pester
* PSScriptAnalyzer

Note: What tools can I use for testing my PowerShell modules and scripts?

---

@title[Release]

### Release
![Release](images/release.jpg)
#### Deploy changes to production

* Can I deploy straight to production?
* Where are the changes

Note: Can we go straight to production, what do we need to do to go to production

---

@title[Release2]

### Release
![Release](images/release.jpg)
#### Deploy changes to production

* PSDeploy

Note: Talk about NuGet Feeds (PSGallery, MyGet, VSTS, TFS 2017) or File Share

---

### Demo

---

### Thanks!

![Rin Avatar](img/rin.jpg)
* [@GavinEke on Twitter](https://twitter.com/GavinEke)
* [GavinEke on GitHub](https://github.com/GavinEke)
* [http://scripting.rocks/](http://scripting.rocks/)
* [https://github.com/markekraus/2017NovemberWebCmdletsTalk](https://github.com/markekraus/2017NovemberWebCmdletsTalk)

---

## Q & A