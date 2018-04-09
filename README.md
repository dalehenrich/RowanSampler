# RowanSampler

## file: Rowan, RowanSample1, and RowanSample2
```
file:/home/dhenrich/rogue/_homes/rogue/_home/shared/repos/RowanSampler/specs/RowanSample1.ston
file:/home/dhenrich/rogue/_homes/rogue/_home/shared/repos/RowanSampler/specs/RowanSample2.ston
file:/home/dhenrich/rogue/_homes/rogue/_home/shared/repos/RowanSampler/specs/Rowan.ston
```
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
		'file:/home/dhenrich/rogue/_homes/rogue/_home/shared/repos/RowanSampler/specs/RowanSample1.ston'
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

## config creation code for RowanSample1
Execute the following after the RowanSample1 has been cloned (not necessary to load the project before exporting config):
```smalltalk
((RwProjectConfiguration newNamed: 'Default' for: 'RowanSample1')
		comment:
				'standard config for RowanSample1. The BaselineOfRowanSample1 package should not be loaded.';
		addConfig: 'RowanSample1-Core';
		addConfig: 'RowanSample1-Extensions';
		addConfig: 'RowanSample1-Tests';
		addConfig: 'RowanSample1-XXX';
		yourself) export
```
