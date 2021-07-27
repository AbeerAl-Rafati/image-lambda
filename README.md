# image-lambda


proccesse 
Create an S3 Bucket with “open” read permissions.   
Download a file called “images.json” from the S3 Bucket if it exists   
The images.json should be an array of objects, each representing an image.    
Create an empty array if this file is not present   
Append the data for this image to the array   
Upload the images.json file back to the S3 bucket   
