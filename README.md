# AWS Lambda@Edge Repository

> Test repository for AWS Lambda@Edge Functions using AWS Lambda + AWS Cloudfront

### Why use Lambda@Edge?

- **Speed**: Take advantage of CloudFront's reduction in latency.

- **Cost**: Consolidate requests and removes transfer out fees from AWS origins.

- **Security**: Improved security from DDOS attacks through AWS Standard Shield.

### Lambda@Edge Use Cases

With Lambda@Edge, you can build a variety of solutions, for example:

- Inspect cookies to rewrite URLs to different versions of a site for A/B testing.

- Send different objects to your users based on the User-Agent header, which contains information about the device that submitted the request. For example, you can send images in different resolutions to users based on their devices.

- Inspect headers or authorized tokens, inserting a corresponding header and allowing access control before forwarding a request to the origin.

- Add, delete, and modify headers, and rewrite the URL path to direct users to different objects in the cache.

- Generate new HTTP responses to do things like redirect unauthenticated users to login pages, or create and deliver static webpages right from the edge. For more information, see Using Lambda functions to generate HTTP responses to viewer and origin requests in the Amazon CloudFront Developer Guide.

### Resources

- [Lambda - Lambda@Edge Docs](https://docs.aws.amazon.com/lambda/latest/dg/lambda-edge.html)
- [CloudFront - Lambda@Edge Docs](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/lambda-at-the-edge.html)
- [Example Lambda Functions](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/lambda-examples.html)