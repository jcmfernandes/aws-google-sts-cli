# aws-google-sts-cli

## Description

AWS IAM credentials from STS with your Google account made easy!

## Installation

```
$ sudo bash -c "curl -o /usr/local/bin/aws-google-sts-cli https://raw.githubusercontent.com/jcmfernandes/aws-google-sts-cli/master/aws-google-sts-cli && chmod +x /usr/local/bin/aws-google-sts-cli"
```

## Requirements

* Ruby >= 2.4
* geckodriver (if you use Firefox)
* ChromeDriver (if you use Chrome)

## Usage

```
$ aws-google-sts-cli --help
Usage: aws-google-sts-cli [options]
        --browser BROWSER            The browser (chrome or firefox)
        --browser-profile [BROWSER_PROFILE]
                                     The browser profile (firefox default: default / chrome default: your OS default)
        --idpid IDPID                The SAML IDPID
        --spid SPID                  The SAML SPID
        --aws-region AWS_REGION      The AWS region
        --aws-arn AWS_ARN            The AWS ARN (performs a partial match)
        --aws-cli-profile [AWS_CLI_PROFILE]
                                     The AWS CLI profile (default: default)
        --google-email [GOOLE_EMAIL] The google email, necessary when you have multiple accounts
    -h, --help                       Prints this help
```
