# Augmented-AI-Workflow--Data Analysis (Research-paper)
As with any other story, the journey of data analysis seems to have come a long way since its inception. As you surf through its history, the BI has moved from rigid, IT owned systems to more flexible, business-oriented tools that has not only enabled a more business-facing Data Analyst mindset but has also added a flood of pretty, easy filters ,drill downs and consolidations to help. What exactly is still a limitation are its static dashboards.

Today — with the rise of cloud-native data warehouses and advancements in scalable inference methods — we’re at the cusp of a new phase that can not only afford better, faster processing of data, but also lets operational data analysts impact business decisions like never before. I call this phase Data Analyst 3.0. 

Learning Technology through History

Browsing through the pages of history, its fascinating to see how far we have come. Data Analysis in the job market started with a single person within an IT team who had all the relevant knowledge and skills required to become an expert in data. Partly the smaller number of resources had a lot to agree with the Data that wasn’t big or wide which meant that learning new data skills like (SQL and Excel) should not have been a problem and the process of sending over a CSV to answer almost all the business questions worked just fine.

But a significant trend that came into perspective was the failure of data requests in the hand off between IT and the business. This can be reasoned due to the lesser known ways of making data infrastructure consumable to the Excel user. These limitations can be categorized into two folds:

One question, one answer: Most of the iterative questions put up by the business had single natured answers. This meant, every new question needed getting back in line and waiting until somebody stopped asking questions altogether.

Vast gap between data and business users: The people involved in decision making could not participate in the data exploration which is where most of the discoveries happen. So, all you got were rolled-up KPIs and consolidations but no “oh yes! ah-ha” moments.

Over the years, the system has seen a lot of progress with the advent of more business centric data modelling, BI and various visualization tools like Tableau, PowerBI: the second wave of BI.

This second wave dashboards work really well to answer the most generalized business question “what has happened?”. However, these dashboards are not well equipped to answer more specific questions where the businesses need Analyst to add the most value – when something goes wrong (like in those weekly meetings and the VP of the sales asks “Why did sales drop by 50% in a particular quarter?”.

This happens because all along the data exploration and diagnosis were being made on consolidations and if you only operate on aggregates, you can’t explore in detail. Of course, Analyst can leverage the use of ‘filters’ and ‘drill downs’ on dashboards but as the columns and the unique attributes within each column grow, the ways they could slice the data explodes (20 stores * 3 regions * 20 states * 70 cities… you get the idea!).

Also, there are days when an Analyst may have to start diagnosis for a particular ad-hoc question from scratch. This leads to reinventing the wheel which subsequently hampers decision making velocity. Hence, we end up in the same situation as first and second wave – only this time we get stuck on answering the “why” questions.

Augmented AI Workflow: Answering the ‘why’

In order to answer questions like, “Why does the data look the way it does?” and “what updates could we gather from previous week reports?”, it is imperative to understand the new age technological advancements:

Cloud storage, logical pools: The availability of cheap cloud warehouses has already expediated the data querying to 25% - 50% making it easier to extract data from denormalized tables rather than traditional star schemas. Now all a Data Analyst has to rethink is to model the data for data diagnosis vs. reporting.This again drills down to two major factors:

Granularity: Keeping in mind the requirements of the business, the modeled tables should be drilled down to their lowest granularity. For example, if the business cares about the “Avg Transactions made in a quarter” or “Customer conversion rate”, then the subsequent demonstrated tables should be constructed at the transaction and user grain.
Data Diversity: The traditional procedure of cherry-picking dimensions leads to human bias and removes potential signals from the data. Allowing the inclusion of every possible dimension should allow a Data Analyst to answer most of the follow-up questions and investigate the trail wherever it leads. A consolidated report can answer major chunks of top-level questions, but it may not fulfill the requirement of follow-up questions put forward in a Monday morning meeting.
Algorithmic developments, Sisu: Making use of proactive analytics in scalable inference methods in tools like Sisu, Analyst can leverage real time structured data. Instead of relying on descriptive dashboards and mining for insights from big tables, Sisu continuously assesses incoming information to help answer more difficult business questions like company strategy, market condition, patient safety.


![Augmneted Ai Image](https://user-images.githubusercontent.com/79339159/109707328-08d62800-7b68-11eb-89d9-de4ea6560e34.png)







How can it aid in real time Analysis?

Assist in responding to ad-hoc questions put up by the Business arising out of aggregated numbers.
Help in answering 10x more questions linked to one major top - level question.
With these recent algorithmic developments , the concept of data visualization and BI tools can be augmented to whole other level where an Analyst can not only put forward the counts in front of the Business but can also share proactive solutions with the help of AI- powered workflow. Lets enable the future of Analysis to unfold the best!

