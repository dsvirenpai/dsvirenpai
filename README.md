<h2><center>KNN in Forensic Science: Classifying Glass Evidence for Criminal Investigations</center></h2>

<h3>Problem Description </h3>
The study of the classification of glass type is motivated by criminological investigations. At a scene of crime, shattered pieces of glass are used as evidence if it's correctly classified. 

<h4>Types of Investigations:</h4>
<ul>
<li>Hit and Run: Glass fragments from broken headlights are used to identify the make and model of the vehicle involved.</li>
<li>Burglary: Glass fragments from a smashed window can be connected to a suspect if fragments match glass found on their person or belongings.</li>
<li>Vandalism/Assault: Glass from broken bottles or other objects can link a suspect to a crime scene or indicate the type of weapon used</li>
</ul>

![Crime_Scene](https://github.com/dsvirenpai/KNN_Forensic_Science_Classifying_GlassType/assets/118036431/507929a6-62d3-4092-86af-767a7d46985f)

Forensic labs maintain databases of known glass samples (from car manufacturers, major glass suppliers, etc.).The data set consists of 214 unique glass samples labeled as one of six class categories.
Once the composition of an unknown glass sample is known, the glass type needs to be correctly matched with the ones in the database to narrow down the scope of the investigation.
Once the composition of an unknown glass sample is known, the glass type needs to be correctly matched with the ones in the database to narrow down the scope of the investigation.

As an analytics firm, the objective is to resolve the problem of classifying glass fragments in a criminal investigation.

<h3>Success Criteria:</h3>

<ul>
<li>Business Success - Decrease investigation time by 50hrs/week</li>
<li>ML Success Criteria - Obtain classification model accuracy of 90%</li>
<li>Economic Success Criteria - Increase in the firm's revenue by 10%
</li>
</ul>

<h3>Data Description:</h3>
<ul>
<li>Total Observations: 214</li>
<li>Total Features: 10</li>
<li>Dependent Feature: Type</li>
</ul>

<h4>Features:</h4>

<ul>
<li>RI(float64) - Refractive Index</li>
<li>Na(float64) - Percentage Composition of Sodium</li>
<li>Mg(float64) - Percentage Composition of Magnesium</li>
<li>Al(float64) - Percentage Composition of Aluminium</li>
<li>Si(float64) - Percentage Composition of Silicon</li>
<li>K(float64) - Percentage Composition of Potassium</li>
<li>Ba(float64) - Percentage Composition of Barium</li>
<li>Fe(float64) - Percentage Composition of Iron</li>
<li>Type(int64) - Glass Type (1-7)</li>
</ul>

         
<h3>Conclusion:</h3>
<ul>
<li>KNN Model Accuracy: 0.69</li>
<li>Performance of the model precision, recall, and F1-score vary for each class. The model performs well in classifying classes 1, 2, 7, and 5, with an F1-score of 0.67, 0.70, 0.94, and 0.75 respectively.</li> 
<li>However, the model performs poorly in classifying class 3, with an F1-score of only 0.40. It suggests the model may have difficulty distinguishing between class 3 and other classes.</li>
</ul>

<h3>Future Scope:</h3>
<ul>
<li>Assess the cost of misclassification: Real-world impact: What are the real-world consequences of incorrectly classifying or missing instances of class 3? It could involve reputational damage, or other negative outcomes.</li>
<li>Improving model accuracy by experimentation with other classification algorithms.</li>
</ul>





"# dsvirenpai" 
