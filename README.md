
# YOUTUBE TRENDING VIDEO ANALYSIS  
<img src="https://user-images.githubusercontent.com/129526047/236859217-b71c4e06-e2f1-479e-a3f8-dfa075979129.png" width="500">       <img src="https://user-images.githubusercontent.com/129526047/236859088-e1f4b177-4a9a-4e8a-a625-fc99bfb3f878.png" width="500">

# ABOUT PROJECT
Welcome to this project on YouTube video trend analysis! In this project, we will explore trends in YouTube video data to gain insights into what makes a video successful. We will use a dataset of YouTube video information and analyze key features such as views, likes, comments, category and various other factors  to identify patterns and relationships that can help creators optimize their videos for success. Along the way, we will use a variety of tools and techniques from data analysis and visualization to machine learning and predictive modeling. Whether you're a data analyst, a YouTube creator, or just curious about the secrets of YouTube success, this project is for you!

# Introduction
YouTube is one of the largest online video-sharing platforms, providing content creators with a space to share their videos and earn extra income. For content creators, understanding whether their videos will be engaged by viewers is essential for improving the quality of their content before publishing. In this project, we build a dataset of videos collected from various categories and evaluate metrics for measuring video engagement.


#  DATASET AND FEATURES

This dataset offers two distinct sets of data, each with its own distribution. 
The first set consists of trending video datasets from Vietnam, extracted from UCL, containing plenty of features which is used to provide valuable insights into the underlying factors contributing to video trends.

## VIETNAM DATASET FEATURES
The dataset includes the following columns:

< > channel_id : ID of channel

< > channel_name : Name of channel

< > channel_category : Category of channel

< > channel_started : Started year of channel

< > channel_rank : Rank of channel in most-subscribed Vietnamese channels

< > channel_subscribers : Number of subscribers of channel

< > id : ID of video

< > title : Title of video

< > length_title : Length title of video (tokens)

< > categories : Categories of video

< > description : Description of video

< > tags : Tags of video

< > num_tags : Number of tags of video

< > upload_date : Uploaded date of video

< > delta_upload_date : Distance between collected date and uploaded date (days)

< > duration : Duration of video (minutes)

< > view_count : Number of views of video

< > like_count : Number of likes of video

< > comment_count : Number of comments of video

< > dislike_count : Number of dislikes of video

< > like_per_view : Number of likes per views of video

< > comment_per_view : Number of comments per views of video

< > dislike_per_view : Number of dislikes per views of video

< > engagement_rate_1 : Total comments and likes per views of video

< > engagement_rate_2 : Total comments, likes, and dislikes per views of video

< > q_score : Q score of video

< > label_1 : Engagement level based on engagement_rate_1 of video

< > label_2: Engagement level based on q_score of video


## Missing Data Table

| Column | Description | Missing Rate |
| ------ | ----------- | ------------ |
| channel_id | Id of channel | 0.000000 |
| channel_name | Name of channel | 0.000000 |
| channel_category | Category of channel | 0.000000 |
| channel_started | Started year of channel | 0.000000 |
| channel_rank | Rank of channel in most-subscribed Vietnamese channels | 0.000000 |
| channel_subscribers | Number of subscribers of channel | 0.000000 |
| id | Id of video | 0.000000 |
| title | Title of video | 0.000000 |
| length_title | Length title of video (tokens) | 0.000000 |
| categories | Categories of video | 0.000000 |
| description | Description of video | 0.017609 |
| tags | Tags of video | 0.000000 |
| num_tags | Number of tags of video | 0.000000 |
| upload_date | Uploaded date of video | 0.000000 |
| delta_upload_date | Distance between collected date and uploaded date (days) | 0.000000 |
| duration | Duration of video (minutes) | 0.000000 |
| view_count | Number of views of video | 0.000000 |
| like_count | Number of likes of video | 0.000000 |
| comment_count | Number of comments of video | 0.000000 |
| dislike_count | Number of dislikes of video | 0.000000 |
| like_per_view | Number of likes per views of video | 0.000000 |
| comment_per_view | Number of comments per views of video | 0.000000 |
| dislike_per_view | Number of dislikes per views of video | 0.000000 |
| engagement_rate_1 | Total comments and likes per views of video | 0.000000 |
| engagement_rate_2 | Total comments, likes, and dislikes per views of video | 0.000000 |
| q_score | Q score of video | 0.000000 |
| label_1 | Engagement level based on engagement_rate_1 of video | 0.000000 |
| label_2 | Engagement level based on q_score of video | 0.000000 |

## COUNTRY'S DATASET FEATURES
The second set consists of various datasets from different countries, which can be analyzed individually.
Also analyzing the dataset for different countries to understand the factors behaviour for indivisual country's Video to Trendiness.
Countries analyzed for experiments includes India, great Britain, France, Cannada, Japan, Mexico, Russia and United State.

< > Video ID

< > Trending date

< > Title of the video

< > Channel title

< > Category ID

< > Publish time

< > Tags

< > Views

< > Likes

< > Dislikes

< > Comment count

< > Thumbnail link

< > Description

# Whole Process Cycle
<img src="https://user-images.githubusercontent.com/129526047/230573386-c303cea5-3b7f-49a9-9d4b-b33d6704622d.png" width="500">   <img src="https://user-images.githubusercontent.com/129526047/230573546-73862639-3eec-4ed6-9b74-c44a7a237039.png" width="500">



# REFERENCES

[1] Gabielczak, P., Sobczyk-Kolbuch, M., & Rokicki, M. (2018). Analysis of factors affecting YouTube video popularity. International Journal of Electronics and Telecommunications, 64(3), 319-326.

[2] Song, Y., Shah, C., Jenkins, P., & Li, X. (2018). Understanding video popularity on YouTube: An empirical study. ACM Transactions on Multimedia Computing, Communications, and Applications, 14(3), 1-21.


[3] Petrovic, M., Osmani, V., & Litovski, V. (2020). Analysis of factors influencing video popularity on YouTube: A systematic literature review. Journal of Ambient Intelligence and Humanized Computing, 11(11), 4939-4962.




