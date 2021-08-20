## Using Shutterstock's image datasets to train your computer vision models

Welcome! This repository contains the Amazon SageMaker notebook code used in the blog post [**Using Shutterstock's image datasets to train your computer vision models**](https://aws.amazon.com/blogs/awsmarketplace/using-shutterstocks-image-datasets-to-train-your-computer-vision-models/).


For this example, we use the Free Sample: Images & Metadata of “Whole Foods” Shoppers dataset from Shutterstock’s Image Datasets to demonstrate how to train a multi-label image classification model using Shutterstock’s prelabeled image assets. This dataset can be found in the [AWS Data Exchange](https://aws.amazon.com/data-exchange/) and contains images of Whole Foods shoppers. Each image is tagged with 7-50 keywords describing what is seen in the image. 


You can get started using this notebook by following the steps outlined in [this blog](https://aws.amazon.com/blogs/awsmarketplace/using-shutterstocks-image-datasets-to-train-your-computer-vision-models/). 

At a high level, setup involves these 4 steps:

1. Subscribe to the Free Sample: Images & Metadata of “Whole Foods” Shoppers dataset from Shutterstock’s Image Datasets here. Export this dataset to an S3 bucket.
2. Create an Amazon SageMaker Notebook instance [here](https://console.aws.amazon.com/sagemaker/home?region=us-east-1#/notebook-instances). For the development of this notebook, we used an `ml.t2.medium`. Make sure the SageMaker role has access to your Shutterstock Image Dataset S3 bucket. Note that charges apply.
3. Once your instance has been spun up, click **Open Jupyter** and upload `image-classification-shutterstock-image-datasets.ipynb` from this repository.
4. Once uploaded, open `image-classification-shutterstock-image-datasets.ipynb` and update the variable at the top to point to the S3 bucket you are using to store your Shutterstock Image Dataset.


## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

