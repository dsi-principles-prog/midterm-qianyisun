# Principles of Programming Midterm project


## Dataset Source information
The dataset is from https://www.kaggle.com/ramamet4/app-store-apple-data-set-10k-apps and it includes more than 7000 Apple iOS mobile application details.Dimensions of the data set are 7197 rows and 16 columns.

## Target variable
"user_rating_ver": it represents the average user rating value for current version. The average user rating value is the range between 0 and 5.

## The definition of variables
"id" : App ID\
"track_name": App Name\
"size_bytes": Size (in Bytes)\
"currency": Currency Type\
"price": Price amount\
"rating_count_tot": User Rating counts (for all version)\
"rating_count_ver": User Rating counts (for current version)\
"user_rating" : Average User Rating value (for all version)\
"ver" : Latest version code\
"cont_rating": Content Rating\
"prime_genre": Primary Genre\
"sup_devices.num": Number of supporting devices\
"ipadSc_urls.num": Number of screenshots showed for display\
"lang.num": Number of supported languages\
"vpp_lic": Vpp Device Based Licensing Enabled\

## Motivting question
My main goal is to solve the problem that how the attributes of App contribute the average current user ratings. Finally we can build a model to predict the average user rating value for current version.
