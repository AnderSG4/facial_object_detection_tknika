# facial_object_detection_tknika
This project will detect diferentnt facial objects like mask, glasses, hat, helmet... using tensorflow. 

## Download and prepare dataset
To prepare the dataset you will need to daownload the dataset from https://humansintheloop.org/resources/datasets/mask-dataset-download/?submissionGuid=ae72ecbe-f80d-48bd-a441-c74ebb8d3a5d and prepare it executing the code in json_to_tfRecord.ipynb 


For that, it is necesary to put the folders annotations and images into a floder named data. Everithing in the same folder of the repository. The meta.json is used to create the file label_map.pbtxt with which we define the names and ids of the clases to detect, as well as the name that wil be shown in the image.