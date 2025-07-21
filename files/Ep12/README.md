# Episode 12 images

Images were downloaded from the [Cell Painting Gallery](https://github.com/broadinstitute/cellpainting-gallery) and are licensed under CC0 1.0.

Images can be downloaded using [AWS CLI](https://aws.amazon.com/cli/) with the following command:

```bash
aws s3 cp --recursive s3://cellpainting-gallery/cpg0016-jump/source_4/workspace/analysis/2021_04_26_Batch1/BR00117035/analysis/BR00117035-A01-1/outlines/ outlines/ --no-sign-request
```
