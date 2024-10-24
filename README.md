# BERT-text-classifier

The dataset in tskv format contains the following information:
* Address of the organization (address)
* Name of the organization (name_ru)
* List of categories to which the organization belongs (rubrics)
* User rating from 0 to 5 (rating)
* The text of the review (text)
  
You need to send a tskv file with a test dataset
(20 thousand lines) with predicted ratings in
the rating column (one of 5 values: 1., 2., 3., 4., 5.). The order
of the lines must match the original file

Dataset is available here https://github.com/yandex/geo-reviews-dataset-2023
