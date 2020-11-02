# aws-sam
AWS SAM template for Serverless Application using Lambda
Default SAM template doesn't provide an easy way to have more control on resources like Name, StageName, Logging/Tracing configuration, VPC Configuration
LambdaVPC/lambdavpc.yml - This template may answer few questions to have more control over resources.

API Gateway:
1. StageName
2. Logging Configuration
3. Tracing
4. Resource Policy
5. Authentication/Authorization

Lambda:
1. Configuration for VPC
2. Configuration for Events and their paths
