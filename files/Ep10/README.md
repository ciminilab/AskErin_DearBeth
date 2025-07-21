# Episode 10 images

Images were downloaded from the [Cell Painting Gallery](https://github.com/broadinstitute/cellpainting-gallery) and are licensed under CC0 1.0.

Images can be downloaded using [AWS CLI](https://aws.amazon.com/cli/) with the following command:

```bash
aws s3 cp s3://cellpainting-gallery/cpg0021-periscope/broad/images/20210422_6W_CP257/images_corrected_cropped/CP257A_Well1/CorrDNA/CorrDNA_Site_12.tiff CorrDNA_Site_12.tiff --no-sign-request

aws s3 cp s3://cellpainting-gallery/cpg0021-periscope/broad/images/20210422_6W_CP257/images_corrected_cropped/CP257A_Well1/Cycle01_DAPI/Cycle01_DAPI_Site_12.tiff Cycle01_DAPI_Site_12.tiff --no-sign-request
```
