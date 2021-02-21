# aws-codecommit
1)Go to the codecommit service in the aws account
2)create a repo with a user name.
3)create a user with codecommitfull access policy.
4)generate the HTTPS Git credentials for AWS CodeCommit and store in anywhere you want
5)then goto the aws code commit repo and copy the https url from there.
6)open command promt and intilize git there(git version should be 1.7 or more)
7)use git clone with awscodecommit https url
8)it will ask for username and password to clone the repo.
9)submit the credential which you are stored before.
10)then it will clone the repository.
11)if you want to any make changes do it and push back to the aws codecommit repo.
