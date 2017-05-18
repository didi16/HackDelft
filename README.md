Hack Delft

The code here presented was developed during TU DELFT's hackathon. 
Our case was sponsored by KPMG and in its essence consists of a news classifier that can be improved with the user's input. With our machine learning approach the end goal was to remove the need of using hand-crafted filters that group the news by content. Also, our grouping method can be used to allow a more user friendly experience while browsing through KPMG's cyber security trends index.

The process starts with the extraction of the news from the web using a provided API. Then,  two approaches are available: (i)  an unsupervised approach, which will cluster the incoming news based on their similarity and generate classes and (ii) a  supervised approach, where a Random Forrest Classifier trained on 3204 news will attribute one of the six existing classes to the news. The user is allowed to confirm whether the prediction is right or wrong. In case that it is wrong he has the opportunity of correctly label the data and improve the model!

-> https://www.hackdelft.com/ -> https://cyber.kpmg.com/#trends/day/group:tczfu0uduaxdswlovcmb0intjkfxamnc
