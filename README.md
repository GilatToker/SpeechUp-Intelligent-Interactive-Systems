## 12.2023

<table>
  <tr>
    <td>
      <img src="logo.jpg" alt="Alternative text for the image" title="Optional title attribute" width="150"/>
    </td>
  </tr>
</table> 

# Intelligent Interactive System - Final Project : SpeechUp

## Description

in this project, we aim to address a particularly timely issue - Israeli advocacy and responding to expressions of antisemitism on social media. Our system will enable various users, regardless of their level of articulation, language barriers, and experience, to create high-quality and relevant texts that increase exposure to Israeli advocacy. The solution we propose is an intelligent system that supports a variety of functions, including:

## Features
- **Reply to Text**: Given anti-Israeli text, it can generate a responsive text.
- **My Style**: Given a user's previous post, it can generate new text inspired by your content while maintaining elements unique to you.
- **Rewrite**: Given your initial version, it can rewrite and create a quality, correct post.
- **Generate New Post**: It can create entirely new text.
The system is based on an LLM capable of generating interesting and clear text, and on a dataset we created by scanning Reddit. The unique element of the system is its focus on a specific issue - pro-Israeli posts on social media. While similar solutions exist in other sectors, they are aimed at the business sector, do not allow expressing the user's personal style, and avoid discussion on sensitive topics like this one.

<table>
  <tr>
    <td>
      <img src="system_UI.jpg" alt="Alternative text for the image" title="Optional title attribute" width="1000"/>
    </td>
  </tr>
</table> 

This project utilizes a key data source, reddit_data_IsraelPalestine.csv, which consists of data we have meticulously web-scraped from Reddit. This dataset plays a crucial role in enhancing the quality and relevance of the generated text by our system. It is designed to make the output more vivid and closely aligned with the current discourse on social media regarding Israeli advocacy and responses to antisemitism.

## Installation

```bash
pip install praw nltk openai ipywidgets pandas

To run the project, open the file via jupyter notebook for optimal performance. using other programs to open the notebook (such as google collab) might cause the interactions of the program to run suboptimally due to different system components.
upload the files Nevonot_project.ipynb and logo.jpg in the same folder.
to insert API key edit the following code line in the 10th cell:
os.environ["OPENAI_API_KEY"] = "YourKeyHere"
run all cells.
once you are finished generating several inputs, run the last cell to view history. 
