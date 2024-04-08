<table>
  <tr>
    <td>
      <img src="logo.jpg" alt="Alternative text for the image" title="Optional title attribute" width="350"/>
    </td>
  </tr>
</table> 
בפרויקט זה נרצה לתת מענה לבעיה אקטואלית במיוחד בימינו - הסברה ישראלית ותגובה לביטויי אנטישמיות ברשתות החברתיות.
המערכת שלנו תאפשר למשתמשים שונים , ללא תלות ברמת ההתנסחות, בפערי השפה וברמת הניסיון, ליצור טקסטים איכותיים ורלוונטיים אשר מגבירים חשיפה בעניין הסברה ישראלית. הפתרון שאנו מציעות הוא מערכת חכמה שתומכת בשלל פונקציות, ביניהן: 

(1) בהינתן טקסט אנטי-ישראלי , תדע לייצר טקסט תגובה אליו, 

(2) בהינתן פוסט עבר שלך - תדע לייצר טקסט חדש בהשראת הטקסט שלך, תוך כדי שמירת אלמנטים ייחודיים לך,  

(3) בהינתן וורסיה ראשונית שלך, תדע לשכתב ולייצר פוסט איכותי ותקין ו-

(4) תייצר טקסט חדש לגמרי.

המערכת מבוססת על  LLM אשר יש ביכולו ליצור טקסט מעניין ובהיר ועל דאטהסט שייצרנו ע"י סריקה מ - Reddit. האלמנט הייחודי של המערכת הוא המיקוד בנושא ספציפי - פוסטים פרו ישראליים ברשתות חברתיות . אומנם קיימים פתרונות דומים בסקטורים אחרים, אך הם מכוונים למגזר העסקי , לא מאפשרים להביא לידי ביטוי את הסגנון האישי של המשתמש ונמנעים משיח בנושאים רגישים כמו זה.

# Project Title: Nevonot Enhanced Text Generator

## Description

The Nevonot Enhanced Text Generator is an innovative project that leverages advanced natural language processing (NLP) techniques and the GPT-4 model to interact with and generate textual content. It offers users the ability to generate new posts, rewrite existing text, reply to text, and create content in a specific style directly within a Jupyter Notebook environment.

## Features

- **Reply to Text**: Generate a contextually relevant reply to the given text input.
- **My Style**: Create new content that matches the style of the input text.
- **Rewrite**: Offer a rewritten version of the provided text.
- **Generate New Post**: Produce completely new content based on a set of predefined criteria.

## Installation

To run this project, you'll need to have Jupyter Notebook or JupyterLab installed. If you haven't already, you can install Jupyter via Anaconda or pip. Additionally, this project requires Python 3.6 or later.

### Dependencies

Before running the project, install the required Python packages:

```bash
pip install praw nltk openai ipywidgets pandas


To run the project, open the file via jupyter notebook. 
to insert API key edit the following code line in the 9th cell:
os.environ["OPENAI_API_KEY"] = "YourKeyHere"
run all cells except the last one. 
once you are finished generating several inputs, run the last cell to view history. 
