# BERT-text-classifier

In Yandex Maps, users leave
more than 120 thousand reviews every day. People praise the atmosphere
of the restaurant, scold the hotel service,
recommend a good car wash to others and write
much more. These texts contain a lot
of useful information that helps
to make the Maps service better. ML models allow
you to identify the features of an organization, find places similar
to it and create a generative description
of the institution.

But let's imagine that the data on user ratings
attached to reviews has disappeared. Is it possible to
restore them from the texts that were written
users? **Your task is to restore
the user's ratings based on the text and organization data.**

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
