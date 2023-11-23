# Nonstop_Web_Scrapping
Web Scrapping of "The New York Times" News Website is done

I conducted web scraping on The New York Times to gather article titles and their respective sections, including categories such as "US," "World," and "Sport". The obtained data was systematically organized into a CSV file with dedicated columns for both the article section and title.

Subsequently, I developed a machine learning model employing a text classification approach. This model was trained on the collected article titles to predict the section to which a news article might belong. Components crucial to this process, such as a TF-IDF vectorizer, were utilized and the entire model, along with these components, was saved using the pickle library.

Utilizing PyCharm, I designed a Streamlit web application. This application allows users to input a news article title, and subsequently, the app leverages the pre-trained model to predict the appropriate section for the given news article.

This streamlined provided a seamless user experience for predicting news article sections based on their titles.

![Output_Screenshot](https://github.com/KalpakKondekar/Nonstop_Web_Scrapping/blob/main/Output_Screenshot.jpg)
