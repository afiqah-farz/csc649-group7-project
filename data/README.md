# Dataset: IT Job Interview Q&A

This folder holds the custom dataset for our IT interview chatbot.

| Item | Detail |
|---|---|
| File | interview_it_questions.csv |
| Format | CSV (UTF-8) |
| Columns | Question, Answer |
| Size | 33 question–answer pairs (34 lines including the header) |
| Domain | Job interviews in the IT field for students and fresh graduates |

## What the dataset covers

- **Projects and work habits:** projects you are proud of, deadlines, preparing for a project, mistakes, personal projects
- **IT career:** why IT, staying up to date, certifications, education, areas to learn, AI in the industry
- **Technical knowledge:** IP address, CPU, command line, operating systems, network security, web development, Agile and Waterfall, Git and GitHub, databases, continuous integration
- **Troubleshooting scenarios:** troubleshooting process, slow website, user cannot log in, failing API, debugging a program

## Where the data came from

The questions were collected from the articles below. The line numbers match the line numbers shown for the CSV file on GitHub (line 1 is the header).

| Source | Article | Lines |
|---|---|---|
| SEEK Employer Malaysia | [The 5 Most Important IT Interview Questions Every Hirer Must Know](https://my.employer.seek.com/market-insights/article/the-5-most-important-it-interview-questions-every-hirer-must-know) | 2, 4, 5, 8, 9 |
| Coursera | [10 Common IT Interview Questions and How to Answer Them](https://www.coursera.org/articles/common-it-interview-questions-and-how-to-answer-them) | 3, 6, 7, 10, 11, 14–17 |
| FDM Group | [Top 9 Questions to Expect in a Software Developer Job Interview](https://www.fdmgroup.com/software-developer-interview-questions/) | 12, 13 |
| Exec | [What Questions Can You Expect in an IT Interview?](https://www.exec.com/learn/it-interview-questions) | 18, 19 |
| Indeed | [13 Common Technical Interview Questions Plus Example Answers](https://www.indeed.com/career-advice/interviewing/common-technical-interview-questions-and-answers) | 20, 22–25 |
| Forage (via ASU Career Services) | [30+ Common IT Interview Questions (and How to Answer Them)](https://career.eoss.asu.edu/blog/2024/12/30/30-common-it-interview-questions-and-how-to-answer-them/) | 26–30 |
| Analytics Insight | [Must-Know CSE, IT Interview Questions to Crack Your First Job](https://www.analyticsinsight.net/education/must-know-cse-it-interview-questions-to-crack-your-first-job) | 21, 31–34 |

**How the answers were written:**

- The article gave an advice for a question (SEEK, Coursera, FDM Group, Exec, Indeed) then the answer was summarised from the advice in our own words.
- The Forage and Analytics Insight articles list questions or topics without the full answers. Based on this, those answers were written for this dataset with standard IT knowledge. The CPU question (line 14) was suggested by the Coursera article as a variation of the IP address question.
- No text was copied from the sources.
- Answers were checked with AI for assistance (Claude) only then checked and edited by the group against the sources and our course notes.
