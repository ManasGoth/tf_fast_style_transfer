# tf_fast_style_transfer
Add styles from famous paintings to any photo in a fraction of a second

Original code @https://github.com/lengstrom/fast-style-transfer  
The above code used Scipy 1.X .   

### Modifications made in files to support Scipy 2.X
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
  
