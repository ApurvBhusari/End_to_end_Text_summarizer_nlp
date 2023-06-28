# End to end Text-Summarizer-Project

## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update entity
4. Update the configuration manager in src config
5. update the conponents
6. update the pipeline
7. update the main.py
8. update the app.py


# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/ApurvBhusari/End_to_end_Text_summarizer_nlp.git
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n gpu_python_3.8 python=3.8 -y
```

```bash
conda activate gpu_python_3.8
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```


```bash
Author: Apurv Bhusari
Data Scientist
Email: apurvabhusari@gmail.com

```



# AWS-CICD-Deployment-with-Github-Actions

## 1. Login to AWS console.

## 2. Create IAM user for deployment

	#with specific access

	1. EC2 access : It is virtual machine

	2. ECR: Elastic Container registry to save your docker image in aws


	#Description: About the deployment

	1. Build docker image of the source code

	2. Push your docker image to ECR

	3. Launch Your EC2 

	4. Pull Your image from ECR in EC2

	5. Lauch your docker image in EC2

	#Policy:

	1. AmazonEC2ContainerRegistryFullAccess

	2. AmazonEC2FullAccess

	
## 3. Create ECR repo to store/save docker image
    - Save the URI: 963419612467.dkr.ecr.ap-south-1.amazonaws.com/text_sum

	
## 4. Create EC2 machine (Ubuntu) 

## 5. Open EC2 and Install docker in EC2 Machine:
	
	
	#optinal

	sudo apt-get update -y

	sudo apt-get upgrade
	
	#required

	curl -fsSL https://get.docker.com -o get-docker.sh

	sudo sh get-docker.sh

	sudo usermod -aG docker ubuntu

	newgrp docker
	
# 6. Configure EC2 as self-hosted runner:
    setting>actions>runner>new self hosted runner> choose os> then run command one by one


# 7. Setup github secrets:

    AWS_ACCESS_KEY_ID=AKIA6AUCIUUZWCH7BPWW

    AWS_SECRET_ACCESS_KEY=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

    AWS_REGION=ap-south-1

    AWS_ECR_LOGIN_URI = 963419612467.dkr.ecr.ap-south-1.amazonaws.com/text_sum

    ECR_REPOSITORY_NAME = simple-app

# EC2 ECR and AWS CLI setup 
![Screenshot (1419)](https://github.com/ApurvBhusari/End_to_end_Text_summarizer_nlp/assets/80256026/bb159c6b-064c-4246-bd27-6ca345d4d7c4)

# INTERFACE OF EC2 ON AWS
![Screenshot (1423)](https://github.com/ApurvBhusari/End_to_end_Text_summarizer_nlp/assets/80256026/211e70a7-b4ad-4e8d-a389-c49edf71baab)

![Screenshot (1422)](https://github.com/ApurvBhusari/End_to_end_Text_summarizer_nlp/assets/80256026/f3f63506-0b27-4f58-a7ae-474986f43ff2)

# INTERFACE OF FRONT END AFTER DEPLOYING ON AWS
![Screenshot (1424)](https://github.com/ApurvBhusari/End_to_end_Text_summarizer_nlp/assets/80256026/0294dc25-6ebf-4059-ac56-fda0b80fac0b)

# GIVING INPUT AS TEXT IN FRONT END
![Screenshot (1425)](https://github.com/ApurvBhusari/End_to_end_Text_summarizer_nlp/assets/80256026/13ecd3ad-2d67-4878-a194-d5768249cb2b)

# FINAL TEXT SUMMARIZED OUTPUT PREDICTED BY TRANSFORMER
![Screenshot (1432)](https://github.com/ApurvBhusari/End_to_end_Text_summarizer_nlp/assets/80256026/1bdd7161-0c7f-480c-ba07-73f4a4e2c485)

#VS CODE RESPONSE 
![Screenshot (1434)](https://github.com/ApurvBhusari/End_to_end_Text_summarizer_nlp/assets/80256026/387508f9-9c2b-4fa8-bbf2-c3dc1b9c2c05)


