# Security

If you discover a potential security issue in this project, we ask that you notify AWS Security via our [vulnerability reporting page](http://aws.amazon.com/security/vulnerability-reporting/). Please do **not** create a public GitHub issue.

## Reporting Security Issues

**Please do not report security vulnerabilities through public GitHub issues.**

Instead, please report them to the AWS Security team. You can do this by:

1. Visiting the [AWS Vulnerability Reporting page](http://aws.amazon.com/security/vulnerability-reporting/)
2. Following the instructions to submit your report

Please include the following information in your report (as much as you can provide):

* Type of issue (e.g., buffer overflow, SQL injection, cross-site scripting, etc.)
* Full paths of source file(s) related to the manifestation of the issue
* The location of the affected source code (tag/branch/commit or direct URL)
* Any special configuration required to reproduce the issue
* Step-by-step instructions to reproduce the issue
* Proof-of-concept or exploit code (if possible)
* Impact of the issue, including how an attacker might exploit the issue

This information will help us triage your report more quickly.

## Security Best Practices

When using this sample code:

1. **Never commit credentials** - Use AWS Secrets Manager or Systems Manager Parameter Store for sensitive values
2. **Review IAM permissions** - Follow the principle of least privilege for all IAM roles
3. **Enable logging** - Configure CloudWatch Logs for Lambda@Edge functions
4. **Use HTTPS** - Always use HTTPS for production deployments
5. **Rotate secrets** - Regularly rotate OAuth client secrets and other credentials
6. **Monitor authentication** - Set up CloudWatch alarms for authentication failures
7. **Keep dependencies updated** - Regularly update npm packages and CDK versions
8. **Review security groups** - Ensure proper network isolation
9. **Enable encryption** - Use encryption at rest and in transit for all data
10. **Test security controls** - Regularly test your authentication and authorization mechanisms

## Preferred Languages

We prefer all communications to be in English.
