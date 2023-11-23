# ChattoBotto
This is my first chatbot. I've used meta's LLaMa 7B parameter version and fine tuned it using SFT on WhatsApp chats and a medical assistant dataset. As of now it doesn't have contextual memory but in the future I plan on making the changes. 
It can understand Hinglish prompts from the user with good accuracy and also repond quite well to ambiguous questions when asked.

I am hereby providing the link to model's location - https://huggingface.co/unmolb/ChattoBotto_v2

STEPS TO USE THE MODEL FOR INFERENCE - 

1. Generate an access token (READ) from your hugging face profile settings.
2. Login to the huggingface hub from kaggle nb or colab nb.
3. Load the model using AutoModelForCausalLM and its tokenizer from AutoTokenizer.
4. Make use of the pipeline modulde of the transformers library.

# Inferences - 
![Inference 1](/Chattobotto%20inference/inference_1.jpg)

![Inference 2](/Chattobotto%20inference/inference_2.jpg)

![Inference 3](/Chattobotto%20inference/inference_3.jpg)

![Inference 4](/Chattobotto%20inference/inference_4.jpg)



