# SnapshotAnalyser
Demo to manage EC2 Instances

##About
This project is a demo, an uses boto3 to manage AWS EC2 instance snapshots.

##Configuring
shoty uses the configuration file created by the AWS cli. e.g

`aws configure --profile shotty`

##Running

`pipenv run python "shotty\shoty.py <command><subcommand><--project=PROJECT"`
*command* is instances, volumes or snapshots
*subcommand" depends on command
*project* is optional
