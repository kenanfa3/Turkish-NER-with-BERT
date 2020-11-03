# Turkish-NER-with-BERT
A repositery that includes the code to run NER for Turkish utilizing BERT as described in my Medium blog https://medium.com/analytics-vidhya/named-entity-recognition-for-turkish-with-bert-f8ec04a31b0 <br/>
This work was focused on fine-tuning BERT model for NER task on a turkish dataset. Another goal was to handle the limitation of BERT with sequences longer than maxiumum length of 512 tokens. This problem was solved by building shorter overlapping sequences performing the token classification and then reconstructing them again. <br/>
Unfortunately, this code needs to be updated as HuggingFace updated their Trainer API.
