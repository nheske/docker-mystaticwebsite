Based on [Creating, pushing, and deploying container images
with Amazon Lightsail](https://aws.amazon.com/getting-started/hands-on/lightsail-containers/)

# To push to AWS Lightsail:
aws lightsail push-container-image --region <Region> --service-name <ContainerServiceName> --label <ContainerImageLabel> --image <LocalContainerImageName>:<ImageTag>

e.g.
aws lightsail push-container-image --region us-west-2 --service-name myservice --label mystaticwebsite --image mystaticwebsite:v2

add C:\temp\lightsailct1; to path

```
aws configure
AWS Access Key ID [None]: AKIAIOSFODNN7EXAMPLE
AWS Secret Access Key [None]: wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY
Default region name [None]: us-west-2
Default output format [None]: json
```
```
aws configure list
```