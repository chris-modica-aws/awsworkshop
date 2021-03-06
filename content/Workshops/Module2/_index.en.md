+++
title = "Lab 2: Threat detection and response in AWS"
date = 2019-11-18T08:23:04+11:00
weight = 29
chapter = false
+++

This workshop is designed to help you get familiar with AWS Security services and learn how to use them to identify and remediate threats in your environment. You'll be working with services such as Amazon GuardDuty (threat detection), Amazon Macie (discover, classify & protect data), Amazon Inspector (vulnerability & behavior analysis), AWS Security Hub (centralized security view). You will learn how to use these services to investigate threats during and after an attack, set up a notification and response pipeline, and add additional protections to improve the security posture of your environment.

### Lab Overview

{{< rawhtml >}}
<video width="696" height="392" controls>
  <source src="https://apj-security-workshop.s3-ap-southeast-2.amazonaws.com/q4/lab2-intro-cmd.mp4" type="video/mp4">
  Your browser doesn't support video.
</video>
{{< /rawhtml >}}

>  **Speakers: TBD** 

>  *In this video, you’ll also hear from our partner [TBD](https://aws.amazon.com)  highlighting a real-world example of the deployment of the AWS services you’ll use in this lab. For more information, please visit [here](https://aws.amazon.com)*

## Scenario

Your company is new to the cloud and has recently performed a lift-and-shift of your infrastructure for piloting purposes.  You are a systems administrator and have been tasked with security monitoring within your AWS environment.  As part of that maintenance you are also responsible for responding to any security event in your environment.

## Architecture

For this Workshop you will have a single instance setup in the us-west-2 region. As this was a “lift-and-shift” migration for piloting, you have yet to build redundancy into your application, so you have a single public-facing web server. The web server has access to the Internet Gateway through an Elastic Network Interface. Customers access your web server through a DNS entry pointing to the Elastic Network Interface. You store static content in an S3 bucket and use the VPC S3 Endpoint Gateway for access from the web server.

![Architecture](/images/diagram-basic-arch-v2.png "Workload Architecture")

<!-- ## Presentation deck
[Workshop Presentation Deck](./threat-detect-workshop-presentation.pdf) -->

## Region
Please use the **ap-southeast-2 (Sydney)** region for this workshop.

## Modules

This workshop is broken up into the four modules below: 
{{% children depth=1 %}}

Click [here](../module2/setup) to get started!

