# RoomPal-Housing-Shared-Living-PropTech-Data-Analysis-
## Project Overview
RoomPal is a data analysis project focused on understanding housing experiences, shared accommodation, roommate dynamics, housing search challenges, fraud, trust, and the use of digital housing platforms in Nigeria.
The analysis uses responses from the Apartment, House-Sharing &
Roommate Experience Survey. The objective is to transform raw survey
responses into structured, evidence-based insights that can support
housing platform development, property management, policy discussions,
and user-centered decision-making.

The project was conducted entirely in Microsoft Excel, using data
cleaning, Pivot Tables, Pivot Charts, filtering, sorting, descriptive
analysis, and Excel formulas.

Important: This project is descriptive and exploratory. It does
not use predictive modelling or advanced statistical modelling.

# What Nigerian Housing Data Reveals About Roommates, Rental Stress and Trust in PropTech

## Introduction

Finding a place to live should be straightforward: identify a suitable property, assess the cost, confirm that it is legitimate, and move in.

For many people, however, the housing search is far more complicated.

The process can involve unreliable listings, high costs, limited availability, agents, informal referrals, unfamiliar landlords, potential roommates, and—perhaps most importantly—a lack of trust.

This analysis explores these challenges through the **Apartment, House-Sharing & Roommate Experience Survey**, a primary survey designed to understand how people in Nigeria experience renting, shared housing, roommate arrangements, housing searches, and digital housing platforms.

Rather than looking at housing purely as a real estate problem, the analysis approaches it as a **user experience and trust problem**.

Using **Microsoft Excel**, the dataset was cleaned, segmented, analyzed and visualized through:

- Pivot Tables
- Pivot Charts
- Frequency distributions
- Comparative analysis
- Excel formulas
- Dashboard visualizations

The objective was to understand:

- Who the respondents are
- How they currently live
- How they search for housing
- What makes the housing process stressful
- What challenges they encounter with roommates and shared housing
- What influences trust in digital housing platforms

The findings point to a central theme:

> **Housing access is not only about finding a property. It is about finding a property, person and process that users can trust.**

---

## 1. Story of Data

The story begins with the people behind the housing decisions.

The dataset comes from a primary survey titled **"Apartment, House-Sharing & Roommate Experience Survey."** Unlike datasets collected from public databases or external platforms, this dataset captures self-reported experiences directly from respondents.

The survey covered several dimensions of the housing journey, including:

- Demographics
- Current living arrangements
- Rental experiences
- Shared housing experiences
- Roommate arrangements
- Housing search methods
- Housing search challenges
- Housing search stress
- Fraud experiences
- Trust in digital housing platforms
- Verification preferences

Each respondent represents one row in the dataset, while each column represents a survey variable.

### Key Variables

Some of the major variables analyzed include:

- Age group
- Gender
- Location
- Employment status
- Student status
- Current living arrangement
- Length of stay in a city
- Previous rental experience
- Previous shared housing experience
- Housing search stress
- Fraud experience
- Platform trust
- Verification preferences

This structure made it possible to look beyond individual responses and identify broader patterns.

For example:

- Demographic variables provided context for understanding living arrangements.
- Current living arrangement became an important outcome variable.
- Housing search stress provided insight into the difficulty of finding accommodation.
- Shared housing experiences revealed roommate-related challenges.
- Platform trust provided insight into the role of verification and security in PropTech.

### Data Characteristics and Limitations

The data is **cross-sectional**, meaning it represents a snapshot rather than changes observed over time.

This makes it useful for understanding current patterns, but it also means the findings should be interpreted as **descriptive rather than predictive**.

Important limitations include:

- Respondents reported their own experiences, which may introduce recall or perception bias.
- The sample consists only of people who participated in the survey.
- The findings cannot automatically be generalized to the entire Nigerian population.
- Many variables are categorical, limiting the use of advanced statistical and predictive techniques.

These limitations do not make the data less useful. Instead, they define how the findings should be interpreted.

The analysis tells us about **the experiences represented in the survey**, rather than claiming to describe every Nigerian renter.

---

## 2. Data Splitting and Preprocessing

Before looking for insights, the data had to be made reliable enough to analyze.

The raw survey responses were transformed into a structured **Clean Data** worksheet that became the primary source for the analysis.

### Data Cleaning

The cleaning process focused on three major areas:

- Duplicate records
- Data consistency
- Missing information

Duplicate records were reviewed using the respondent identifier to prevent the same response from being counted more than once.

Categorical variables such as gender, employment status and living arrangement were standardized to ensure that differences in spelling, capitalization or formatting did not create artificial categories.

The column headers were also checked against the **Data Dictionary** to ensure that each variable accurately represented the original survey question.

### Missing Values

Missing responses were deliberately not replaced with assumptions.

Instead:

- Blank responses were preserved.
- Missing values were excluded from relevant calculations where appropriate.
- Important missing information remained represented as blank or **"Not specified."**

This approach helped protect the integrity of the respondents' original answers rather than introducing values that were never provided.

### Analytical Transformation

Because this was a categorical survey dataset, there was no need for numerical normalization or scaling.

Instead, the main transformations involved:

- Grouping responses
- Calculating frequencies
- Calculating percentages
- Creating summary tables
- Building Pivot Tables
- Creating Pivot Charts
- Comparing respondent groups

### Analytical Segmentation

The dataset was also logically separated into explanatory and outcome variables.

**Explanatory variables included:**

- Age
- Gender
- Employment status
- Student status
- Location
- Length of stay

**Outcome variables included:**

- Current living arrangement
- Housing search stress
- Shared housing experience
- Fraud experience
- Digital platform trust

> **Important:** This was not machine-learning data splitting. The segmentation was analytical rather than a train-test split for predictive modeling.

---

## 3. Pre-Analysis

The pre-analysis stage was about asking questions before attempting to answer them.

The initial review suggested that the respondent population was largely made up of working-age individuals, with notable representation from students and early-career professionals.

The data also appeared to have a strong urban orientation.

This mattered because urban housing markets often bring together:

- Affordability pressures
- Mobility
- Competition
- Limited housing availability
- Demand for rental accommodation
- Demand for shared accommodation

### Initial Questions

The analysis began with several key questions:

- Does age influence living arrangements?
- Does employment status influence housing choices?
- How stressful is the housing search process?
- Does previous rental experience reduce housing search stress?
- Why do people choose shared housing?
- What makes a roommate relationship successful?
- What causes people to distrust housing platforms?
- Which verification features could increase trust?

### Early Patterns

The preliminary analysis suggested that age and employment status could be important factors.

Students and younger respondents appeared more inclined toward shared accommodation, while longer-term residents and people with greater economic stability appeared more likely to live independently.

A significant portion of respondents also reported moderate to high levels of stress during housing searches.

More importantly, the initial analysis suggested that this stress was not necessarily limited to people who were new to renting.

This raised an important hypothesis:

> **Perhaps housing search stress is a systemic problem rather than a lack-of-experience problem.**

### Shared Housing

The shared housing analysis raised another set of questions.

Many respondents had previous experience with roommates or shared accommodation.

But affordability was not the only consideration.

Other factors included:

- Compatibility
- Reliability
- Responsibility
- Communication
- Safety
- Lifestyle differences

### Trust

Early patterns indicated that verification of listings and users was an important concern.

Fear of fraud and misinformation appeared closely connected to people's comfort with digital housing platforms.

The open-ended responses added an important human dimension.

Respondents repeatedly referenced themes such as:

- Affordability
- Safety
- Trust
- Communication

These responses appeared to reinforce the patterns emerging from the structured survey questions.

At this stage, however, these were hypotheses—not final conclusions.

The dashboards were built to test whether these patterns held up under deeper analysis.

---

## 4. In-Analysis

The in-analysis stage moved from asking what might be happening to exploring why those patterns might exist.

### Demographics and Living Arrangements

One of the clearest emerging relationships was between **demographics and living arrangements**.

Age and employment status appeared to influence whether respondents:

- Lived alone
- Lived with family
- Lived with roommates
- Used other shared accommodation arrangements

Younger respondents and students showed greater inclination toward shared accommodation, potentially reflecting affordability and flexibility considerations.

### Housing Search Stress

The analysis also revealed something more surprising.

Housing search stress appeared to persist even among people with previous rental or shared housing experience.

This challenged a straightforward assumption:

> **Experienced renters should find the housing process easier.**

Instead, the evidence suggested that the difficulty may lie within the housing system itself.

Potential sources of friction include:

- Market constraints
- Information gaps
- Unreliable listings
- High costs
- Limited availability
- Competition
- Trust concerns

These factors may create friction regardless of how experienced the renter is.

### Shared Housing and Compatibility

Shared housing revealed another layer of complexity.

Living with others can make housing more accessible and affordable, but it also introduces interpersonal risk.

Respondents expressed concerns around:

- Compatibility
- Reliability
- Accountability
- Lifestyle differences
- Communication
- Safety
- Privacy

In other words, finding a roommate is not simply about finding someone who can share the rent.

It is about finding someone whose habits, expectations and values can coexist with yours.

### Trust in PropTech

Trust became even more important when digital platforms entered the picture.

The analysis suggested that fear of fraud and the absence of strong verification mechanisms could reduce willingness to use housing platforms.

Respondents showed a preference for:

- Verified listings
- Identity checks
- Property verification
- Secure communication
- Transparent user profiles
- Platform accountability

This suggests that trust is not a feature added after a housing platform has been built.

> **Trust is part of the product itself.**

### Analytical Tools

The analysis was conducted entirely in **Microsoft Excel** using:

- Pivot Tables
- Pivot Charts
- Filtering
- Sorting
- `COUNT`
- `COUNTA`
- Percentage calculations
- Comparative analysis

No predictive modeling was applied, keeping the analysis within the descriptive and exploratory boundaries of the dataset.

---

## 5. Post-Analysis and Insights

The post-analysis brought the different pieces together.

### 1. Housing Decisions Are Connected to Life Stage

Age and employment status emerged as important factors in living arrangements.

Younger respondents and students were more likely to engage with shared housing, while respondents with stable employment showed a stronger preference for independent living.

### 2. Housing Search Stress Is Systemic

One of the more counterintuitive findings was that prior experience with renting did not eliminate housing search stress.

Instead, stress remained widespread across respondent groups.

This points toward broader market problems involving:

- Affordability
- Information quality
- Availability
- Competition
- Trust

### 3. Shared Housing Is an Important Part of the Housing Ecosystem

Shared accommodation is not simply a niche or temporary arrangement.

A substantial portion of respondents had experienced shared housing, making it an important component of the housing ecosystem represented in the dataset.

However, shared housing comes with trade-offs.

**Benefits include:**

- Lower housing costs
- Greater accessibility
- Flexibility
- Shared expenses

**Challenges include:**

- Privacy concerns
- Lifestyle differences
- Safety concerns
- Accountability
- Interpersonal conflict
- Compatibility issues

### 4. Trust Is a Major Housing Decision Factor

Fraud experiences, verification concerns and platform accountability all influenced housing decisions.

Respondents showed a clear preference for mechanisms that could reduce uncertainty, including:

- Verified listings
- Identity verification
- Property verification
- Secure communication
- Transparent profiles
- Dispute-resolution mechanisms

The analysis therefore suggests that a housing platform cannot simply be a digital noticeboard where landlords upload properties.

It needs to become a **trusted intermediary**.

### 5. Qualitative Feedback Reinforced the Quantitative Findings

The open-ended responses strengthened these conclusions.

Recurring themes included:

- Affordability
- Safety
- Trust
- Communication
- Compatibility
- Reliability

These qualitative responses helped explain the "why" behind the quantitative patterns.

### The Most Important Question

There was one particularly interesting finding.

The expectation that inexperienced renters would experience more stress was challenged.

Housing search stress remained significant even among experienced renters.

That finding shifts the conversation away from:

> "Users need to become better at finding houses."

Toward:

> **"How can the housing ecosystem become better at helping people find houses?"**

---

## 6. Data Visualizations & Charts

The analysis was translated into several Excel dashboards designed to make the patterns easier to understand.

Rather than presenting the data as isolated tables, the dashboards created different perspectives on the housing journey.

### Demographics & Current Living Situation

The first dashboard established the foundation.

It examined:

- Age
- Gender
- Employment status
- Student status
- Location
- Current living arrangements
- Length of residence
- Previous rental experience
- Previous shared housing experience

The visualization showed a concentration of working-age respondents and significant representation among students and employed participants.

It also demonstrated that shared housing represents a meaningful component of the respondent population rather than a marginal housing choice.

This dashboard provided the context needed to interpret the rest of the analysis.

### Housing Search Experience

The Housing Search Experience dashboard examined how people actually search for accommodation.

It covered:

- Housing search methods
- Effectiveness of different search channels
- Time taken to secure accommodation
- Housing decision factors
- Common housing challenges
- Fraud experiences
- Housing search stress

The visualizations revealed an important distinction:

> **The channel people use is not necessarily the channel they find most effective.**

Searches can also take longer than expected, increasing fatigue and stress.

Affordability and location emerged as important housing decision factors, while high costs, limited availability, unreliable information and competition contributed to the difficulty of the search.

The dashboard therefore portrays housing acquisition as both a practical and emotional process.

### Fraud, Trust & Security

The Fraud, Trust & Security dashboard focused on one of the most important themes in the analysis: confidence.

The charts examined:

- Fraud experiences
- Importance of verified listings
- Willingness to use platforms with identity verification
- Willingness to use platforms with property verification
- Comfort with online housing transactions
- Reasons for avoiding platforms
- Features that increase trust

Fraud concerns, lack of trust and fear of scams emerged as important barriers to platform usage.

Verification, secure communication and transparent user profiles were identified as strong trust-building mechanisms.

This makes the product implication particularly clear:

> **A platform that solves discovery but fails to solve trust has only solved half the problem.**

### Roommate & Shared Housing

The Roommate & Shared Housing dashboard looked at:

- Previous shared housing experience
- How people find roommates
- Qualities people seek in roommates
- Major roommate concerns
- Compatibility factors
- Safety concerns

One of the most interesting observations was the reliance on personal networks and informal channels for finding roommates.

That points to a potential market gap.

People already have a need to find compatible roommates, but the process remains largely informal.

The qualities people seek also go beyond demographics.

Important considerations include:

- Cleanliness
- Respect
- Responsibility
- Lifestyle compatibility
- Communication
- Reliability

This means that a useful roommate-matching system should not simply match people based on location or price.

It should consider **how people live**.

### Housing Search Behaviour and Trust

The final analytical synthesis showed that digital housing search methods were widely used and perceived as effective.

But digital convenience alone was not enough.

Users associated:

- Verified listings
- Direct communication
- Transparent information
- Identity verification
- Property verification

with greater confidence and safety.

Informal or unverified channels were associated with greater vulnerability to fraud.

The implication is significant for PropTech companies:

> **Technology can make housing search faster, but trust determines whether people are willing to use the technology.**

---

## 7. Recommendations and Observations

The findings suggest that improving housing experiences requires more than adding more property listings.

### Build Trust Into the Core Product

Housing platforms should prioritize:

- Verified property listings
- Authenticated landlord profiles
- Verified roommate profiles
- Transparent reporting mechanisms
- Dispute-resolution processes
- Secure communication

Security should not be buried somewhere in the platform's settings.

It should be visible throughout the user journey.

### Segment Users by Their Real Housing Needs

A student searching for a first apartment has different needs from an employed professional relocating to a new city.

Age, employment status and length of residence can help platforms create more relevant recommendations and experiences.

### Make Listings More Transparent

Housing seekers should be able to understand what they are getting before they commit time or money.

Platforms can reduce uncertainty by standardizing information such as:

- Pricing
- Location
- Amenities
- Property conditions
- Availability
- Shared-house rules
- Landlord information

### Make Roommate Matching More Sophisticated

Roommate matching should go beyond location and affordability.

Compatibility criteria, communication tools and expectations around responsibilities can help users identify potential conflicts before moving in together.

Potential matching criteria could include:

- Lifestyle
- Cleanliness preferences
- Work schedule
- Social habits
- Privacy preferences
- Financial expectations
- Household responsibilities

### Treat Qualitative Feedback as Data

The open-ended survey responses are not just additional comments.

They explain the **"why" behind the numbers**.

Users' own language can reveal concerns that structured survey questions may fail to capture.

This information can be used to improve:

- Product features
- User experience
- Communication
- Customer support
- Trust mechanisms

### Position Platforms as Trust Intermediaries

The strongest strategic opportunity may be to rethink the role of digital housing platforms.

They should not simply connect renters with listings.

They should help users navigate the risks associated with those connections.

That means making **safety, transparency and reliability** central to the value proposition.

---

## 8. Conclusion

The RoomPal analysis reveals a housing ecosystem shaped by four interconnected forces:

- **Demographics**
- **Affordability**
- **Trust**
- **Human relationships**

People's housing choices are influenced by their age, employment status and stage of life.

Shared housing provides an important response to affordability and accessibility challenges, particularly for younger people and students.

But finding housing remains stressful even for people who have done it before.

That is perhaps the most important insight from the analysis.

The problem is not simply that renters lack experience.

The housing search itself contains structural friction.

Information can be unreliable. Costs can be high. Search channels can be inefficient. Fraud creates additional risk. And once people move into shared accommodation, compatibility and trust become important determinants of whether the arrangement works.

Digital platforms have an opportunity to address some of these challenges.

But technology alone is not enough.

The analysis suggests that users want platforms that make housing:

- **Safer**
- **More transparent**
- **More predictable**
- **More trustworthy**

For PropTech companies, this means that verification, communication and user protection should be treated as core product infrastructure.

For housing stakeholders, it means recognizing that accessibility involves more than simply increasing supply.

For researchers, it highlights the importance of combining quantitative survey data with qualitative user experiences.

Ultimately, the lesson from the RoomPal dataset is simple:

> **The future of digital housing will not be determined only by how many properties a platform can list. It will be determined by how much trust it can create around every listing, landlord and roommate.**

---

## 9. References & Appendices

### References

The analysis was based primarily on the **Apartment, House-Sharing & Roommate Experience Survey**, with the cleaned survey dataset serving as the main analytical source.

Microsoft Excel was used throughout the analysis, including:

- Pivot Tables
- Pivot Charts
- Excel Tables
- Conditional Formatting
- `IF`
- `COUNTIFS`
- `AVERAGEIFS`
- Percentage calculations

No external proprietary datasets were introduced.

The findings presented in this project are derived from the project-provided survey data.

### Appendices

The original project included the following supporting analytical materials:

- **Demographics & Living Situation Dashboard**
- **Housing Search Experience Dashboard**
- **Roommate & Shared Housing Dashboard**
- **Fraud, Trust & Security Dashboard**
- **Open-Ended Response Analysis Dashboard**
- **ROOMPAL Interactive Dashboard & Data Flow Insights**
- **Data Dictionary**
- **Data Preparation and Cleaning Documentation**
- **Excel Analysis Techniques and Formula Documentation**

These materials provide additional detail on:

- Variables
- Dashboards
- Preprocessing steps
- Excel techniques
- Analytical formulas
- Data preparation

### A Note on the Analysis

The findings should be interpreted within the limitations of the dataset.

The survey is:

- Self-reported
- Cross-sectional
- Limited to the variables captured by the questionnaire
- Based on survey participants rather than the entire Nigerian population

Future research could strengthen the analysis by incorporating:

- Longitudinal data
- Verified fraud incidents
- Platform usage data
- Larger and more representative samples
- User behaviour data
- Clustering techniques
- Predictive modeling

The broader opportunity is to move from understanding what people **say** about housing to understanding how they **actually behave** throughout the housing journey.

That is where the next generation of housing intelligence can begin.
