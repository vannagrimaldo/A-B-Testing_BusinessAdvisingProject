# E-News Express A/B Testing Project

## Business Context

The advent of e-news portals has provided a significant opportunity for rapid access to global news updates. Information from these portals is retrieved electronically from online databases, processed using various software, and transmitted to users. The advantages of transmitting news electronically include faster content access and the ability to utilize diverse technologies such as audio, graphics, video, and other interactive elements that are either not utilized or uncommon in traditional newspapers.

E-News Express, an online news portal, aims to expand its subscriber base. With every visitor taking specific actions based on their interests, the company plans to analyze these behaviors to understand user preferences and enhance engagement. Executives at E-News Express have observed a decline in new monthly subscribers compared to the previous year, attributing it to the current webpage’s design, which may not effectively engage users long enough to encourage subscription.

To address this, E-News Express is implementing an experimental technique known as **A/B testing**. This method involves analyzing user responses to two variants of a product to determine which version is more effective based on chosen metrics.

## Objective

The design team has researched and developed a new landing page featuring an improved outline and more relevant content. To test the effectiveness of this new landing page in attracting new subscribers, the Data Science team conducted an experiment by randomly selecting 100 users and dividing them equally into two groups:

- **Control Group:** Served the existing landing page.
- **Treatment Group:** Served the new landing page.

Data regarding user interactions with both versions of the landing page was collected. As a data scientist at E-News Express, you are tasked with exploring the data and performing a statistical analysis (at a significance level of 5%) to determine the effectiveness of the new landing page in gathering new subscribers by answering the following questions:

1. Do users spend more time on the new landing page compared to the existing one?
2. Is the conversion rate (the proportion of users who visit the landing page and subscribe) for the new page greater than that of the old page?
3. Does the conversion status depend on the preferred language?
4. Is the time spent on the new page consistent across different language users?

## Data Dictionary

The dataset contains information regarding user interactions with both landing page variants:

- **user_id:** Unique user ID of the person visiting the website.
- **group:** Indicates whether the user belongs to the control group (existing landing page) or treatment group (new landing page).
- **landing_page:** Specifies whether the landing page is new or old.
- **time_spent_on_the_page:** Time (in minutes) spent by the user on the landing page.
- **converted:** Indicates whether the user became a subscriber of the news portal.
- **language_preferred:** Language chosen by the user to view the landing page.
