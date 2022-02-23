## Introduction

[![GitHub stars](https://img.shields.io/github/stars/inferrd/inferrd?style=social&label=Star&maxAge=2592000)](https://GitHub.com/inferrd/inferrd/stargazers/) [![License](https://img.shields.io/static/v1?label=license&message=ELv2&color=brightgreen)](https://github.com/inferrd/inferrd/tree/main/LICENSE)

![](assets/logo.png)

**ML Deployment made simple, scalable and collaborative**  
The new open-source standard to deploy, monitor and secure Machine Learning services.

![](assets/product_screenshot.png)

Inferrd is on a mission to make machine learning deployment a breeze.

* **Maintenance-free environments**. Just drag and drop your models, and get an API.
* **Your data stays in your cloud**. Have full control over where you send your data, and how it's processed.
* **No more security compliance process** to go through as Inferrd is self-hosted. 
* **No more pricing indexed on volume**, as cloud-based solutions offer. 

## Quick start

Inferrd can be installed by clone this repo and docker.

Make sure `docker` is installed on your inference server. Then create a `.env` file that contains your AWS S3 keys & host name (it will be used to store your models).

```
AWS_SECRET_ACCESS_KEY=xxxxx
AWS_ACCESS_KEY_ID=xxxx
AWS_BUCKET_NAME=my-models
# change this if you want Inferrd to be accessible from another server
HOST=localhost
```

Then run the two following commands to get started:

```
git clone https://github.com/inferrd/oss.git
cd inferrd
docker-compose up
```

Now visit [http://localhost:3001](http://localhost:3001)

## Features

* **Wide framework support**: Deploy TensorFlow, PyTorch, HuggingFace, ONNX, Scikit and XGBoost hassle free.
* **GPU Support**: GPU acceleration comes pre-configured out of the box.
* **Monitoring**: Monitoring is available as soon as you make your first request. Prometheus monitoring is also available.
* **Versioning**: Keep track of all the versions you deploy and rollback anytime.
* **Request Logging**: Inspect all requests coming into your model.

## Community support

For general help using Inferrd, please refer to the official Inferrd documentation. For additional help, you can use one of these channels to ask a question:

* [Discord](https://discord.gg/EequCErc6s) \(For live discussion with the Community and Inferrd team\)

## Entreprise Edition

Are you looking for support and more advanced features such as RBAC, AutoScale, Multi-node deployments and A/B testing? [Contact us](mailto:theo@inferrd.com).