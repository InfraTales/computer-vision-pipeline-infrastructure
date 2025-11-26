# Cost Analysis (₹)

Cost estimates for the **Computer Vision Pipeline** in **Indian Rupees (₹)**.

## Production Environment

| Service | Monthly Cost (₹) | Notes |
|---------|------------------|-------|
| **Rekognition** | ₹40,000–80,000 | Image/video analysis |
| **MediaConvert** | ₹20,000–40,000 | Video transcoding |
| **SageMaker** | ₹30,000–60,000 | Custom ML models |
| **Kinesis Video** | ₹15,000–30,000 | Video streaming |
| **S3** | ₹10,000–20,000 | Media storage |
| **Lambda** | ₹5,000–10,000 | Processing functions |
| **Total** | **₹120,000–240,000** | ~$1,500–3,000/month |

## Per-Video Costs

| Resolution | Cost per Hour (₹) |
|-----------|-------------------|
| 720p | ₹50–100 |
| 1080p | ₹100–200 |
| 4K | ₹300–500 |

## Cost Optimization

- **Frame sampling** – Analyze every Nth frame
- **Region of interest** – Process only relevant areas
- **Batch processing** – Use off-peak pricing
- **Model optimization** – Use smaller models for simple tasks
