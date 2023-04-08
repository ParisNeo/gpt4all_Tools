# gpt4all_Tools

This is a small repo for people who wants to convert their gpt4all models to work with the new python bindings.
- First download the model here:
https://the-eye.eu/public/AI/models/nomic-ai/gpt4all/gpt4all-lora-quantized.bin
- put it to your models folder
- download the tokenizer here:
https://github.com/ParisNeo/gpt4all_Tools/raw/main/tokenizer.model
- put it to your models folder
- after installing the pyllamacpp execute this code:
pyllamacpp-convert-gpt4all models/gpt4all-lora-quantized.bin models/llama_tokenizer models/gpt4all-lora-quantized.bin
Now you can use the ui
