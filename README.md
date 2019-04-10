# earthquake_kaggle

### Things to do  

The training dataset is very large, so we might want to work with a subset for the time-being  

- Write a simple de-spike filter to remove weird signals in the acoustic signal data

- Think of a smart way of downsampling - we almost certainly don't need data recorded at this frequency. Also note the step-like behavior in the 'time_to_failure' column  

- Decide how to chunk the data, but avoid the situation where chunks cross a failure. This should be easy to do since we have the time to failure column  

- Come up with lots of statistical features that can be calculated on the chunks. We can then train regression models on these features  

- Anything else?   