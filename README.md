## Solution details:

1. Run docker-compose.yml to add API_KEY to enviornmemt variable. We can also take off key value from docker-compose file and give the value while running 'docker-compose run -e API_KEY=*****'
2. I tried to provide a good experience but I didn't add advanced UI experience since I am not a Front end expert.
3. For ideal production ready code, json files should like on a cloud location like S3 or google drive. I don't have resources to support that on my home machine.
 I will use Boto3 to connect to S3 bucket and access files
