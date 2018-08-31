# snapshotalyzer
Demoproject to manage AWS resources and snapshots

## about
This is a project that uses boto3 to manage AWS EC2 instances snapshots

## configuring
admin uses the configuration file created by AWS cli e.g.
   
    aws configure --profile admin

## running
pipenv run python admin/admin.py <command> <subcommand> <--project=PROJECT>

*command* is instances, volumes or snapshots
*subcommand*  depends on command
*project* is optional
