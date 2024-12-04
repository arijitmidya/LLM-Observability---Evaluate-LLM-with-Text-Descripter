# LLM-Observability---Evaluate-LLM-with-Text-Descripter

# Steps of Implementation 

## Step 1 : Import necessary libraries , dataset and perform baseline EDA

![image](https://github.com/user-attachments/assets/f4b7fcd2-dc7a-45f2-b421-f3433092fba9)

## Step 2 : Generate one-off reports 

### a. Simple descripters : Create baseline report on the "question" and "response column"on the following 
          Sentiment
          Text Length
          OOV
          Non letter character percentage
          SentenceCount
          WordCount

  Please find below some example visuallization from the report , the complete report is attached as simple_descriptors.html ( download and open in browser of your choice )

  ![image](https://github.com/user-attachments/assets/ecaa4bb1-4710-4e98-b706-a48269c85a6f)

  ![image](https://github.com/user-attachments/assets/7861213c-fd3f-4200-ae5e-4a7237184ba6)

  ![image](https://github.com/user-attachments/assets/252258e0-3369-4b0b-a241-7cc909a66d49)

  ![image](https://github.com/user-attachments/assets/4a784f6d-b051-415f-a1b7-741210082615)

 
### b. Complex descripter : Generate reports using complex descripters "question" and "response column"on the following 
           BeginsWith
           RegExp
           IncludesWords
           EndsWith
           ExcludesWords
           Contains
           DoesNotContain

  Please find below some example visuallization from the report , the complete report is attached as complex_descriptors.html ( download and open in browser of your choice )

  ![image](https://github.com/user-attachments/assets/a0821f45-9aea-4088-b5c8-b5d1f20030df)

  ![image](https://github.com/user-attachments/assets/caf3b0e5-771c-4b27-a056-b42a276d148c)

  ![image](https://github.com/user-attachments/assets/3e2f0055-61e1-4b92-800f-46f1a031469b)

  ![image](https://github.com/user-attachments/assets/ec5877ce-1b4b-4ac3-8b3c-7d6bc159216f)

### c. Model based descripters : Here we will leverage huggingface models for binary classification on the "response" column on following 
           Toxicity classification
           emotions classification ( dissapointment )
           emotions classification (optimism)
           Topic modelling ( HR , Finance )
           PII classification 

![image](https://github.com/user-attachments/assets/6653bed5-e829-4d83-82be-3b4c1feb3162)

![image](https://github.com/user-attachments/assets/6a251310-2a55-4989-ac39-2524546c5fad)

![image](https://github.com/user-attachments/assets/09471ecf-abcd-45e3-b6c6-662c9f244179)

![image](https://github.com/user-attachments/assets/36686e2c-6da5-4ac0-9130-9dfbb5911a8f)

![image](https://github.com/user-attachments/assets/ec8550cb-82d8-4c2a-81d5-34e5ff95bc5f)

the complete report is attached as model_based_descriptors.html ( download and open in browser of your choice )

### d. LLM based descripters : Here we will leverage LLM ( Open AI model "gpt-4o-mini") , define PII and negativity prompt to evaluate the "response" column

![image](https://github.com/user-attachments/assets/2a74ff0b-cae0-4d11-a9c2-453a763476a2)

![image](https://github.com/user-attachments/assets/a67fbdee-e17c-4a50-b152-d816d700d50b)

![image](https://github.com/user-attachments/assets/4da8f7d7-a83b-4f67-891a-306a213fece9)

the complete report is attached as llm_descriptors.html ( download and open in browser of your choice )

N.B : To execute the LLM descripter based report , you would need to use your personal Open AI Key

Happy Coding :)






           






