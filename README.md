To contribute:
	- Go to the 'Issues' tab, read an issue and then assign yourself to it

Modding files:
	- DO NOT TOUCH COMMON FILES WITHOUT BEING ASSIGNED TO AN ISSUE THAT NEEDS TO MODIFY IT !!!!!
		- This means files that start with 00_/01_ etc. or files that have a unique job such as map\supply_nodes.txt
	- To add a file that is not currently in the mod, copy it from your Hearts of Iron IV folder and make sure the folder structure matches exactly in the mod
		- e.g. common\decisions\categories\ENG_decision_categories.txt
	- When adding something new, make sure to prefix it with MS_ and keep it separate from vanilla files
		- e.g. A script file for effects relating to the Pacific war should be called MS_pacific_war_scripting.txt
		- If it must stay in the same file - e.g. national focuses - prefix it with MS_ too; A new focus in the Japanese national focus tree should have the key MS_JAP_naval_focus
	- When overriding a define from common/defines, follow the namespace structure of the define and add the original value as a comment
		- e.g. overriding the output of a military factory would look like this in the file:
			NDefines.NProduction.BASE_FACTORY_SPEED_MIL = 4 -- 3.5