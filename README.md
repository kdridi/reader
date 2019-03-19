# Reader

## Server

### AWS Configuration

- Go to the [AWS console](http://console.aws.amazon.com)
- Select the [IAM service](https://console.aws.amazon.com/iam/)
- Create a new User _serverless-admin_ with a _Programmatic access_ and attach _AdministratorAccess_ policy

### AWS Deployment

```bash
npm run server-deploy
```