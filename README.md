## Google Cloud Platform
* GCP **gloud-cli** setup
```powershell
gcloud auth login
gcloud config set project
gcloud cloud-shell ssh 
```

## Generate ssh key pair

* Run the following command:
```powershell
ssh-keygen -f "C:\Users\JohnDoe\.ssh\gcpcloud"
```

* Generated **ssh key pair**:
	gcpcloud.pub<**public**>
	gcpcloud<**private**>
				
![](https://github.com/projectfinalaudio/GCP_GCE/blob/main/images/generate%20ssh%20key%20pair%20and%20publish%20the%20public%20key%20to%20GCP.png?raw=true)


## Update your config file with the private key path
![](https://github.com/projectfinalaudio/GCP_GCE/blob/main/images/update%20your%20config%20file%20with%20the%20private%20key%20path.png?raw=true)

## Modify generated ssh key to use the Google Cloud account username

![](https://github.com/projectfinalaudio/GCP_GCE/blob/main/images/modify%20generated%20ssh%20key%20to%20use%20google%20account%20username.png?raw=true)
