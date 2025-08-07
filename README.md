# Enhancing Airbnb Listings: Aligning Visual Appeal with Guest Experiences in Athens
## Dataset Source: https://insideairbnb.com/get-the-data/
### Business Analysis with Unstructured Data | Team Assignment Grade: 88.75/100
### Professor Comment:
The team delivered a very good project that explored the mismatch between Airbnb listing photos and actual guest experiences in Athens, using a combination of image and text data. The presentation was well-structured, and the initial framing of the problem showed a solid understanding of the business context and platform trust dynamics. Drawing from a substantial dataset—14,000 listings, 770,000 guest reviews, and 100 representative images—the team was able to extract meaningful patterns, including a weak negative correlation between image sharpness and review sentiment.

The technical work was competently executed, with good choices of tools and frameworks to manage large-scale unstructured data. However, the presentation would have benefited from a clearer explanation of why those specific tools and techniques were selected. Word clouds and graphs helped visualize language usage across reviews, but the multilingual nature of the data introduced ambiguity. It would have been valuable to see a more critical discussion of whether translating reviews was considered, and what the implications of such a choice might have been—both in terms of insight quality and potential loss of nuance.

While the findings were interesting, particularly the sentiment-to-image sharpness correlation, this part of the analysis could be strengthened further with more robust statistical validation. The methodology could also be enhanced by developing more sophisticated trust metrics, validating the proposed personalization recommendations, and incorporating pricing factors into the sentiment analysis. On the visualization side, there is room for improvement in terms of showing temporal trends, enabling neighborhood comparisons, and creating more interactive dashboards for deeper exploration.

The ethical analysis report, submitted separately, touched on the key issues but remained fairly basic and descriptive. A more critical engagement with the ethical dimensions—such as potential bias in visual analysis or the implications of automating trust scores—would have strengthened this component of the project.

In summary, this was a very good project with strong foundations and thoughtful use of multimodal data.
### Assignment Instructions:
Description of Assignment:

You will work in your teams to analyze a real-world business problem using at least two types of unstructured data (e.g., text + image, video + text) and propose strategic recommendations.
You will use basic Python tools to extract and analyze data, and your main deliverable will be a 10-minute presentation aimed at a decision-making audience.
The project also encourages reflection on ethical concerns in handling unstructured data (e.g., privacy, bias, transparency).

You are encouraged to combine different data types to deliver a deeper analysis. For example:

Text sentiment from YouTube comments + image themes from thumbnails
Product reviews (text) + brand imagery (image) from Instagram
Video transcripts + visual content trends across competitors
They should frame this combination in terms of:

What unique insights come from using multiple data types?
What would be missed if only text or only image/video were used?
 

Deliverables
1. Presentation (Primary Deliverable – 75%)
A 10-minute pitch to simulate a consulting team presenting to business stakeholders.
Structure:

Introduction (1–2 min): Define the business problem and the type of unstructured data used
Findings (3–4 min): Share key insights from your analysis with visual support (e.g., charts, word clouds, image/video screenshots)
Business Recommendations (2–3 min): What strategic actions should the business take based on your analysis?
Ethical Considerations (1–2 min): Reflect on how data privacy, algorithmic bias, or misrepresentation could impact your findings or their use
2. Technical Notebook (Supporting Deliverable – 15%)
A single Jupyter Notebook or .py file that shows:

At least two types of unstructured data processed (e.g., text + image, video + text)
Simple processing with code cells and markdown:
o    Text: nltk, textblob, TF-IDF, wordcloud
o    Image: OpenCV, object recognition, metadata extraction
o    Video: extract captions or frames, get metadata, use thumbnails
Include clean, readable code with explanations (can be minimal if visual results are clear)
3. Ethical Brief (Written Reflection – 10%)
1-page written response to the following:

What ethical risks did you encounter in working with this data?
How would you address those risks if this were a real business decision?
Example prompts:

Could your insights reinforce stereotypes or bias?
Are you using data that violates someone’s privacy?
Could decisions based on your results affect vulnerable groups?
