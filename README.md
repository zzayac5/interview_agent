# interview_agent
Repository for a project building an interviewing AI agent.

<p> I want to build an ai agent that will be able to ingest content, develop interview questions, and then create content from the interview. I want to start first on the agent building long and short form text content from the interview. That means it should create tweets, linkedin posts, and blogs based on the interview. This could then spin into long and short form video content because you could include an virtual representation of the "interviewer" and create mass on demand short form video content from these interviews.</p>

### Initial Requirements List.

**Requirement 1:** Accepts URLs of content into the system </li>
* User will submit a URL of content that they either agree with, disagree with, hate, or love and this will be the basis of the interview questions developed. The User will need a place to input a URL and an interface where they can select Agree or Disagree and a 1-10 scale to determine how the content should be read and how the questions should be developed. 

<br/>

**Requirement 2:** Content that is submitted is scraped for its context </li>
* The text based article or post submitted through the URL is ingested and then from this ingestion an LLM will parse the content and develop questions for the interview based on the agree/disagree selection.

<br/>

**Requirement 3:** Client is called via a voice enabled LLM to have the interview </li>
* Clients are called by the LLM interviewer to have a discussion about the content they submitted. The LLM asks the client the key questions and any follow up questions it determines will be important for making content. 

<br/>

**Requirement 4:** The original article and the interview are used to make long and short form content </li>
* Based on the interview the LLM creates various short form and long form content with a similar tone and contextual thought process as the client it interviewed. 
<br/>

# DAY 1 : 6 AUG 2025

Today I am focused on getting this repository and VS code set up to work within. 
This sounds super simple to most but I am using VS code for this build because I will also be using it as a chance to learn JS and it was suggested to use VS code for that and not Pycharm. 
Also I want to get an initial build of the requirements and a design for the architecture for the use case. 


