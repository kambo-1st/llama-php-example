# example for LLama C++ library php bindings

Simple example for LLama C++ library PHP bindings.

**This is highly experimental and not suitable for production use!**

**Use at your own risk!**

**Only Linux is supported!**

![asciicast](llama-php.gif)

## How to run this

How to run this demo (ggjt model from huggingface is used):
```bash
composer install
cd models
wget https://huggingface.co/LLukas22/gpt4all-lora-quantized-ggjt/resolve/main/ggjt-model.bin
cd ..
php example.php
```
