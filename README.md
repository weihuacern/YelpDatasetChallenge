# YelpDatasetChallenge
## Yelp Dataset
- Location of the Yelp dataset, round 11. See [details](https://www.yelp.com/dataset). <br />
- Description of the Yelp dataset, round 11, in [JSON](https://www.yelp.com/dataset/documentation/json) and [SQL](https://www.yelp.com/dataset/documentation/sql). <br />
  - business.json: Contains business data including location data, attributes, and categories. <br />
  - review.json: Contains full review text data including the user_id that wrote the review and the business_id the review is written for. <br />
  - user.json: User data including the user's friend mapping and all the metadata associated with the user. <br />
  - checkin.json: Checkins on a business. <br />
  - tip.json: Tips written by a user on a business. Tips are shorter than reviews and tend to convey quick suggestions. <br />
  - photos.json: This file is formatted as a JSON list of objects. <br />

## Notebooks Description
- Several jupyter notebooks are stored in the [NoteBooks](https://github.com/weihuacern/YelpDatasetChallenge/tree/master/NoteBooks) directory for different model development aims for this project. <br />
  - [BasicFeatureExplore.ipynb](https://github.com/weihuacern/YelpDatasetChallenge/blob/master/NoteBooks/BasicFeatureExplore.ipynb): Basic feature investigation for all datasets. <br />
  - [TextFeatureExplore.ipynb](https://github.com/weihuacern/YelpDatasetChallenge/blob/master/NoteBooks/TextFeatureExplore.ipynb): Feature engineer for text features. <br />
  - [PredictRateModels.ipynb](https://github.com/weihuacern/YelpDatasetChallenge/blob/master/NoteBooks/PredictRateModels.ipynb): Model test for review rate prediction. <br />
  - [RecommendationSysTest.ipynb](https://github.com/weihuacern/YelpDatasetChallenge/blob/master/NoteBooks/RecommendationSysTest.ipynb): Build recommendation system with [Surprise package](http://surpriselib.com/). <br />

## Project Documentation
- All the documents related to this project, like weekly summary slides and latex documentation, are stored in the [Documentation](https://github.com/weihuacern/YelpDatasetChallenge/tree/master/Documentation) directory. <br />
  - [YelpDataChallenge_20180204.pdf](https://github.com/weihuacern/YelpDatasetChallenge/blob/master/Documentation/YelpDataChallenge_20180204.pdf): Yelp dataset challenge kick off slide for data incubator semi-final list. <br />
  - [YelpDataChallenge_DIInterview_20180220.pdf](https://github.com/weihuacern/YelpDatasetChallenge/blob/master/Documentation/YelpDataChallenge_DIInterview_20180220.pdf): Yelp dataset challenge summary for data incubator final list. <br />
