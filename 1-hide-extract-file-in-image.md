Step1: Download steghide from this URL- [Steghide](https://sourceforge.net/projects/steghide/)

Add this steghide path to environment variables.

Step2: Test the steghide  
```
steghide --help
```
  
This should be visible when you type this command  
![image](https://github.com/Modilover69/CFEL/assets/132368904/5b6998c5-0416-458a-ba24-fca188256329)

step3: Embed text file in image.

Command - 
```
steghide embed -ef test.txt -cf image.jpeg
```

![image-1](https://github.com/Modilover69/CFEL/assets/132368904/cb3aabda-e2e9-4105-8d36-74c7e1fd626e)

step4: Command to extract text file form imgae

```
steghide extract -sf image.jpeg
```  

![image-2](https://github.com/Modilover69/CFEL/assets/132368904/682a67b3-9ff8-4b8b-8330-997a18733c82)

step5: Output of the command  

![image-3](https://github.com/Modilover69/CFEL/assets/132368904/0af758c3-bd24-48df-beac-d5c6ef7e0f53)

To see any file are embeded in image file or not

Command - 
```
steghide info image.jpeg
```  

![image](https://github.com/Modilover69/CFEL/assets/132368904/8ae75d56-7157-4c55-9e49-dc03557bc74e)
