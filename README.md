# Details for VKN2: Tasks 1 and 2 Medical Readmission Scenario/Data Dictionary

## Audience Background
You will build a Tableau data dashboard that the following executive leaders of your
organization will use to guide their decision-making. As described below, each leader has a
specific focus and area of expertise in the organization, but they do not have a technical
data analysis background like yours. As a result, the dashboard you build must be easy to
navigate and should present broad and understandable insights from the data relevant to
their perspectives.

**Executive Leaders**
* **Senior Vice President of Hospital Operations (SVP):** The SVP oversees hospital operations across all locations, ensuring regulatory
compliance, and high-quality patient care. They are interested in demographic and regional trends in patient outcomes.
* **Executive Vice President of Research (EVP)**: The EVP leads initiatives to identify patterns in patient care using data-driven strategies to reduce readmissions. They are interested in research that uncovers patterns in patient demographics, medical conditions, and hospital procedures that influence patient outcomes.
* **Chief Medical Officer (CMO):** The CMO oversees clinical operations, patient care strategies, and quality improvement initiatives across all hospital locations. They are interested in how readmission rates correlate with patient demographics, conditions, and treatment plans to enhance care to reduce readmissions.
* **Data Analytics Peers:** You work on a team of data analysts who have technical backgrounds similar to yours.Members of this team are research-minded and have a specific interest in how the design,
methodology, and results of a data analysis can be translated to specific business insights.Your peers are eager to hear you tell an engaging story about your data analysis, dashboard elements, and an explanation of your design choices.

## Views provided in dashboard

* Map showing percentage of readmissions by state: Highlights regional trends in readmission rates – included to support operational planning and geographic comparison.
[Audiences: SVP, CMO]
* Readmission by State and Gender percentages: Enables demographic analysis by location and gender – included to examine if certain populations are disproportionately readmitted.
[Audiences: SVP, CMO, EVP]
* Readmission rate vs. initial days in care: Shows trend between hospital stay length and readmission likelihood – included to explore care duration as a predictor of readmission.
[Audiences: CMO, EVP, Data Analytics Peers]
* Readmission by services provided: Compares outcomes across different service types – included to assess which departments or services may require review or support.
[Audiences: CMO, EVP]
* Initial admission reason by readmission rate: Connects initial conditions to readmission risk – included to help identify high-risk treatment areas.
[Audiences: CMO, EVP]
* Survey details by volume: Displays which care experience factors patients ranked as most important – included to align care improvements with patient expectations and priorities.
[Audiences: SVP, CMO]
* Total Charges vs. Readmission Rate: Evaluates whether cost of care is related to readmission risk – included to identify inefficiencies and inform financial decisions.
[Audiences: EVP, SVP, Data Analytics Peers]

## Script for presentation

Hi, my name is Bradley Wheeler, and I’m a software engineer; however, I am also a student of data science. For this project, I analyzed a medical readmission dataset tied to a national hospital chain. The scenario focused on reducing 30-day readmissions, which impact both patient care quality and CMS penalty costs.

I created a dashboard to help hospital executives explore the drivers of readmission. One of the charts I included is a **map showing readmission percentage by state**. This helps identify regional patterns that could guide resource allocation. Another important chart is a **line graph comparing readmission rate to initial days of hospital stay**, which shows how longer or shorter stays may relate to likelihood of return. I chose both because they help uncover trends rather than just static comparisons—supporting operational and care strategy decisions.

Two filters I added include **gender** and **complication risk**. Selecting gender changes all views to focus on either male or female patients, while filtering by complication risk highlights differences in outcomes between low-, medium-, and high-risk patients. These filters improve usability by letting stakeholders zero in on specific patient groups and tailor insights to their priorities.

To make the dashboard accessible, I used Tableau’s color-blind-friendly palette to ensure all viewers can distinguish between categories. I also included clear labeling on all charts and summary KPIs at the top for easy reference, which improves understanding for both technical and nontechnical users.

There are at least three important findings that can be deduced from this dashboard: 
1. The readmission rate is higher when the initial days is higher.
2. Some states have readmission rates that vary more greatly than others by Gender.  For example, if you look at Wyoming - it is clear the females return at lower rates than male patients.  To make this memorable, I could make a joke about cowgirls being more durable than cowboys; however, I'll refrain from this during the presentation.  But, now that I've said that - I bet you will remember this point regardless of the joke.  This is a narrative framing technique by allocating humor to a data point.
3. Survey details are clearly not being collected for a large number of patient responses as shown by the large bubble diagram. And men and women respond slightly differently.  There may be a deeper correlation that could be pursued. This readmission problem could be one of **contrast** and showing visual comparisons helps make that point.

Throughout my presentation, I used two storytelling elements to engage the audience and communicate insights clearly: **narrative framing** and **contrast**. Narrative framing helped structure the entire dashboard around a central question: “What factors are contributing to patient readmissions, and how can we reduce them?” By organizing the data into a story—from geographic patterns to service types, patient risk, and care experiences—I guided the audience step-by-step through the key variables influencing outcomes. This approach made the insights more meaningful and connected to real-world decisions.

The second storytelling element, **contrast**, was used to draw attention to differences between patient groups. For example, comparing readmitted vs. non-readmitted patients or high vs. low complication risk helped highlight actionable differences that might otherwise be overlooked. These comparisons were visualized using bar charts, line graphs, and side-by-side KPIs, making it easy for executive leaders to see where interventions may have the most impact.

During the dashboard creation process, I learned the importance of **structuring filters for executive usability**. Filters needed to be intuitive and relevant, such as gender, state, and admission reason. Overly complex filter options would have distracted from the goal of quick and meaningful exploration. From the presentation perspective, I realized that **visual clarity boosts confidence** in your analysis. By reducing clutter, using accessible color schemes, and emphasizing only the most relevant insights, I was able to ensure that both technical and nontechnical audiences could engage with the data effectively. These lessons will guide me in future projects to build dashboards that are not only informative but also user-centered and action-driven.