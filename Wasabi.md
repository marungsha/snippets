=> aws configure
access_key => 
access_secret => 
default => region
output => json

aws --endpoint-url=https://s3.eu-central-1.wasabisys.com s3 ls
aws --endpoint-url=https://s3.eu-central-1.wasabisys.com s3 cp /usr/local/lsws/classroom/sdgs-backup.tar.gz  s3://sdgs/27-04-2021-backup.tar.gz