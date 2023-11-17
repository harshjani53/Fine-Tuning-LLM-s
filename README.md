# Fine-Tuning-LLM-s

###### In this project I have worked on Google's FLAN-T5 model and Conversation Dataset on AWS Sagemaker.
###### First of all converted data into tokens so that we can use it in model.
###### Then, ran original model to check output.
###### Then fully fine tuned the model on conversation data.
###### Now it takes a lot of computing power to fully fine tune a LLM, so did PEFT(Parameter Efficient Fine Tuning) to retrain just some part of weights of LLM rather than all the weights.
###### Finally compared Rouge-1 scores of all 3, 1) Original Model 2) Fully Fine Tuned Model 3) PEFT Model.
###### Fully fine tuned model has the highest rouge-1 score followed by PEFT and Original model.
###### But the difference between Fully fine tune and PEFT models are significantly less, this indicates that PEFT is giving similar results to fully fine tuned model.

