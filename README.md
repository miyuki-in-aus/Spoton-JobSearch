# Spoton-JobSearch
Helsinki University, Final Project for Building AI Course

![AI Network](https://raw.githubusercontent.com/ChatGPTAssets/ai-images/main/ai-network-01.png)


## Summary

This project helps job seekers find truly personalised job opportunities using a new matching algorithm. It goes beyond CV data by considering workplace culture, company size, and preferred location, enabling more accurate and meaningful role recommendations—without relying on recruiters.


## Background

Modern job platforms often fail to provide relevant recommendations because they depend heavily on keyword matching or CV-only data. This leads to an overwhelming number of irrelevant suggestions, repeated listings, and a reliance on recruiters who may prioritise commissions over candidate fit.

Key problems this project addresses:

- Recommendations based only on CV data
- Time wasted reviewing irrelevant roles
- Repeated suggestions of already-applied jobs
- Lack of consideration for culture, size, and location fit
- Cost and time inefficiencies caused by recruiter-driven processes


## How is it used?

Users interact with a curated list of recommended job openings. As they engage with the system, the algorithm gradually learns their preferences, strengths, and suitability. Over time, it can even propose opportunities outside the user’s initial search criteria—helping uncover roles they may not have known to look for.

Deep learning methods and sigmoid-based scoring are used to refine predictions and improve matching accuracy as more user data becomes available.

Users and needs:
- Job seekers who want personalised and accurate recommendations
- People overwhelmed by irrelevant or repetitive job suggestions
- Candidates who value culture fit, company size, and location—not just required skills

## Data sources and AI methods
This project requires diverse datasets to train and refine the matching algorithm, including:
- Job openings
- Company information (size, culture indicators, location, industry)
- Job seeker skillsets
- Required skills and suitability patterns for different roles
- User-specific preference data learned dynamically over time
- Broader contextual data such as labour-market trends

Because these datasets are too large to collect manually, the project relies on open-source and publicly accessible databases. These sources offer structured, high-quality, frequently updated data suitable for machine learning.

Potential open data sources:

Open skills / skillset data
O*NET (US Department of Labor)
https://www.onetcenter.org/database.html

Job titles, occupations, and skill taxonomies
ESCO (European Commission)
https://esco.ec.europa.eu/en

Company data
OpenCorporates
https://opencorporates.com/

Job market datasets
Kaggle open datasets
https://www.kaggle.com/datasets

General open data repositories for AI training
Google Dataset Search
https://datasetsearch.research.google.com/

Data.gov
https://www.data.gov/

These sources enable the system to build a robust matching model that incorporates both objective criteria and personal preferences.

## Challenges

This solution cannot fully replace existing job platforms and faces several limitations:
- Personal data: Only limited, consent-based user information can be used.
- Platform boundaries: It relies on external job databases and does not handle applications itself.
- Cost: Deep-learning features may require paid support to remain sustainable.

## What next?

The project could grow by integrating:

- Real-time job feed APIs
- More advanced deep-learning architectures (e.g., Transformers)
- A feedback loop to continuously refine recommendations
- UX design improvements to help users express preferences more easily

Future development would benefit from skills in:
- Backend engineering
- Data engineering
- Model deployment (MLOps)
- UI/UX design
- Collaboration with career advisors or labour-market specialists


## Acknowledgments

- Credit to all open-source datasets and tools used in this project.
- No external code or copyrighted materials have been used without permission.
