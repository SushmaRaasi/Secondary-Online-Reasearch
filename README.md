# Secondary-Online-Reasearch

- [Project Description](#project-description)
- [Business Problem](#business-problem)
- [DataSet](#dataset)
- [Approach](#approach)
- [Tech Stack Used](#tech-stack-used)
- [Data Preparation](#data-preparation)
- [Locating the Metrics In Dataset](#locating-the-metrics-in-Dataset)
- [Setting up Slicers](#setting-up-slicers)
- [Creating Performance-based Metrics](#creating-performance-based-metrics)
- [Trend-based Views](#trend-based-views)
- [Creating Performance-based Metrics](#creating-performance-based-metrics)
- [Analysing the Dashboard](#analysing-the-dashboard)


### Project Description
###### About the Data Operations Team
<p>Data Operations Team performs secondary research online and gathers relevant information about private companies per the team’s methodologies. Each company’s information is stored in a profile identified by ProfileID. Profiles are tracked as Private Equity (PE), Venture Capital (VC), Mergers & Acquisitions (M&A), etc., based on the company’s backing. On each profile, multiple workflows are worked on by the researchers in the data operations teams. Researchers belong to various research groups with expertise in understanding details about a company’s corporate decisions like fundraising, industry group changes, etc. Each workflow is created by an automated system or by other researchers who find more information about the company. Time taken to complete the workflow is tracked in seconds, and the amount of data added to the profile is tracked as benchmark points. Workflows are categorized based on the information that is being tracked, e.g., if it is a new profile where the company has raised funding, a New Company workflow is created. If an existing company (in our database) raises money, then a New Round workflow is created, and so on. Workflow is also tagged with the various process types that indicate from which team the data is coming from, e.g., news (Post News, News), client request (Special Request), product demo (Demo Update), etc., and the regions from where data is gathered, Greater China, Europe, etc. Each workflow goes through various stages, from its creation to closure. As shown below, Sometimes workflows are created with incorrect details or on the wrong profile, which cannot be worked on. Such workflows are “unassigned” by the team that receives them and is completed by a more relevant team.</p>
