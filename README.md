# Introduction to Deep Learning as a Service (DLaaS)
---
_Learn how to use DLaaS for training Deep Neural Networks while tuning Hyperparameters_

There are several ways to interface with Deep Learning as a Service:
* Watson Studio GUIs
* Command Line Client
* REST APIs and Python SDK

During this introduction and lab, we will focus on using the Python SDK, and CLI but the web interface is really intutative and simplifies interaction with the service.

## Part 0 - Setup
1) Sign up for Watson Studio
If you are not already signed up for Watson Studio, sign up [here](https://www.ibm.com/cloud/watson-studio)

2) [Download and install the IBM Cloud CLI](https://console.bluemix.net/docs/cli/index.html#overview) and the machine-learning plugin
  ```
  curl -fsSL https://clis.ng.bluemix.net/install/linux | sh
  ibmcloud plugin install machine-learning
  ibmcloud login
  ibmcloud target —cf
  ```

3) [Create IBM Watson Machine Learning Service](https://github.com/biosopher/unofficial-watson-studio-python-utils/wiki/Create-WML-service-via-ui)

4) [Create IBM Cloud Object Storage](https://github.com/biosopher/unofficial-watson-studio-python-utils/wiki/Create-COS-service-via-ui)

5) Download the [Watson Machine Learning Python SDK](https://wml-api-pyclient.mybluemix.net/)

  `pip install watson-machine-learning-client`

6) Download the Unofficial Watson Studio Python Utils
  ```
  git clone https://github.com/biosopher/unofficial-watson-studio-python-utils.git
  cd unofficial-watson-studio-python-utils/
  ```


## Part 1 - Set 

## Part 2 - 
