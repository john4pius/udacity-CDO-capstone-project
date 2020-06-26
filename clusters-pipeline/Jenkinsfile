 
pipeline {
     agent any
     stages {
         stage('Build') {
             steps {
                 sh 'echo "Udacity Capstone Project"'
                 sh '''
                     echo "Multiline shell steps works too"
                 '''
             }
         }

		 stage('Create kubernetes cluster') {
			steps {
				withAWS(region:'us-east-2',credentials:'aws-credential') {
					sh '''
						eksctl create cluster \
						--name CDOcapstonecluster \
						--version 1.16 \
						--nodegroup-name standard-workers \
						--node-type t2.micro \
						--nodes 2 \
						--nodes-min 1 \
						--nodes-max 3 \
						--region us-east-2 \
						--zones us-east-2a \
						--zones us-east-2b \
						--zones us-east-2c \
					'''
				}
			}
		}

		stage('Create conf file cluster') {
			steps {
				withAWS(region:'us-east-2', credentials:'aws-credential') {
					sh '''
						aws eks --region us-east-2 update-kubeconfig --name CDOcapstonecluster
					'''
				}
			}
		}
                 
     }
}
