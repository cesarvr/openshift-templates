## Openshift 3.xx Resources. 


### How to configure secrets for git repository
  - [Basic Auth](https://docs.openshift.com/enterprise/3.1/dev_guide/builds.html#basic-authentication)
  - [SSH](https://docs.openshift.com/enterprise/3.1/dev_guide/builds.html#ssh-key-authentication)




### Templates. 
  - deploy-router-services 
    - this template takes an image:tag and listen for changes, if a change happens he deploy the image. 
    - **use case:** to promote image between environments/projects (eg: from development to QA). 

