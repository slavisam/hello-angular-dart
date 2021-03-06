# Getting started with Angular Dart on Sourcevoid

This is a tutorial on how to get started with Angular Dart on the Sourcevoid cloud platform. Follow the instructions below to get 
your first app up and running. If you have any questions of issues let us know by [creating a issue](https://github.com/Sourcevoid/hello-angular-dart/issues/new) 
on this repo or contact us directly! 

## Prerequisites

![alt tag](https://raw.githubusercontent.com/Sourcevoid/cloud-portal-animations/master/public/hello-prerequisites.gif)

1. [Create a Sourcevoid account and login](https://cloud.sourcevoid.com/#signup) 
2. Create a Sourcevoid pool (if you don't already have one you want to use)
3. Create a Sourcevoid app (if you don't already have one you want to use)

## Deploy a Angular Dart env from Github (option 1)

1. Fork this repo to your account or create a new repo and upload the contents of this repo to your own 
2. Connect your Github account
3. Enter a name for the environment, "angular-dart" for example  
4. Select your Github repo from the selector
5. Press the create button and wait a few seconds to allow the deployment to complete
6. Press the "Static env settings" button (will appear when the env as been deployed) 
7. Press "Edit" on the row with directory "public" and change it to "build/web", go back to the app view (back button works)
8. Press the start button to start the environment
9. Press one of the links in the "App" or "Env" column in the app view to open the app/env 
10. Press the blue console button to watch the output of the server process (optional) 

## Deploy a Angular Dart env from local archive upload (option 2)

1. [Click here](https://github.com/Sourcevoid/hello-angular-dart/archive/master.zip) or above on "Clone or download" to download a zip archive of this repo
2. Enter a name for the environment, "angular-dart" for example  
3. Select your "zip" as the deployment type from the selector
4. Press the "Choose archive" button and choose the archive you downloaded in step 1
5. Press the "More" button and enter (or copy/paste) "/hello-angular-dart-master" into the "Source Root" field (this because the Github zipped archive contains a top level directory called "hello-angular-dart-master" where the source resides)
5. Press the create button and wait a few seconds to allow the deployment to complete
6. Press the "Static env settings" button (will appear when the env as been deployed) 
7. Press "Edit" on the row with directory "public" and change it to "build/web", go back to the app view (back button works)
8. Press the start button to start the environment
9. Press one of the links in the "App" or "Env" column in the app view to open the app/env 
10. Press the blue console button to watch the output of the server process (optional) 

