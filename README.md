# Agify API Challenge

This is a Python oriented code challenge designed to showcase 
proficiency in Python and REST APIs using the publicly available API resource [Agify](https://agify.io/). 



## The task
The goal of this challenge is to create a basic Python script which will use the [Agify API](https://agify.io/) to 
recursively fetch the estimated age of X amount of names provided from a JSON file and output the results to a 
new JSON file. The estimated age must be appended to the person's existing data.


This challenge will be assessed on efficiency and speed of the script, as well as the structure and extensibility.

Example input:
```
  {
    "email": "colemanwells@custimy-fake.io",
    "name": "Newman"
  },
  ....
```

Example output:
```
  {
    "email": "colemanwells@custimy-fake.io",
    "name": "Newman",
    "age": 52
  },
  ....
```

Additionally, the input and output file must be parameterized for easy execution
and should allow following execution pattern:
```
python script.py input_file.txt output_file.txt
```


## Resources

- In this git repository, you will find the *people.json* file. 
This contains the names and emails of 20 randomly generated people.
- The API documentation for the Agify API can be found [HERE](https://agify.io/)

## Submission
When you feel like you have arrived at a good solution, you can either push your code to a new repository or
ZIP up your project files and upload the file to [WeTransfer.com](https://wetransfer.com/) and 
send the submission to ```l.popp@custimy.io```

## Help
If you encounter any problems with the deployment of the application, or you have any questions regarding the actual task, 
please do not hesitate to send us an email at ```l.popp@custimy.io``` and we will quickly get back to you. 
Any such questions will **not** count towards your final assessment.
