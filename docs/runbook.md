# Runbook

## Deployment

```bash
npm install && cdk deploy --context environment=prod
```

## Processing Video

```bash
# Upload video for processing
aws s3 cp video.mp4 s3://input-bucket/

# Check processing status
aws stepfunctions describe-execution --execution-arn arn:aws:...
```

## Custom Model Deployment

1. Train model in SageMaker
2. Create endpoint configuration
3. Update Lambda to use new endpoint
4. Test with sample videos

## Monitoring

- Check Rekognition API usage daily
- Monitor Lambda duration/errors
- Review S3 storage growth weekly
