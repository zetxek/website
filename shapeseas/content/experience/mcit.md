---
date: "2020-12-09T14:27:40-05:00" # date in which the content is created - defaults to "today"
title: "Mastering the fundamentals"
draft: false # set to "true" if you want to hide the content
jobTitle: "Mastering the fundamentals" # job description/title. Fill-in
company: "MCIT" # name of the company you worked for. Fill-in
location: "Penn Engineering" # place/city/country for the experience. Fill-in.
duration: "2020-2024" # from-to, for example "2022-2024". Fill-in.

---

## MCIT

I began my graduate studies to deepen my computer science knowledge and practice. While I had learned alot from YouTube University, I was missing some of the fundamental instruction that computer science programs provide. In 2019 I applied to and was accepted into the [Master of Computer and Information Technology Online](https://online.seas.upenn.edu/course-catalog/mcit-online/) graduate program at Penn Engineering. Once the pandemic started, many graduate programs were upended, but MCIT Online had the infrastructure in place to continue.

#### Mastering the fundamentals

Formally studying computer science allowed me to focus on the fundamentals. Building software that is correct AND maintainable is not just coding. It requires an understanding of abstractions, algorithms, and modularity. I focused my studies on software development, data structures, discrete math, algorithms, computer/operating systems, computer and network security, wireless communications, networked systems, and database and information systems. I learned about abstractions from the level of circuitry and machine code up through operating systems and all the way to solutions of classical problems (e.g. efficient search, sort, etc). 

Towards the end of my degree I applied this to a project, `See the Science`.

##### See the Science

As part of a database course team project, I developed a web application to view information on the extraordinary, the ordinary, and the ugly sides of scientific publishing, including information on scientific authors, papers, grants, prize-winning papers and retracted papers from around the world.

Working in and around the social sciences, I wanted to spotlight the production of science so I pitched this to the team. I led the front-end and API development and collaborated on a [video demo](https://www.youtube.com/watch?v=Witku_fJgD4), project design document, and web application in a team of four. 

I learned that optimization matters when scaling a web application from hundres of records to tens of thousands. For example viewing a table of authors would take milliseconds with a sample dataset, but over 2 seconds with the full dataset, which feels unbearably slow in today's environment. To deal with this, I implemented a debounced search bar in the front-end to limit API requests to when a user was more likely to be done typing, created pagination in the API to limit the number of records being sent at any one time, rearranged complex queries to only perform array joins on the final list of paginated records instead of the full list of records, and built indices on tables that had sorting and searching on non-primary keys.

Key project elements include:

\- React front-end, including debounced author search and pagination to optimize display time

\- Express API, with pagination, filtering, ordering, and searching to serve information on scientists, papers, summary statistics, and co-authorship distance using Breadth-first search algorithm

\- Normalized MySQL database with over 15 tables deployed on AWS RDS

\- Merged data from 5 sources with over 140,000 authors, 47,000 articles, 11,000 grants, 44,000 institutions, including metadata on prize-winning papers and retractions
