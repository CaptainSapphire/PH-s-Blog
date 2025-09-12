---
layout: post
title: "Netflix Data Science Project"
date: 2025-09-12
featured-img: https://i.ytimg.com/an_webp/GTf-p7YnqGU/mqdefault_6s.webp?du=3000&sqp=CJC-kcYG&rs=AOn4CLCKlC3RLhrClb7MdJcIBB2_BvL5Yw
---
# Data Science Project: Netflix

## The start of the story
One day, I googled potential data science projects I could do, and found a reddit post with a range of links. I clicked on the one saying Netflix, since that piqued my interest. I was taken to a Medium article, which you do typically have to pay for. However, I gave the link to ChatGPT, and it gave me the summary on how to set up the project. <br><br>

Once I set RStudio and Anaconda/Python on my computer, I jumped straight into the code.

## Taking a look at the code
From here, the project can be sliced into 4 parts. The setup (where I import libraries and time conversions), and then the three distinct graphs.
### 1. Most watched Profile
```
df %>%
  group_by(`Profile Name`) %>%
  summarise(TotalMinutes = sum(Duration_minutes, na.rm = TRUE))
```
This sets up our summaries, in minutes, of what profiles watch the most. 

```
ggplot(df) + 
  geom_boxplot(aes(x = `Profile Name`, y = Duration_minutes))
```
This makes our boxplot graph (a visual view of the summary from above). This is also the format, as you will see, for making any graph. 

### 2. Most Watched Series
```
# Most Watched Titles
df %>%
  count(Title, sort = TRUE) %>%
  top_n(10) %>%
  ggplot(aes(x = reorder(Title, n), y = n)) +
  geom_col(fill = "darkred") +
  coord_flip() +
  labs(title = "Top 10 Most Watched Titles",
       x = "Title", y = "Watch Count") +
  theme_minimal()
```

### 3. Most Watched Device

Although this graph is a little confusing because of how the devices are titled, we watch Netflix on our TV the most (that's the main conclusion meant to be drawn).

## Making the Presentation
Putting the presentation together was relatively simple, it was just done in powerpoint. 

## The Video + Repo
From there, I leaned the back of my computer against a wall and proped my phone on top of the laptop monitor. I recorded my screen in powerpoint, and edited it all in capcut. It's all free, and I would reccomend recording the final results of your projects. <br><br>
The repository is accessible [here]()

## Things I'd do differently next time
I would definitely label my x-axis with the time units so my final analysis is more coherent of each graph. 

## Final Thoughts
This post was meant for a couple months ago, but I found the old draft and figured I'd finish it. 
