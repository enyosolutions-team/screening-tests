## setting up an architecture.

We have a client that want to build a **SaaS** to offer a service to help companies manage their recruitment process. A recruitment is the process of finding a new staff member or contractor for a position. Features includes : 

- job listings (inside the app)
- Mini website for listing job posting.
- Posting jobs to other platforms.
- Monitoring performance of postings.
- Import data from linked In or Viadeo
- Candidates management
- Spontaneous candidates (candidate not coming from job postings)
- Interviews management (multiple inteviews with various people in the company
- integrated communication with the candidates via emails.
- Integrated calendar that can be synched with externals calendars.
- Automated communication to the candidates when the process is advancing or is terminated.
- SaaS offers and profile management.


Write a document detailing the architecture you'd choose to implement this Human Ressources Recruitment management SaaS.
- Layers
- Detailed Data-model and relations (class diagram).
- Softwares list with an explanation (what database, what http server, what solution for search etc). You can also list tools that might be useful for the scaling, backup ping, security etc.
- Would you do sql or no sql why ?

- How do you manage the clustering of data to manage :

-- authentication

-- data clustering (avoid one client seeing data of another client)

- backup.


## performance

Your offer is posted on hackernews.com (very busy website). As a result you have 1.000.000 users on your website overnight. They are trying to log in and use the platform.
- How can you scale your app to match the demand ?
- how can you improve your architecture above for better performance ?


## Attack

You now have a russian hacker that is attacking you by a DDoS

- How do mitigate that attack ?
- How do you stop that from happening in future


## Detecting profile 

We have an idea to go scan linkedIn to find candidates that match the job description with a matching profile on linkedIn. 
- How do you scrap the data ? 
- how do you match a profile with a job offer ?
- How do you tell if a person is looking for a new position.

