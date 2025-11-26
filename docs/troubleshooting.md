# Troubleshooting

## Common Issues

### Video Processing Fails
- Check video format is supported
- Verify S3 permissions
- Review Lambda timeout settings

### Low Detection Accuracy
- Check video quality/resolution
- Verify model is appropriate for use case
- Consider custom model training

### High Latency
- Enable frame sampling
- Use smaller model variants
- Check for Lambda cold starts

### Rekognition Throttling
- Request limit increase
- Implement exponential backoff
- Queue requests with SQS
