# target platform

target will be referred from xxx.configuration project with group id and artifact id
tycho plugin work principal is that will find ${artifactId}.target in this project, 
to work with multiple eclipse targets, symbel link is used here, popular eclipse target platform version 
are list here and then create one symbel link file name as ${artifact}.target point to target defination file

under Win 10,
mklink -D target source
linux ln 