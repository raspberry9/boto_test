# boto_test
Testing boto3

### Installation

```
$ virtualenv -p python3.8 env
$ source env/bin/actiivate
$ pip install -r requrements.txt
```

### Configuration

```
$ sudo apt install awscli
$ aws configure

# https://console.aws.amazon.com/iam/home?region=ap-northeast-2#/users
# 위의 페이지에서 [사용자 추가] > [엑세스 유형: 프로그래밍 방식 엑세스]
AWS Access Key ID [None]: 위에서 만든 id
AWS Secret Access Key [None]: 위에서 만든 secret access key
Default region name [None]: ap-northeast-2
Default output format [None]: json
```
