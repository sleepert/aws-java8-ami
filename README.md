# aws-java8-ami

Use packer to create an AMI with java 8 runtime pre-installed

## Usage
Ensure that you have an IAM user with full access to EC2

put user access keys into your environment variables

```
export AWS_ACCESS_KEY_ID=xxx
export AWS_SECRET_ACCESS_KEY=xxxxxx
```

run the command
```
packer build packer.json
```
