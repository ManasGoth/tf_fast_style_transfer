# tf_fast_style_transfer
Add styles from famous paintings to any photo in a fraction of a second

Original code @https://github.com/lengstrom/fast-style-transfer  
   

### Modifications made in files to support scipy==1.3.1 and tensorflow==2.0.0
 ```
 .\evaluate.py 
  .\src\utils.py
  .\src\transform.py
```

### List of required packages , included in requirements.txt file 

### Run code
```
>>python evaluate.py --checkpoint ./rain-princess.ckpt --in-path ./input_image.jpg --out-p
ath ./output_image.jpg
```
  
