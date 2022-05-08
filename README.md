<h1 align="center">Question Generation</h1>
<p align="center">
</p>


## Theme:
AI/ML

## Introduction:
During the COVID-19 pandemic worldwide, the education sector had taken a toll on both teachers and student life. The students were unsure about the knowledge they are gaining during the online courses due to the lack of physical interactions. We aim to build an application which will be able to facilitate the teachers in generating questions automatically to be given as a short assessment to the teachers. Other than that any individual appearing for online courses will be able to assess themselves by using our application. We plan to implement a end to end solution for assessing students and learners using 4 different kinds of question formats after getting input from various sources like text, audio, pdf and video links.

  
## Demo Video Link:
  <a href="https://drive.google.com/file/d/1noe_IQ-2mBNea8YDuomiMPlbY3PAWnB_/view?usp=sharing">Demo Video Link</a>
  
## Presentation Link:
  <a href="https://www.canva.com/design/DAE5DvSZw28/ifSQPJLvTNLkul9g_Ku8gw/view?utm_content=DAE5DvSZw28&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton"> PPT link here </a>
  
  
## What it does:
It takes in the audio in real time from the online course or a lecture and transcribe it to text. With that text it is processed to generate question of various types like MCQ, FAQ, Paraphrase and Boolean type. We have also implemented a feature to take a pdf file of a teachers materials and generate questions from it. Other than that it can also generate questions from a video link.

## Challenges we Faced:
It took strong teamwork and time management to complete a large-scale project within 30 hours. To learn how to implement the BERT API, we had to learn about natural language processing at a lower level and try to figure out how it can be used to generate distractors for MCQ type of question. We also had to take a subscription of Open AI GPT-2 to build the model.

## API Endpoints:
<b>/                 </b>- Home page for our application <br>
<b>/index            </b>- page to record the audio and converts to text using webspeech API <br>
<b>/questionType     </b> - Select the type of question like MCQ, Paraphrase, FAQ and boolean type

## Screenshots
![1](https://user-images.githubusercontent.com/42286904/162557248-524f4854-c328-417c-9d95-8fa8cf913082.jpg)
![2](https://user-images.githubusercontent.com/42286904/162557250-81e7a34a-99ab-4a91-a28f-8d8c80b182bd.jpg)
![3](https://user-images.githubusercontent.com/42286904/162557251-153a163b-c4bb-41b0-a275-191e72a82803.jpg)
![4](https://user-images.githubusercontent.com/42286904/162557252-9f3c89b8-acfc-456c-9f00-c8ed38a87116.jpg)
![5](https://user-images.githubusercontent.com/42286904/162557235-ab6d881e-9670-495a-8810-58bcf558c520.jpg)
![6](https://user-images.githubusercontent.com/42286904/162557236-b93f1039-03ad-4f7c-9eb3-2a1dc040b68a.jpg)
![7](https://user-images.githubusercontent.com/42286904/162557238-c7c532bd-e12e-47ac-a227-8ff62209a4ad.jpg)
![8](https://user-images.githubusercontent.com/42286904/167292818-55f1a866-9f93-4444-a201-7a16d0f5c405.png)
![9](https://user-images.githubusercontent.com/42286904/167292863-f304e253-ada1-476a-a5ba-9209ba4bb9a2.png)
![10](https://user-images.githubusercontent.com/42286904/167292896-dc190bef-375a-4754-ba65-ac5e53d34654.png)
![12](https://user-images.githubusercontent.com/42286904/162557243-b095fd6b-9f28-4693-b33f-aff5f06588ed.jpg)
![13](https://user-images.githubusercontent.com/42286904/162557245-19355824-e301-4d9b-a385-03026ef252b7.jpg)
![14](https://user-images.githubusercontent.com/42286904/162557247-07368db7-f695-437c-a420-2e5f5ddf1241.jpg)
![15](https://user-images.githubusercontent.com/42286904/162557326-23f1c481-9cb2-4ac3-a3a2-bba30181967e.jpg)
![16](https://user-images.githubusercontent.com/42286904/162557328-5a93668a-4332-4517-b5a2-68d1bc8c44e0.jpg)




## Overall Architecture
![1](https://user-images.githubusercontent.com/42286904/159449919-3ba28167-7490-47b5-b426-4b8969f4b866.jpeg)
## Generating Wrong Choices for the MCQ Questions
![2](https://user-images.githubusercontent.com/42286904/159449943-b7d03b47-c8fd-49df-9cb4-ccbafc4e73e2.jpeg)
## Generating False Sentences for the Boolean Questions Architecture
![3](https://user-images.githubusercontent.com/42286904/159449950-0c1e6267-d97f-408a-9c52-1c6377ac3725.jpeg)



## Future Scope
- Better Speech Recognition with CNN Model
- Integrate with various meeting sites like teams, gmeet, zoom, etc.
- Make a robust chatbot to handle more complex enquiry or product detail enquiry
- Improve the accuracy of the Questions


## Technology Stack:
 - Flask
 - HTML, CSS, JS
 - Bootstrap4
 - Jquery
 - Python NLTK
 - Spacy
 - Wordnet
 - ConceptNet
 - BERT
 - Sense2vec
 - PyTorch
  

## Contributors:

Team Name: Odd Bit Squad

* [Ayan Sadhukhan](https://github.com/ayan2809)
* [Ronit Sarkar](https://github.com/Codee0101)
* [Aniket Bansal](https://github.com/nicolausmaximus)
* [Chandru S](https://github.com/CRag-01)


### Made at: HackDefine 2022