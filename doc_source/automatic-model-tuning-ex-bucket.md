# Specify a Bucket and Data Output Location<a name="automatic-model-tuning-ex-bucket"></a>

Specify the name of the Amazon S3 bucket where you want to store the output of the training jobs that the tuning job launches\. The name of the bucket must start with **sagemaker**, and be globally unique\. The bucket must be in the same AWS Region as the notebook instance that you use for this example\. You can use the bucket that you created when you set up Amazon SageMaker, or you can create a new bucket\. For information, see [Step 1\.2: Create an S3 Bucket](gs-config-permissions.md)\.

`prefix` is the path within the bucket where Amazon SageMaker stores the output from training jobs\.

```
bucket = 'sagemaker-MyBucket'                               # Replace with the name of your S3 bucket
prefix = 'sagemaker/DEMO-automatic-model-tuning-xgboost-dm'
```

## Next Step<a name="automatic-model-tuning-ex-next-data"></a>

[Download, Prepare, and Upload Training Data](automatic-model-tuning-ex-data.md)