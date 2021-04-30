Based on [Creating, pushing, and deploying container images
with Amazon Lightsail](https://aws.amazon.com/getting-started/hands-on/lightsail-containers/)

# To push to AWS Lighsail:
aws lightsail push-container-image --region <Region> --service-name <ContainerServiceName> --label <ContainerImageLabel> --image <LocalContainerImageName>:<ImageTag>

e.g.
aws lightsail push-container-image --region us-west-2 --service-name myservice --label mystaticwebsite --image mystaticwebsite:v2

