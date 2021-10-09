# Project-Seminar - Infectious Disease Modeling - SEIR-Model
Short Case Study - Differential Equation Modeling in Infectious Disease Forecasting in the context of a project seminar

The case study consists of a basic part and one extension. A SEIR differential equation model is developed to fit the described cases. Differential equation models divide the individuals of a population into different compartments and describe the transitions into and out of these using differential equations. The SEIR model consists of four compartments:
<ol>
  <li><strong>S</strong>usceptibles (Healthy but susceptible to getting infected)</li>
<li><strong>E</strong>xposed (Infected but not yet contagious)</li>
<li><strong>I</strong>nfectious</li>
<li><strong>R</strong>ecovered</li>
</ol> 

Flowchart of the model for the basic part:

<img src="https://raw.githubusercontent.com/lukasheide/Project-Seminar---Seminar-Thesis---SIR-Model/main/Assets/Images/SEIR%20Model%20Flowchart.PNG?raw=true" width="700" height="150" />

The description of both parts of the case study is as follows:

**Basic part:**
In a medium-sized city, there is an outbreak of a new type of respiratory disease that, according to initial findings, affects almost exclusively children between the ages of three and six. None of the 10,000 children of the affected age group appear to be immune to the rapidly spreading disease. The disease is transmitted by aerosols and respiratory droplets. Investigations have indicated that children who become ill are contagious for an average of 10 days. The approximated latency period after infection is 4 days in which most children show no symptoms. With an estimated reproductive value of 10, the novel disease is extremely contagious. The modeling objective is to obtain precise forecasts for the development of the next 100 days. 

**Extension:**
After two weeks the sharp increase in the number of infections leads to increased social awareness. In combination with quarantine measures for infected children and increased hygiene measures in kindergartens, the reproductive value of the disease drops to 6.
One week later further measures such as separate kindergarten groups and stricter quarantine measures are introduced, leading to a further drop in the R value to 3. After 28 days, the kindergartens are closed completely which pushes the R-value to 1.5. In addition, another week later a vaccine is available to vaccinate 50 children per day. 80% of parents indicate willingness to have their children inoculated with this vaccine. 


Modeling results of the basic approach:

<img src="https://raw.githubusercontent.com/lukasheide/Project-Seminar---Seminar-Thesis---SIR-Model/main/Assets/Images/SEIR%20Model%201%20-%20Results.PNG?raw=true" width="750" height="400" />
