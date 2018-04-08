# CI Info
Provides in depth insight into the continuous integration and deployment 
process.  

# Table Of Contents
- [Overview](#overview)
- [Getting Started](#getting-started)

# Overview
CI Info aims to provide users with in depth knowledge about the current state 
of their continuous integration and deployment workflows.  

Features include:

- **Service agnostic**
	- CI Info works with any continuous integration platform.

- **Granular status information**
	- CI Info provides details about exactly what stage and step the 
	  pipeline is currently executing.

- **User manual generation**
	- CI Info automatically generates a user manual for the continuous integration pipeline.
	- Complete with troubleshooting guides for troublesome pipeline steps.

CI Info is composed of 2 main compontents:

- API - Stores continuous integration information
- Client - Submits continuous information

# Getting Started
To use CI Info you must insert a few CI Info API calls into your continuous 
integration pipeline.  

These API calls provide CI Info with live in depth status information about the 
execution of a pipeline.  

To make these API calls use the `ci-info` client. A binary download is only
available for linux at the moment because the tool is still in active development.  
