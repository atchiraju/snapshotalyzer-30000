# snapshotalyzer-30000
A demo project to manage AWS EC2 instance snapshots

##About

This project is a demo and uses boto3 to manage AWS EC2 instance snapshots.

##Configure

shotty uses the config file created by the AWS cli.e.g.

`aws Configure --profile shotty`

##Running

`pipenv run python shotty/shotty.py <command> <subcommand> <--project=PROJECT>`

*command* is instances,volumes or snapshots
*subcommand* -depends on command
*project* is optional
