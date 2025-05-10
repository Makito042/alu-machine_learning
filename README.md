Last login: Sat May 10 11:23:14 on ttys000
mac@makito ~ % ls
-summative_assessment_one_group9
AirBnB_clone_v2
AirBnB_clone_v3
AirBnB_clone_v4
AppDataRoamingPythonScriptsfab-script.py
Applications
Betty
CascadeProjects
Desktop
Development
Documents
Downloads
Dropbox
Library
Movies
Music
OpenSSH_8.1p1,
Pictures
Public
PycharmProjects
SparseMatrix
Stock-metrics
Untitled Project
Vagrantfile
VirtualBox VMs
WebstormProjects
ai_completion
alu-AirBnB_clone
alu-back-end
alu-interview
alu-scripting
alu-system_engineering-devops
alu-web-development
alu-web_front_end
alu-webstack
alx-higher_level_programming
alx-low_level_programming
alx-system_engineering-devops
bank
banking
bans
bk
card
chat
debug1:
document
document.pub
fatal:
fil
group-9-project
install.sh
jet
kingset
kingset.pub
lookup
my.cnf
myenv
netbank
new p
new-p-group
newww
odinwork
pharmalink
phl
phl2
privatekey
privatekey.pub
prototype
react-app
repos
ronhelp
rte2
setwork
sorting_algorithms
sqlalchemy-env
stock-lookup
test
tests
the
tri
untitled folder
web01
websites
work
zero_day
mac@makito ~ % cd Development
mac@makito Development % ls
flutter		projects
mac@makito Development % cd flutter
mac@makito flutter % ls
AUTHORS			PATENT_GRANT		docs
CHANGELOG.md		README.md		engine
CODEOWNERS		TESTOWNERS		examples
CODE_OF_CONDUCT.md	analysis_options.yaml	flutter_console.bat
CONTRIBUTING.md		bin			flutter_root.iml
DEPS			dartdoc_options.yaml	packages
LICENSE			dev			version
mac@makito flutter % cd bin
mac@makito bin % pwd
/Users/mac/Development/flutter/bin
mac@makito bin % cd..
zsh: command not found: cd..
mac@makito bin % cd ..
mac@makito flutter % d ..
zsh: command not found: d
mac@makito flutter % cd ..
mac@makito Development % cd ..
mac@makito ~ % ls
-summative_assessment_one_group9
AirBnB_clone_v2
AirBnB_clone_v3
AirBnB_clone_v4
AppDataRoamingPythonScriptsfab-script.py
Applications
Betty
CascadeProjects
Desktop
Development
Documents
Downloads
Dropbox
Library
Movies
Music
OpenSSH_8.1p1,
Pictures
Public
PycharmProjects
SparseMatrix
Stock-metrics
Untitled Project
Vagrantfile
VirtualBox VMs
WebstormProjects
ai_completion
alu-AirBnB_clone
alu-back-end
alu-interview
alu-scripting
alu-system_engineering-devops
alu-web-development
alu-web_front_end
alu-webstack
alx-higher_level_programming
alx-low_level_programming
alx-system_engineering-devops
bank
banking
bans
bk
card
chat
debug1:
document
document.pub
fatal:
fil
group-9-project
install.sh
jet
kingset
kingset.pub
lookup
my.cnf
myenv
netbank
new p
new-p-group
newww
odinwork
pharmalink
phl
phl2
privatekey
privatekey.pub
prototype
react-app
repos
ronhelp
rte2
setwork
sorting_algorithms
sqlalchemy-env
stock-lookup
test
tests
the
tri
untitled folder
web01
websites
work
zero_day
mac@makito ~ % vi .zshrc
mac@makito ~ % source ~/.zshrc

mac@makito ~ % cd Development
mac@makito Development % ls
flutter		projects
mac@makito Development % cd projects
mac@makito projects % ls
your_app_name
mac@makito projects % rename setAppName --targets ios,android --value "m.okoye_FirstFlutterProject"

Targets: [ios, android]
Value: m.okoye_FirstFlutterProject
┌───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────
│ #0   main (file:///Users/mac/.pub-cache/hosted/pub.dev/rename-3.1.0/bin/rename.dart:28:12)
│ #1   <asynchronous suspension>
├┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄
│ ⛔ CustomException: Missing build script: Could not find 'build.gradle' (Groovy) or 'build.gradle.kts' (Kotlin DSL) in the android/app directory.
└───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────
mac@makito projects % ls
your_app_name
mac@makito projects % mv your_app_name m.okoye_FirstFlutterProject
mac@makito projects % ls
m.okoye_FirstFlutterProject
mac@makito projects %  git clone https://github.com/Ronnie5562/alu-machine_learning.git
Cloning into 'alu-machine_learning'...
remote: Enumerating objects: 848, done.
remote: Counting objects: 100% (848/848), done.
remote: Compressing objects: 100% (457/457), done.
remote: Total 848 (delta 341), reused 836 (delta 329), pack-reused 0 (from 0)
Receiving objects: 100% (848/848), 14.53 MiB | 2.10 MiB/s, done.
Resolving deltas: 100% (341/341), done.
mac@makito projects % ls
alu-machine_learning		m.okoye_FirstFlutterProject
mac@makito projects % rm -rf alu-machine_learning
mac@makito projects % ls
m.okoye_FirstFlutterProject
mac@makito projects % cd ..
mac@makito Development % cd ..
mac@makito ~ % git clone https://github.com/Ronnie5562/alu-machine_learning.git
Cloning into 'alu-machine_learning'...
remote: Enumerating objects: 848, done.
remote: Counting objects: 100% (848/848), done.
remote: Compressing objects: 100% (457/457), done.
remote: Total 848 (delta 341), reused 836 (delta 329), pack-reused 0 (from 0)
Receiving objects: 100% (848/848), 14.53 MiB | 1.52 MiB/s, done.
Resolving deltas: 100% (341/341), done.
mac@makito ~ % cd alu-machine_learning
mac@makito alu-machine_learning % ls
README.md		math			supervised_learning
mac@makito alu-machine_learning % vi README.md

# ALU Machine Learning

![img](https://start.alueducation.com/resource/1568810909000/AluLogoForAdmissions)


# Author

## [`makuochi okoye`](linkedin.com/in/makuochi-okoye-32a385206/)
~                          
