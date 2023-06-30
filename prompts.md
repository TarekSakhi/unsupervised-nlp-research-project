## Knowledge-based prompt for keywords

Given the following description of [Lbl2vec](https://github.com/sebischair/Lbl2Vec) algorithm:
The key idea of the algorithm is that many semantically similar keywords can represent a topic. In the first step, the algorithm creates a joint embedding of document and word vectors. Once documents and words are embedded in a vector space, the goal of the algorithm is to learn label vectors from previously manually defined keywords representing a topic. Finally, the algorithm can predict the affiliation of documents to topics from document vector <-> label vector similarities.

And given the [following](https://www.simplypsychology.org/qualitative-quantitative.html) comparison between the qualitative and quantitative study methods:
A research study includes the collection and analysis of data. In quantitative research, the data are analyzed with numbers and statistics, and in qualitative research, the data analyzed are non-numerical and perceive the meaning of social reality.

What Is Qualitative Research?
Qualitative research observes and describes a phenomenon to gain a deeper understanding of a subject. It is also used to generate hypotheses for further studies. In general, qualitative research is explanatory and helps understands how an individual perceives non-numerical data, like video, photographs, or audio recordings. The qualitative data is collected from diary accounts or interviews and analyzed by grounded theory or thematic analysis.

When to Use Qualitative Research?
Qualitative research is used when the outcome of the research study is to disseminate knowledge and understand concepts, thoughts, and experiences. This type of research focuses on creating ideas and formulating theories or hypotheses.

Benefits of Qualitative Research
Unlike quantitative research, which relies on numerical data, qualitative research relies on data collected from interviews, observations, and written texts.
It is often used in fields such as sociology and anthropology, where the goal is to understand complex social phenomena.
Qualitative research is considered to be more flexible and adaptive, as it is used to study a wide range of social aspects.
Additionally, qualitative research often leads to deeper insights into the research study. This helps researchers and scholars in designing their research methods.
Qualitative Research Example
In research, to understand the culture of a pharma company, one could take an ethnographic approach. With an experience in the company, one could gather data based on the —

Field notes with observations, and reflections on one’s experiences of the company’s culture
Open-ended surveys for employees across all the company’s departments via email to find out variations in culture across teams and departments
Interview sessions with employees and gather information about their experiences and perspectives.
What Is Quantitative Research?
Quantitative research is for testing hypotheses and measuring relationships between variables. It follows the process of objectively collecting data and analyzing it numerically, to determine and control variables of interest. This type of research aims to test causal relationships between variables and provide generalized results. These results determine if the theory proposed for the research study could be accepted or rejected.

When to Use Quantitative Research?
Quantitative research is used when a research study needs to confirm or test a theory or a hypothesis. When a research study is focused on measuring and quantifying data, using a quantitative approach is appropriate. It is often used in fields such as economics, marketing, or biology, where researchers are interested in studying trends and relationships between variables.

Benefits of Quantitative Research
Quantitative data is interpreted with statistical analysis. The type of statistical study is based on the principles of mathematics and it provides a fast, focused, scientific and relatable approach.
Quantitative research creates an ability to replicate the test and results of research. This approach makes the data more reliable and less open to argument.
After collecting the quantitative data, expected results define which statistical tests are applicable and results provide a quantifiable conclusion for the research hypothesis
Research with complex statistical analysis is considered valuable and impressive. Quantitative research is associated with technical advancements like computer modelling and data-based decisions.
Quantitative Research Example
An organization wishes to conduct a customer satisfaction (CSAT) survey by using a survey template. From the survey, the organization can acquire quantitative data and metrics on the brand or the organization based on the customer’s experience. Various parameters such as product quality, pricing, customer experience, etc. could be used to generate data in the form of numbers that is statistically analyzed.

qualitative vs. quantitative research 

Data Collection Methods
1. Qualitative Data Collection Methods
Qualitative data is collected from interview sessions, discussions with focus groups, case studies, and ethnography (scientific description of people and cultures with their customs and habits). The collection methods involve understanding and interpreting social interactions.

Qualitative research data also includes respondents’ opinions and feelings, which is conducted face-to-face mostly in focus groups. Respondents are asked open-ended questions either verbally or through discussion among a group of people, related to the research topic implemented to collect opinions for further research.

2. Quantitative Data Collection Methods
Quantitative research data is acquired from surveys, experiments, observations, probability sampling, questionnaire observation, and content review. Surveys usually contain a list of questions with multiple-choice responses relevant to the research topic under study. With the availability of online survey tools, researchers can conduct a web-based survey for quantitative research.

Quantitative data is also assimilated from research experiments. While conducting experiments, researchers focus on exploring one or more independent variables and studying their effect on one or more dependent variables.

A Step-wise Guide to Conduct Qualitative and Quantitative Research
Understand the difference between types of research — qualitative, quantitative, or mixed-methods-based research.
Develop a research question or hypothesis. This research approach will define which type of research one could choose.
Choose a method for data collection. Depending on the process of data collection, the type of research could be determined.
Analyze and interpret the collected data. Based on the analyzed data, results are reported.
If observed results are not equivalent to expected results, consider using an unbiased research approach or choose both qualitative and quantitative research methods for preferred results.
Qualitative Vs. Quantitative Research – A Comparison
Qualitative Research	Quantitative Research
It helps understand human behaviour to find the way people think and analyze their experiences.	It aims to compute numbers and perform statistical analysis.
These research methods are ideal when there is no fixed set of questions, and the discussion is useful to explore issues.	It helps generate numerical data and hard facts using statistical, logical, and mathematical techniques.
The time consumed for planning is less as compared to the analysis phase.	The time consumed for planning is more as compared to the analysis phase.
 

With an awareness of qualitative vs. quantitative research and the different data collection methods, researchers could use one or both types of research approaches depending on their preferred results. Moreover, to implement unbiased research and acquire meaningful insights from the research study, it is advisable to consider both qualitative and quantitative research methods.

Your task is to generate keywords for the lbl2vec algorithm in order to classify whether a study uses a quantitative research design or a qualitative research design. Use the knowledge provided and your own knowledge. It should be a comprehensive list of keywords that can identify each class. The output should be python lists.

Given the following description of Lbl2vec algorithm:
The key idea of the algorithm is that many semantically similar keywords can represent a topic. In the first step, the algorithm creates a joint embedding of document and word vectors. Once documents and words are embedded in a vector space, the goal of the algorithm is to learn label vectors from previously manually defined keywords representing a topic. Finally, the algorithm can predict the affiliation of documents to topics from document vector <-> label vector similarities.

## Criteria-based prompt for keywords

### First prompt
I am using lbl2vec for the classifications of scientific studies. They can have quantitative or qualitative study design. In order to give a comprehensive definition to both classes, I have made the following criteria:

Quantitative Research Approach:

- The research question of the study is designed to quantify and statistically measure outcomes, correlations or differences between variables.
- The data collected in the study is numerical and quantifiable.
- The study applies statistical methods to analyze the data collected.
- The data collection process uses (semi-)structured methods, for instance, surveys or questionnaires.
- The findings are mainly presented in a numerical form, such as tables, graphs or measurements. 


Qualitative Research Approach:

- The research question of the study is designed to explore, interpret or generate understanding about a phenomenon.
- The data collected is non-numerical, for instance, text video or audio.
- The study applies interpretive or subjective methodologies for data analyses.
- The data collection process uses unstructured or semi-structured methods, for example, interviews, observations or analysis of documents.
- The findings are presented in a narrative or descriptive form, providing detailed insights.



Can you create keywords to identify each class, use the criteria provided and your knowledge about quantitative and qualitative study designs. Ensure that there are enough keywords per criterion. 
It is important that the keywords are semantically different, in order to better differentiate both classes. Output in python lists.

### Second prompt
Add more keywords that focus on the different meanings of a quantitative and qualitative study design. Avoid using lists of a list
