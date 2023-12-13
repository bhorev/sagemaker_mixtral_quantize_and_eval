# sagemaker_mixtral_quantize_and_eval
Quantize and host a Mixtral with SageMaker LMI and evaluate it with SageMaker Clarify

**mixtral_LMI-8bit.ipynb** - deploy an 8bit quantized Mixtral model on a SageMaker Endpoint

**mixtral_LMI-bf16.ipynb** - deploy an 16bit (bf16) Mixtral model on a SageMaker Endpoint

**eval_mixtral.ipynb** - Use SageMaker Clarify with fmeval to evaluate the 8bit model

Refereneces
- https://mistral.ai/news/mixtral-of-experts/
- https://docs.aws.amazon.com/sagemaker/latest/dg/clarify-foundation-model-evaluate.html

### ml.g5.12xlarge
4x NVIDIA A10G

![image](https://github.com/bhorev/sagemaker_mixtral_quantize_and_eval/assets/65091963/e29e449b-94d8-4e62-a45b-e793902315ce)
