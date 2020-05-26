# tljh-admin

This repository is a collection of management scripts for maintaining a course of Computing students.

## Setup

You need to create a customised `.env` file for your settings. It should look have the following contents:

    course-root = "<your course directory>"
    course-id = "<your course id>"
    admin = "<directory where these scripts are stored>"
    email = "<your email address for letsencrypt registration>"
    domain = "your server domain address for letsencrypt registration"

## Contents

This repository contains the following scripts:

1. `collect-submissions`  
   A script to collect all new submissions, and sync files to Dropbox.

2. `culling`  
   An interface for enabling/disabling auto-culling of unused jupyter kernels.

3. `disk-usage`  
   An interface for checking disk usage on the VM, and vacuuming journal log files (which tend to take up a lot of space after some time.

4. `enable-https`  
   A notebook for enabling automatic HTTPS renewal for your domain.

5. `manage-students`  
   An interface for easy first-time setup of students.

6. `resize-disk-when-full`  
   A notebook documenting steps for resizing a Google Cloud VM instance when it runs out of space.
   
7. `sync-all-to-dropbox`  
   A notebook for syncing course directory contents to a Dropbox account.
