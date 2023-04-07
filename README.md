# YT_Algorithm_Analysis_Using_R





# YouTube Video Engagement Dataset

This project aims to analyze the impact of the YouTube algorithm on video recommendations by building and utilizing an annotated dataset of 23,738 videos collected from 72 YouTube channels in Vietnam.

# Introduction

YouTube is one of the largest online video-sharing platforms, providing content creators with a space to share their videos and earn extra income. For content creators, understanding whether their videos will be engaged by viewers is essential for improving the quality of their content before publishing. In this project, we build a dataset of videos collected from various categories and evaluate metrics for measuring video engagement.

# Dataset

We collected a dataset of 23,738 videos published over a period of 12 years, categorized into four categories: comedy, travel-and-events, education, and science-and-technology. The dataset was collected from 72 YouTube channels in Vietnam.

Using a novel measure called the Q score, we annotated videos with three levels of engagement: Engage, Neutral, and Not Engage. From this supervised dataset, we constructed a multimodal model to infer the degree of engagement based on the content of a YouTube video, such as title, audio, thumbnail, video, and tags.

# Purpose

The purpose of this project is to analyze the impact of the YouTube algorithm on video recommendations. By using our annotated dataset and our metric for measuring video engagement, we aim to provide insights into how the algorithm selects and recommends videos to viewers.

# Conclusion

We believe that our dataset and metric will be useful for engagement analytics and studies on social media content. Our project provides a foundation for future research into the YouTube algorithm and its impact on video recommendations.


# Metadata
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

