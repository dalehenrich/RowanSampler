# RowanSampler

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
		useSsh: useSsh  | useSsh |
	useSsh := true.	"set to false to clone using https:"
	Rowan projectTools clone
		cloneSpecUrl:
			'https://raw.githubusercontent.com/dalehenrich/RowanSample1/master/specs/RowanSample1.ston'
		gitRootPath: '$GS_HOME/shared/repos/'
		useSsh: useSsh
```
