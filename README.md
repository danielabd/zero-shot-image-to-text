# Pytorch Implementation of Zero-Shot-Image-to-Text-Generation-with-a-Specific-Style

## Approach
![](git_images/Architecture.jpg)


## Example of capabilities

variety successful captions of variety images according to the desired sentiment:
![](git_images/3_examples.png)  
  
The Effect of the weight of the sentiment loss on the Captioning with positive sentiment:  
![](git_images/lambda_ex.png)  
as λ is larger the description in the desired sentiment perspective is stronger but the coherence of the generated sentence is decreased.

## Usage

### Set up environment:
```bash
$ conda env update -f environment.yml
$ conda activate zeroshot
$ conda install --yes -c pytorch pytorch=1.7.1 torchvision cudatoolkit=11.0
```


### Run model:
```bash
$ python run.py --reset_context_delta
```
### Results: 
See results in results.csv
