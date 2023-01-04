
#### Screenshot  

#### rds 
  <img width="1440" alt="‏لقطة الشاشة ١٤٤٤-٠٦-١١ في ١٠ ٠٢ ٥٩ م" src="https://user-images.githubusercontent.com/56774274/210631005-c304d4cc-2055-40f6-8411-963a1f5241e0.png">

  
  
#### s3
<img width="1440" alt="‏لقطة الشاشة ١٤٤٤-٠٦-١١ في ١٠ ٠١ ٥١ م" src="https://user-images.githubusercontent.com/56774274/210630374-e8aed2a3-5dda-47a4-9a35-3268bc816bd5.png">
  
  

<img width="1440" alt="‏لقطة الشاشة ١٤٤٤-٠٦-١١ في ١٠ ٠٨ ٠٠ م" src="https://user-images.githubusercontent.com/56774274/210630930-f107d08a-1918-44bc-9569-7d3bac1e0750.png">
  
<img width="1440" alt="‏لقطة الشاشة ١٤٤٤-٠٦-١١ في ١٠ ٠٢ ٠٢ م" src="https://user-images.githubusercontent.com/56774274/210630964-09ba16a4-afea-4664-a0ed-6b6c9ceb498a.png">


http://udagrambucketudacity.s3-website.ap-south-1.amazonaws.com 

#### EB 
 <img width="1440" alt="‏لقطة الشاشة ١٤٤٤-٠٦-١١ في ١٠ ٠٣ ٢٨ م" src="https://user-images.githubusercontent.com/56774274/210631045-3be8f6cd-e589-4a81-bd62-11c26d712567.png">

## enviroment
  <img width="1440" alt="‏لقطة الشاشة ١٤٤٤-٠٦-١١ في ١٠ ١٠ ٥٠ م" src="https://user-images.githubusercontent.com/56774274/210631350-d9c060b9-9800-4e6b-89ce-339c38f13442.png">

>>>>>>> 603f3b64b215dc24c118f917a153c78b78252321






#### circleci

<img width="1440" alt="‏لقطة الشاشة ١٤٤٤-٠٦-١١ في ١٠ ٢١ ٣٧ م" src="https://user-images.githubusercontent.com/56774274/210633433-6f206e11-5060-46e8-b524-b6d334ef112e.png">
<img width="1440" alt="‏لقطة الشاشة ١٤٤٤-٠٦-١١ في ١٠ ٢١ ٣٢ م" src="https://user-images.githubusercontent.com/56774274/210633445-0602ecc6-1435-4c23-9627-1022b8f2b430.png">
<img width="1440" alt="‏لقطة الشاشة ١٤٤٤-٠٦-١١ في ١٠ ٢١ ٢٥ م" src="https://user-images.githubusercontent.com/56774274/210633450-292b6b00-a16e-4b95-bf9e-b1cf8b512592.png">
<img width="1440" alt="‏لقطة الشاشة ١٤٤٤-٠٦-١١ في ١٠ ٢١ ٢٠ م" src="https://user-images.githubusercontent.com/56774274/210633455-52972a88-f7e4-4788-963e-363d7b654455.png">
<img width="1440" alt="‏لقطة الشاشة ١٤٤٤-٠٦-١١ في ١٠ ٢١ ١٢ م" src="https://user-images.githubusercontent.com/56774274/210633463-1e9c8a9a-f7d7-4cda-b9db-6b582579c4af.png">
<img width="1440" alt="‏لقطة الشاشة ١٤٤٤-٠٦-١١ في ١٠ ٢١ ٠٥ م" src="https://user-images.githubusercontent.com/56774274/210633467-c85f2525-8cc2-442e-8e2d-a071f7e3752a.png">
<img width="1440" alt="‏لقطة الشاشة ١٤٤٤-٠٦-١١ في ١٠ ٢٠ ٥٧ م" src="https://user-images.githubusercontent.com/56774274/210633470-d0a189e2-9ea8-40b3-9880-5ee309a2efd9.png">
<img width="1440" alt="‏لقطة الشاشة ١٤٤٤-٠٦-١١ في ١٠ ٢٠ ٤٨ م" src="https://user-images.githubusercontent.com/56774274/210633479-328bc0f0-4544-4f4a-88da-23567f87d60d.png">




# Hosting a Full-Stack Application

### **You can use you own project completed in previous courses or use the provided Udagram app for completing this final project.**

---

In this project you will learn how to take a newly developed Full-Stack application built for a retailer and deploy it to a cloud service provider so that it is available to customers. You will use the aws console to start and configure the services the application needs such as a database to store product information and a web server allowing the site to be discovered by potential customers. You will modify your package.json scripts and replace hard coded secrets with environment variables in your code.

After the initial setup, you will learn to interact with the services you started on aws and will deploy manually the application a first time to it. As you get more familiar with the services and interact with them through a CLI, you will gradually understand all the moving parts.

You will then register for a free account on CircleCi and connect your Github account to it. Based on the manual steps used to deploy the app, you will write a config.yml file that will make the process reproducible in CircleCi. You will set up the process to be executed automatically based when code is pushed on the main Github branch.

The project will also include writing documentation and runbooks covering the operations of the deployment process. Those runbooks will serve as a way to communicate with future developers and anybody involved in diagnosing outages of the Full-Stack application.

# Udagram

This application is provided to you as an alternative starter project if you do not wish to host your own code done in the previous courses of this nanodegree. The udagram application is a fairly simple application that includes all the major components of a Full-Stack web application.



### Dependencies

```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

### Installation

Provision the necessary AWS services needed for running the application:

1. In AWS, provision a publicly available RDS database running Postgres. <Place holder for link to classroom article>
1. In AWS, provision a s3 bucket for hosting the uploaded files. <Place holder for tlink to classroom article>
1. Export the ENV variables needed or use a package like [dotnev](https://www.npmjs.com/package/dotenv)/.
1. From the root of the repo, navigate udagram-api folder `cd starter/udagram-api` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run dev`.
1. Without closing the terminal in step 1, navigate to the udagram-frontend `cd starter/udagram-frontend` to intall the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License

[License](LICENSE.txt)
<<<<<<< HEAD
=======


