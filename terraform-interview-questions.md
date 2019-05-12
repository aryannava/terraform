# You are testing out a new environment and need to ensure you are using the right syntax to reference resources. What are two commands that can help you discover and test the correct interpolation syntax?

– terraform console
– terraform show

# How would name a Docker image resource for reference later?
– resources “docker_image”

How do you specify the location of the module you are referencing in the root/main.tf file?
– source = “./modulename”

# You need to deploy a development and a production environment simultaneously on the same machine. What feature of Terraform allows you to deploy multiple environments with independent states?
– workspace

# You are writing a Terraform script to deploy Docker containers for your organization. You have several items to deploy, what word does Terraform use to refer to each item it deploys?
– Resources

# If you change the port of a Docker container in your Terraform script and run a “terraform apply”, what will happen to your deployment?
– The old resource is destroyed and the new one takes its place.

You are referencing infrastructure in an output file. In this resource: “resource “docker_image” “ghost””, which string is the resource ID?
– ghost

# You need to be able to specify different variable definitions based on whether the environment is a production or development area. What type of variables rely on key-value pairs in order to be defined dynamically based on other provided information?
– Maps

# You are trying to search your system for the file that contains all of your variable definitions. The previous admin has lost it. What extension does the file that holds your variable definitions have?
– .tfvars

# Which of the following is an accurate use description for Terraform?
– Terraform is used for building, changing, and versioning infrastructure with safely and efficiently.

# You need to output the IP address of your docker container with ID “container_id” in order to provide access to your coworkers. How would you script this output value?
– value = “${docker_container.container_id.ip_address}”

# Which provisioner should you use to run a command on the Terraform server during deployment?
– local-exec

# At your company, you need to provide a deployment with variables that are defined interactively when applying. For the “image” variable, you want to ensure the user knows this refers to the name of the image. How would you word this in your variable block?
– description = “name of the image”

# You are trying to decide how to define your variables. What are three common files in which you can specify the value of a variable without having to use a function to extract them? (Choose all that apply)

– variables.tf
– main.tf
– terraform.tfvars

# You have a variable that changes often and you want the ability to modify it during your Terraform apply, either via an external file or by entering it interactively. How should this variable be expressed in the variables.tf file?
– variable “image” {}

The best place to learn Terraform is :Linux Academy
