# Udagram Project

- This is an automated script that helps in the deployment of an application on the AWS server.
- This was a solo project. The project uses yaml and json files.
- The diagram below is a visual representation of the network infrastructure that has been translated into code.

![networking infrastructure](https://user-images.githubusercontent.com/24241962/212282009-79de0f9b-992b-4f30-ac2b-674ca01bbeb8.png)

## Project Url

- http://udagr-WebAp-1SH3I0U3THDTD-1870726708.us-east-1.elb.amazonaws.com

## Getting Started

- Create an IAM Role.
- Cd into the project folder.
- Configure it locally on your machine using the keys provide.
- Run
  ```sh
    aws configure
  ```
  to set up your Iam keys locally.
- Run the create script
  ```sh
      ./create.sh udagram-project-server server-config.yml server-config.json
  ```
