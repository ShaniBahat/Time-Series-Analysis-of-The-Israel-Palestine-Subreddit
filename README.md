# Time Series Analysis of The Israel Palestine Subreddit

This study examines the temporal and social dynamics within Reddit, a social news aggregation, content rating, and forum platform, focusing on an in-depth analysis of the r/IsraelPalestine subreddit. It serves as a vital forum for debates surrounding the Israeli-Palestinian conflict and offers a lens into how digital communities respond to real-world events. The research employs time series analysis to quantify the ebb and flow of community engagement over time. 


By analyzing daily submissions from September 2023 to October 2024, we identify periods of heightened discussion that often correspond with significant events, such as the effect of October 7th and the subsequent war. This temporal perspective reveals cyclical patterns and trends in discussion intensity, shedding light on the responsiveness of online communities to external triggers. In addition to the primary focus on time series analysis, complementary insights from social network methodologies are used to understand the interconnected nature of user interactions during peak activity periods. Together, these approaches provide a framework for understanding the interplay between online discourse and global events, contributing to a deeper comprehension of how digital forums reflect and amplify real-world dynamics.

The submissions classification is done using Hugging Face Transformers pipeline.

![# submissions](dailynumberofsubmissions.png) 

This chart shows the dramatic spike in community activity following October 7th, 2023, reaching nearly 500 daily submissions before gradually declining. The timeline clearly demonstrates how online communities respond immediately to major real-world events, with smaller spikes corresponding to subsequent developments in the conflict.

A complete detailed process and evaluation of pro-Israeli and pro-Palestinian engagement patterns and global event impact can be found in the accompanying PDF file.

#### Data
- **Source**: r/IsraelPalestine subreddit
- **Download Process**: Reddit API data extraction using the attached script
- **Time Period**: September 2023 to October 2024 (14 months)
- **Data Type**: Reddit submissions and comments


#### Tools
`Hugging Face Transformers`, `TensorFlow`, `NetworkX`.

