# Getting Started with Travis CI Explain

## sudo: required

This means that this config file is needed root access with 'sudo'.

## language: generic

This config file is use many language, but if you sure, you can use instead 'generic' with 'language: python'.

## services:
## - docker

This means that this code build process is use docker.

## before_install:
##  - docker build -t myatminsoe/docker-react -f Dockerfile.dev .

This config call docker build process and "-f" stand for name of Dockerfile config. Ofcourse, if you use name in Dockerfile only you may not use '-f' flag.

## provider: elasticbeanstalk

This config is stand to use AWS Elastic BeanStalk Service. Then the deploy process is install beanstalk SDK.

## bucket_path: 'react-app'

This config is means that the path of s3 bucket. The deploy process is copy the hole directory of source code into the s3 bucket. So you should use the name of bucket path is "the directory name of source code".




***********If you ask any question, you caan contact through "ethan.mms01@gmail.com"*************
