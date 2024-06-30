# Deploy different web apps on AWS
My midterm seminar in NT208 - Web-Based Application Development subject.
## Scenarios
3 scenarios:
- scenario 1: Deploy a web-backend server connected to a database
- scenario 2: Deploy a serverless full-stack web app
- scenario 3: Deploy a serverless microservice web-backend
### Scenario 1 - Deploy a web-backend server connected to a database

#### Architecture
![image](https://github.com/PNg-HA/Deploy-different-web-app-on-AWS/assets/93396414/bd1647b6-d0d8-4c02-b8d0-2934ddde6546)
#### Step 1 - Launch an EC2 instance
![image](https://github.com/PNg-HA/Deploy-different-web-app-on-AWS/assets/93396414/22f889dd-4082-4eb9-9bef-7c9aa3dffdd7)

#### Step 2 - Create an Amazon RDS DB instance
![image](https://github.com/PNg-HA/Deploy-different-web-app-on-AWS/assets/93396414/32672efb-d069-4eee-b254-40078c171094)
![image](https://github.com/PNg-HA/Deploy-different-web-app-on-AWS/assets/93396414/0bdc31e6-76ad-472c-8523-511448096bb3)

![image](https://github.com/PNg-HA/Deploy-different-web-app-on-AWS/assets/93396414/f5377623-b85d-4dd9-970f-8b33dc9b5c16)
![image](https://github.com/PNg-HA/Deploy-different-web-app-on-AWS/assets/93396414/99fa5146-fe90-4fb6-bd1b-9d135f1abeae)
#### Step 3 - Deploy a web-backend server connected to a DB

Source code: [SamplePage.php](SamplePage.php), [dbinfo.inc](dbinfo.inc)
Demo:
![image](https://github.com/PNg-HA/Deploy-different-web-app-on-AWS/assets/93396414/30bd96d4-19f9-4755-baee-cff39d06b1b2)

### Scenario 2 - Deploy a serverless full-stack web app
#### Architecture
![image](https://github.com/PNg-HA/Deploy-different-web-apps-on-AWS/assets/93396414/ffad6aa4-9bb9-4f91-b133-b2096717a901)

#### AWS Amplify involved:
Source code: [index.html](index.html)
##### AWS API Gateway involved
![image](https://github.com/PNg-HA/Deploy-different-web-app-on-AWS/assets/93396414/9360b1af-90a5-4e6f-90f4-3745697f77d4)
#### AWS Lambda function
![image](https://github.com/PNg-HA/Deploy-different-web-app-on-AWS/assets/93396414/fc94c1f0-6e0a-4f73-92c9-04f290c4bbbb)
#### ACM involved
![image](https://github.com/PNg-HA/Deploy-different-web-app-on-AWS/assets/93396414/19950559-1f4f-4a5e-b56a-2028d671c808)
#### AWS Route 53
Configure NS:
![image](https://github.com/PNg-HA/Deploy-different-web-app-on-AWS/assets/93396414/4eea5e3f-1fe3-4088-af2e-21df9ed51c1d)
#### Demo
![image](https://github.com/PNg-HA/Deploy-different-web-app-on-AWS/assets/93396414/c6124683-1554-481c-8bf2-755c420c8b6b)

### Scenario 3 - Deploy a serverless microservice web-backend
#### Architecture
![image](https://github.com/PNg-HA/Deploy-different-web-app-on-AWS/assets/93396414/42615f3d-1269-4697-a7d7-af5c08516142)
#### Execution
Source code backend: https://github.com/Sanjeev-Thiyagarajan/ecs-project2/tree/main
![image](https://github.com/PNg-HA/Deploy-different-web-app-on-AWS/assets/93396414/13de81bc-d805-4fe6-a4b8-fdb9d3e9f3f2)
![image](https://github.com/PNg-HA/Deploy-different-web-app-on-AWS/assets/93396414/7a1f5cc7-09dc-426d-974d-586fa27937f1)
![image](https://github.com/PNg-HA/Deploy-different-web-app-on-AWS/assets/93396414/69ac2949-27d9-42ca-975c-46fa3f6cd288)

#### Demo
![image](https://github.com/PNg-HA/Deploy-different-web-app-on-AWS/assets/93396414/98f09258-b531-4fc6-8884-ed0f4b1c28ff)





