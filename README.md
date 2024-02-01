# Document-Layout-Analysis
It's a project on how to fine-tune LiLt for document-understand using Hugging Face Transformers. 
In fact, we present an intriguing document layout analysis model  called Language-independent Layout Transformer (LiLT)(3) combined with XLM RoBERTa(5), a multilingual RoBERTa(6) model (trained on 100 languages),both based on the revolutionary Transformers library and finetuned on the famous Doclaynet dataset that contains more than 80000 human-annotated documents from various sources and was conceived for document layout segmentation.
This is the model is question called LiLT (Language-Independent Layout Transformer)which is a Document Understanding model that uses both layout and text in order to detect labels of bounding boxes: https://huggingface.co/docs/transformers/model_doc/lilt
It relies on an external OCR engine to get words and bboxes from the document image. Thus, let's run an OCR engine ourselves (PyTesseract) as we'll need to do it in real life.
The following link leads to the space of the developed app: https://huggingface.co/spaces/NiamaLynn/lilt-roberta-DocLayNet-256
The following link leads to the processed data used: https://huggingface.co/datasets/pierreguillou/DocLayNet-base
