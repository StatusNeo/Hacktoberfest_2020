<h1 align="center">HashiCorp Terraform<h1>

<p align="center">
  <img src="/blogs/img/Terraform/Terraform_logo.png" height=300 width=700>
</p>

## What is Terraform used for?
HashiCorp terraform is widely used as an **Infrastructure as a code** tool. 
Infrastructure as a code refers to the process of developing configuration files, in a machine-readable format, to manage the infrastructure rather than doing it manually. 
Terraform uses **HCL (Hashicorp Configuration Language)** for the same. These files can be used to interact with providers such as AWS, GitHub, GCP, Docker.
<br><br>Let us take a look at how we can create a simple HCL file for interacting with AWS (Amazon Web Services) to create an EC2 instance.
<br><br>
**Note: The pre-requisite for this tutorial is having an AWS account with a valid IAM user.**
<br><br>

## Creating an AWS EC2 instance using Terraform

<p>1. Downloading Terraform: To download terraform, go to the website: https://www.terraform.io/downloads.html
  <p align="center">
    <img src="/blogs/img/Terraform/Terraform1.PNG">
  </p>
  Download the file as per your OS. In my case, it is Windows x64. Now extract the downloaded zip file at the desired location.
</p>
<br>

<p>2. Open command prompt and navigate to the folder where the extracted file is placed and run the command <b>terraform init</b>.
  <p align="center">
    <img src="/blogs/img/Terraform/terraform2.PNG">
  </p>
  This command initializes the working directory. Now we are ready to write the configuration file.
  <br>
  <b>Note: The configuration file will require the access key and secret key of the IAM user.<br>
  For more information about IAM users click <a href="https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html">here.</a></b>
</p>
<br>

<p>3. Now make a new file in the same directory and write the following code (The extension for the configuration file should be <b>.tf</b>).
  <p align="center">
    <img src="/blogs/img/Terraform/Terraform3.PNG">
  </p>
  The above code will create the specified ami instance named <b>instance1</b> of type <b>t2.micro</b> for the user whose access key and secret key are provided. 
  Since we are interacting with AWS so we have kept our provider as <b>aws</b> and the resource being interacted with is <b>aws_instance</b>.
</p>
<br>

<p>4. Now save the file and run the <b>terraform init</b> command again. You will get the following output.
  <p align="center">
    <img src="/blogs/img/Terraform/Terraform4.PNG">
  </p>
</p>
<br>

<p>5. Run the command  <b>terraform plan</b> to see the execution plan.
  <p align="center">
    <img src="/blogs/img/Terraform/Terraform5.PNG">
  </p>
  This will have the details of the changes that will be taking place.
  The output will be similar to:
  <p align="center">
    <img src="/blogs/img/Terraform/Terraform6.PNG">
  </p>
</p>
<br>

<p>6. Now run the command <b>terraform apply</b> to apply the changes that are listed above.
  <p align="center">
    <img src="/blogs/img/Terraform/Terraform7.PNG">
  </p>
  The changes being applied will be listed and in the end you will get a similar message displayed on the console:
  <p align="center">
    <img src="/blogs/img/Terraform/Terraform8.PNG">
  </p>
</p>
<br>

<p>7. Now the instance will be in the running state. You can verify it on the AWS console.
  <p align="center">
    <img src="/blogs/img/Terraform/Terraform9.PNG">
  </p>
</p>
<br>

<p>8. You can destroy this instance by simply running a command <b>terraform destroy</b> as follows:
  <p align="center">
    <img src="/blogs/img/Terraform/Terraform10.PNG">
  </p>
  The message that will be displayed on your console after successful execution of the above command will be as follows:
  <p align="center">
    <img src="/blogs/img/Terraform/Terraform11.PNG">
  </p>
  Now the instance is destroyed. You can verify it by having a look at the AWS console.
</p>
<br>

By following these simple steps you can create <b>n</b> number of resources by just specifying them in a single file.
