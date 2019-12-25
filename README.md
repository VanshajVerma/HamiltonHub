# UrbanHacks-HamiltonHub
A hackathon I attended in Hamilton Public Library hosted by school kids.

# Inspiration
After hearing the representative of the City of Hamilton speak about the City's difficulties driving social interaction, and furthermore, upon hearing the local Hamiltonian's uplifting story of the library having such a positive effect on her mental/spiritual/emotional health, we wanted to create an app that increased socialization and interaction within the community. We wanted to ensure accessibility for those suffering from mental health problems.

# What it does?
HamiltonHub is a web app that grabs data from CoH's open data and CoH's event calendar to show points of interest and events happening within a 1km radius of a given location (e.g. the user). Our language for the back end plus main driver is Python, which contains scripts for scraping the CoH event calendar website and creating parsed CSV's and JSON's which would be fed into Google Fusion and Google Firebase, respectively. Our Python script also takes all the locations that we pulled from CoH open data and calculates those within an approximately 1km radius (0.01 degree lat/long) from the input location and includes only this data in the aforementioned CSV. We display a Google Fusion map on our webpage with interactive markers for more information.

# Challenges we ran into
- First time with a lot of Google Cloud API
- First time building a webscraper
- Preprocessing dirty data
- Python module dependencies

# Accomplishments that we're proud of
- Overcome many firsts
- Being a ragtag group of individuals that ended up being a good fit team-wise
- Being able to problem-solve through collaboration (albeit they may have been somewhat trivial problems)

# What we have learned
- There is a lot we don't know
- Making use of FireBase and implementation of Google API
- parsing the data
- how to survive and code with less amount of sleep
- How to self-motivate

# What's next with HamiltonHub
- Further linking the front-end and back-end
- Hosting the web-page on a server instead of just our Git repo
- Proficiently using Firebase

# Built with
- CSS
- FireBase
- Fusion
- HTML
- Python

# Order of running the file
- UH18.py runs first
- read_write_open_data.py runs second
- Step Outside folder contains our interface and runs last