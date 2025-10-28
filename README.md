# CLIP Pretraining - Fashion Dataset

To get started, let's establish some common ground:
- We should seperate brand and product names (FYI the first word(s) of a productDisplayName is always the brand name)

- Currently the unique values for the gender column are: Men, Women, Boys, Girls and Unisex - let's keep it that way unless it gets too complex for the fitting process

- Read and run pull_images.ipynb to download images, should be ~600MB for seed 123 and 10% fraction