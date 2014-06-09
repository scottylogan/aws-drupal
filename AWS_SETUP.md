# Local Environment Setup

### This assumes you’re using a Mac running a recent version of OS X.  If not, go get one.

Install the AWS CLI and Elastic Beanstalk CLI from [https://aws.amazon.com/tools/]

Be sure to copy the AWSDevTools directory (from the AWS CLI download) to ~/.local/lib

Setup the directories to store credentials:

    % mkdir ~/.ec2 ~/.aws

Save your AWS Identity Key in `~/.ec2/access_key`
Save your AWS Secret Key in `~/.ec2/secret_key`

If you don't know your AWS Secret Key, create a new Access Key at
[https://console.aws.amazon.com/iam/home?#security_credential]

Create `~/.ec2/aws-credentials` with this content

    AWSAccessKeyId=YOUR-ACCESS-KEY-ID
    AWSSecretKey=YOUR-SECRET-KEY

Create `~/.aws/config` with this content:

    [default]
    aws_access_key_id = YOUR-ACCESS-KEY-ID
    aws_secret_key = YOUR-SECRET-KEY
    region = us-west-2

Pick up configuration pieces from [https://github.com/scottylogan/dotfiles]




