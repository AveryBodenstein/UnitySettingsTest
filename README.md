# UnitySettingsTest
Testing Unity settings for github integration

Current Settings:
- .gitignore: Unity (edited)
	- added windows and mac ignore files
	- added condensation for unity generated diffs
- Unity -> project settings -> editor
	- version control: 	Visible meta files
	- asset serialization:	force text
- git LFS
	- ensure machines have Git installed (not sufficient to have github desktop or sourcetree)
	- download and install git-lfs
	- open git bash and: "git lfs install"
		- need to do this per repo
	- add .gitattributes file to tell lfs which files are large
- .gitattributes: (From thoughtbot.com)