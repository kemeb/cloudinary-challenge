# Welcome to the Cloudinary challenge

As part of this challenge you are going to assume the role of a frontend developer who has recently joined a prominent startup in the e-commerce space. After joining the business, you learn that the company is struggling with serving images to their end users in an efficient manner and as such the site has a very high bounce rate (a lot of visitors leave the site, without purchasing anything). This has been identified as a crucial issue and you are now part of the team that is tasked to resolve it.

After a handful of meetings, the main issues have been gathered which are:

- The marketing and design team are overloaded with work to create “web ready’ images - they are tasked with resizing and cropping
- The images are not served in modern formats for the users
- Sometimes the design team needs to create a crop around a particular object or recolour images and they also struggle with automation. For the purposes of this exercise you need to create a crop around the person’s face and for the second image, you will need to recolour the bag. (Currently your company sells brown, black and orange bags)


After doing your research diligently you find a tool called Cloudinary which seems to be able to tick all the necessary boxes based on the requirements set out above.

Now your task is to test out Cloudinary and present your findings to the engineering managers in hopes that this solution will be the one! 
To get started with the challenge you are required to go through the following steps:

> Please note that if you already have an existing Cloudinary account, you don’t need to register for a new one only for this challenge.


## Step 1: Create a Cloudinary Account

1. Visit the [Cloudinary Website](https://cloudinary.com).
2. Click on the "Sign up for free" button located in the top right corner of the page and register for a new account.
3. Check your email inbox for a verification email from Cloudinary and follow the instructions to verify your email address.
4. Once your email address is verified, log in to your newly created Cloudinary account.


## Step 2: Credentials and configuration of your account

In order to get your credentials, click on the Programmable Media icon in the top left corner, under the Cloudinary logo.
This will lead your dashboard where you can find your Cloud name, API Key, API Secret and API environment variable. 
![Cloudinary account credentials](https://cloudinary-res.cloudinary.com/image/upload/bo_1px_solid_gray/f_auto/q_auto/dpr_2,w_650/docs/prod_env_credentials.png)
If you want, you can change your auto generated Cloud name by clicking on settings in the bottom left corner and change it under "Product environment cloud name:" and hit save.

Now that you are done, choose an [SDK](https://cloudinary.com/documentation/cloudinary_sdks) you want to work with and install it. By clicking on "Quick Start" under the SDK logo, it will lead you to the essentials about that SDK of the documentation site.

## Setp 3: Upload the sample images to Cloudinary

The GitHub repository contains the two sample images in folder “Cloudinary challenge images”. Upload these to your Cloudinary account, via the Media Library using Cloudinary’s interface. You can find the upload button, in the upper right corner of your media library, by clicking on the “Assets” icon in the left side menu.

## Step 4: Apply the necessary transformations and optimisations

The requirement is simple. For the [first image](https://images.unsplash.com/photo-1495366691023-cc4eadcc2d7e?w=900&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8OTF8fHBlcnNvbnxlbnwwfHwwfHx8MA%3D%3D) we need to create a crop around the face of the person in the center, in a 400X400 swuare, and for the [second image](https://images.unsplash.com/photo-1610152564587-03771716da38?w=900&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NHx8d29tYW4lMjB3aXRoJTIwYmFnfGVufDB8fDB8fHww) we need to recolour the bag, as the company sells three versions but there won’t be time to take photos of those so you must use this one image. (The recolour should be done to both green and gray colors). 
 
Furthermore, we also need to save bandwidth so apply automatic quality optimisation and make sure to serve the image up in a next-gen image format.

Sample output for the transformed images:





HINT
For the purposes of this challenge it doesn’t matter which Cloudinary SDK you’re going to use - pick the one that you’re most comfortable with. You can also do the optimisations and transformations by modifying the URL directly.

## Step 5: Submit your work

Go to [this form](https://forms.gle/XAJEgTvKL4tjKh9w8) and add the transformed URLs.
Please note that you need to submit both URLs in order to successfully complete the challenge and you need to make sure to add all transformations and optimisations to the final URL so please double check your work before submitting the form.



