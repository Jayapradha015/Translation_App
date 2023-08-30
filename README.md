# Project Title
## **Automated Document Translation using OpenAI Language Model**
# Project Description
This project is based on the concept of **Large Language Model** . It uses the unlashing potential of **LLM** to localize the text from one language to the other as specified by the user. 
Additionally, it changes the name of the person in the document as specified by the user.
# Screenshot of This Application
![Screenshot_Translation](https://github.com/Jayapradha015/Translation_App/assets/119176840/104fb87e-6e2c-483b-9018-1e14ee32b690)
# Dependencies
Libraries and Packages needs to be installed
```
pip install openai
pip install docx2txt
pip install spacy
pip install streamlit
```
# Details
Read the docx file using the docxtxt python library. Then I split the document into many paragraphs. Then these paragraphs are sent to the **OPENAI API** model which translates the text into the language specified by the user. For finding the name of the person to get change as specified by the user, I have used the spacy library. This library finds the person's name using Named Entity Recognition. The overall view of the app is given using the Streamlit library.
