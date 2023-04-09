pipeline {
	agent any
	
	stages{
		stage('Checkout'){
			git 'https://github.com/HameedNazeer/New_Instance_terraform.git'
			}
		}
		stage('terraform init'){
			steps{
				sh 'terraform init'
				}
			}
		stage('terraform plan and apply'){
			steps{
				sh 'terraform plan'
				sh 'terraform apply -auto approve'
				}
			}
}
}
