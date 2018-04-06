# RowanSampler

## file: RowanSample1
File url for the https://github.com/dalehenrich/RowanSample1 project (assuming RowanSampler has been cloned to disk):
```
file:/home/dhenrich/rogue/_homes/rogue/_home/shared/repos/RowanSampler/specs/RowanSample1.ston
```
Use the url in the `prj list` to create a new github project, or execute the following expressions to clone and load the project:
```Smalltalk
| useSsh |
useSsh := true.	"set to false to clone using https:"
Rowan projectTools clone
	cloneSpecUrl:
		file:/home/dhenrich/rogue/_homes/rogue/_home/shared/repos/RowanSampler/specs/RowanSample1.ston'
	gitRootPath: '$GS_HOME/shared/repos/'
	useSsh: useSsh.
Rowan projectTools load loadProjectNamed: 'RowanSample1'
```

## https:// RowanSample1
Url for the https://github.com/dalehenrich/RowanSample1 project:
```
https://raw.githubusercontent.com/dalehenrich/RowanSample1/master/specs/RowanSample1.ston
```
Use the url in the `prj list` to create a new github project, or execute the following expressions to clone and load the project:
```Smalltalk
| useSsh |
useSsh := true.	"set to false to clone using https:"
Rowan projectTools clone
	cloneSpecUrl:
		'https://raw.githubusercontent.com/dalehenrich/RowanSample1/master/specs/RowanSample1.ston'
	gitRootPath: '$GS_HOME/shared/repos/'
	useSsh: useSsh.
Rowan projectTools load loadProjectNamed: 'RowanSample1'
```
