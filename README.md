# Gradio_GenAI_Deployment
We can deploy any ML model or DL model including chatbots, LLMs, Computer vision models using Gradle UI with simple steps. This can help reduce development time of building UI for your application and concentrate on Experimenting Networks and Data processing steps which are crucial.

Gradio offers intuitive UI to deploy any AI application with fewer lines of code and you can also share it with anyone with a link that expires in 72 hours.

This repo shows how you can deploy 5 different AI applications using Gradio.

I have used Huggingface inference API for different models to focus on Gradio deployment than AI model development. You can run these code samples and experiment it on colab as well. You need to set up few things before
* Create a .env file and have the contents as below
  * Development settings
  * HF_API_KEY=
  * HF_API_SUMMARY_BASE=https://api-inference.huggingface.co/models/sshleifer/distilbart-cnn-12-6
  * HF_API_NER_BASE=https://api-inference.huggingface.co/models/dslim/bert-base-NER
  * HF_API_ITT_BASE=https://api-inference.huggingface.co/models/Salesforce/blip-image-captioning-large
  * HF_API_TTI_BASE=https://api-inference.huggingface.co/models/runwayml/stable-diffusion-v1-5
  * HF_API_FALCOM_BASE=https://api-inference.huggingface.co/models/tiiuae/falcon-7b-instruct
  * PORT1=7901
  * PORT2=7902
  * PORT3=7903
  * PORT4=7904

You can obtain HF_API_KEY by creating an account in Huggingface, you can try out different models from HuggingFace by changing Inference URLs or deploy your own model.

You can learn more about Gradio from https://www.deeplearning.ai/short-courses/building-generative-ai-applications-with-gradio/
