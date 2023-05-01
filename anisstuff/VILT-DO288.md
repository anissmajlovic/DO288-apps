# VILT DO288

```bash
#: Preface A: Introduction
#: Section A.1: Red Hat OpenShift Development II: Building Kubernetes Applications
#: Section A.2: Orientation to the Classroom Environment
#: Section A.3: Controlling Your Systems
mv ~/Downloads/rht_classroom.rsa ~/.ssh/
chmod 0600 ~/.ssh/rht_classroom.rsa
ssh-add ~/.ssh/rht_classroom.rsa
ssh -i ~/.ssh/rht_classroom.rsa -J cloud-user@159.135.163.8:22022 student@172.25.252.1 -p 53009
#: Chapter 1: Deploying and Managing Applications on an OpenShift Cluster
#: Section 1.1: Introducing OpenShift Container Platform 4
#: Section 1.2: Quiz: Introducing OpenShift 4
#: Section 1.3: Guided Exercise: Configuring the Classroom Environment
#: Section 1.4: Deploying an Application to an OpenShift Cluster
TAG: # Delete local branch
git branch -a
# Git's git branch command has two options for deleting a local branch: -d and -D.
git checkout -b feature
git add . && git ci -am'add wonderful.txt'
git push -u origin feature
git checkout main
git branch -d feature
# Deleted branch feature (was 3aac499)
git branch -a
# git branch -d/-D Won't Delete the Remote Branch

TAG: # Delete remote branch
git remote show origin | grep feature
git push origin -d feature
# u/p: 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
git branch -a | grep feature

#: Section 1.5: Guided Exercise: Deploying an Application to an OpenShift Cluster
#: Section 1.6: Managing Applications with the Web Console
#: Section 1.7: Guided Exercise: Managing an Application with the Web Console
#: Section 1.8: Managing Applications with the CLI
#: Section 1.9: Guided Exercise: Managing an Application with the CLI
#: Section 1.10: Lab: Deploying and Managing Applications on an OpenShift Cluster
#: Section 1.11: Summary
#: Chapter 2: Designing Containerized Applications for OpenShift
#: Section 2.1: Selecting a Containerization Approach
#: Section 2.2: Quiz: Selecting a Containerization Approach
#: Section 2.3: Building Container Images with Advanced Containerfile Instructions
#: Section 2.4: Guided Exercise: Building Container Images with Advanced Containerfile Instructions
#: Section 2.5: Injecting Configuration Data into an Application
#: Section 2.6: Guided Exercise: Injecting Configuration Data into an Application
#: Section 2.7: Lab: Designing Containerized Applications for OpenShift
#: Section 2.8: Summary
#: Chapter 3: Publishing Enterprise Container Images
#: Section 3.1: Managing Images in an Enterprise Registry
#: Section 3.2: Guided Exercise: Using an Enterprise Registry
#: Section 3.3: Allowing Access to the OpenShift Registry
#: Section 3.4: Guided Exercise: Allowing Access to the OpenShift Registry
#: Section 3.5: Creating Image Streams
#: Section 3.6: Guided Exercise: Creating an Image Stream
#: Section 3.7: Lab: Publishing Enterprise Container Images
#: Section 3.8: Summary
#: Chapter 4: Managing Builds on OpenShift
#: Section 4.1: Describing the Red Hat OpenShift Build Process
#: Section 4.2: Quiz: The OpenShift Build Process
#: Section 4.3: Managing Application Builds
#: Section 4.4: Guided Exercise: Managing Application Builds
#: Section 4.5: Triggering Builds
#: Section 4.6: Guided Exercise: Triggering Builds
#: Section 4.7: Implementing Post-commit Build Hooks
#: Section 4.8: Guided Exercise: Implementing Post-Commit Build Hooks
#: Section 4.9: Lab: Building Applications for OpenShift
#: Section 4.10: Summary
#: Chapter 5: Customizing Source-to-Image Builds
#: Section 5.1: Describing the Source-to-Image Architecture
#: Section 5.2: Quiz: Describing the Source-to-Image Architecture
#: Section 5.3: Customizing an Existing S2I Base Image
#: Section 5.4: Guided Exercise: Customizing S2I Builds
#: Section 5.5: Creating an S2I Base Image
#: Section 5.6: Guided Exercise: Creating an S2I Base Image
#: Section 5.7: Lab: Customizing Source-to-Image Builds
#: Section 5.8: Summary
#: Chapter 6: Deploying Multi-container Applications
#: Section 6.1: Describing OpenShift Templates
#: Section 6.2: Quiz: Describing OpenShift Templates
#: Section 6.3: Creating a Helm Chart
#: Section 6.4: Guided Exercise: Creating a Helm Chart
#: Section 6.5: Customizing a Deployment with Kustomize
#: Section 6.6: Guided Exercise: Customizing Deployments with Kustomize
#: Section 6.7: Lab: Deploying Multi-container Applications
#: Section 6.8: Summary
#: Chapter 7: Managing Application Deployments
#: Section 7.1: Monitoring Application Health
#: Section 7.2: Guided Exercise: Activating Probes
#: Section 7.3: Selecting the Appropriate Deployment Strategy
#: Section 7.4: Guided Exercise: Implementing a Deployment Strategy
#: Section 7.5: Managing Application Deployments with CLI Commands
#: Section 7.6: Guided Exercise: Managing Application Deployments
#: Section 7.7: Lab: Managing Application Deployments
#: Section 7.8: Summary
#: Chapter 8: Building Applications for OpenShift
#: Section 8.1: Integrating External Services
#: Section 8.2: Guided Exercise: Integrating an External Service
#: Section 8.3: Containerizing Services
#: Section 8.4: Guided Exercise: Containerizing Nexus as a Service
#: Section 8.5: Deploying Cloud-Native Applications with JKube
#: Section 8.6: Guided Exercise: Deploying an Application with JKube
#: Section 8.7: Lab: Building Cloud-Native Applications for OpenShift
#: Section 8.8: Summary
#: Chapter 9: Comprehensive Review: Red Hat OpenShift Developer II: Building Kubernetes Applications
#: Section 9.1: Comprehensive Review
#: Section 9.2: Lab: Comprehensive Review
#: Appendix A: Creating a GitHub Account
#: Section A.1: Creating a GitHub Account
#: Appendix B: Creating a Quay Account
#: Section B.1: Creating a Quay Account
#: Appendix C: Useful Git Commands
#: Section C.1: Git Commands
```