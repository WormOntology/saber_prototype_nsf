

# SABER <img src="https://avatars2.githubusercontent.com/u/34253653?s=200&v=4" alt="APL Brain logo" width="80"/>

## What is SABER?
SABER (Scalable Analytics for Brain Exploration Research) is a library of containerized tools and a workflow deployment system for enabling processing of large neuroimaging datasets. Current workflows include processing of X-ray Microtomorography data to produce cell density estimates as well as processing Electron Microscopy images to segment neuron bodies. 

## Prerequisites
SABER requires docker and docker-compose. Please use the latest versions. To run our example workflows, you will need an AWS account to enable cloud storage through the AWS S3 service (https://aws.amazon.com/account/). To access data for our example workflows you will need an account at https://api.bossdb.org

## Installation
Simply clone this repository and run
`docker-compose up -d` inside it!

## Execution of workflows

Please see our [wiki](https://github.com/aplbrain/saber/wiki) for more information!

## Legal

Use or redistribution of the Boss system in source and/or binary forms, with or without modification, are permitted provided that the following conditions are met:
 
1. Redistributions of source code or binary forms must adhere to the terms and conditions of any applicable software licenses.
2. End-user documentation or notices, whether included as part of a redistribution or disseminated as part of a legal or scientific disclosure (e.g. publication) or advertisement, must include the following acknowledgement:  The Boss software system was designed and developed by the Johns Hopkins University Applied Physics Laboratory (JHU/APL). 
3. The names "The Boss", "JHU/APL", "Johns Hopkins University", "Applied Physics Laboratory", "MICrONS", or "IARPA" must not be used to endorse or promote products derived from this software without prior written permission. For written permission, please contact BossAdmin@jhuapl.edu.
4. This source code and library is distributed in the hope that it will be useful, but is provided without any warranty of any kind.
