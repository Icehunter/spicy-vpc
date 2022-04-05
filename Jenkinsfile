#!/usr/bin/env groovy

@Library(["spicy-automation@development"]) _

spicyVPC(
    jenkinsAWSCredentialsID: "prod/aws/spicy-www",
    region: "us-east-1",
    stackName: "spicy-vpc",
    ownerTag: "SpicyTeam",
    productTag: "spicy",
    componentTag: "spicy-VPC",
    availabilityZones: "us-east-1a,us-east-1b,us-east-1c,us-east-1d",
    createAdditionalPrivateSubnets: true,
    createPrivateSubnets: true,
)
