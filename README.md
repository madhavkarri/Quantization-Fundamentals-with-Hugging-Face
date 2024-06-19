# Quantization Fundamentals with Hugging Face

- Generative AI models, like large language models, often exceed the capabilities of consumer-grade hardware and are expensive to run.
- Compressing models through methods such as quantization makes them more efficient, faster, and accessible. 
- This allows them to run on a wide variety of devices, including smartphones, personal computers, and edge devices, and minimizes performance degradation.
- Quantize any open source model with linear quantization using the Quanto library.
- Get an overview of how linear quantization is implemented. This form of quantization can be applied to compress any model, including LLMs, vision models, etc.
- Apply “downcasting,” another form of quantization, with the Transformers library, which enables to load models in about half their normal size in the BFloat16 data type.
