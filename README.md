# HEADS
Hybrid Extractive Abstractive Document Summarization

This project presents a hybrid document summarization system that integrates extractive and abstractive techniques to produce factually accurate and linguistically coherent summaries of long documents. By leveraging the Longformer model’s ability to process extended sequences and combining it with the fluent text generation capabilities of a modified BART model, our approach addresses key challenges in summarization: extractive methods often produce disjointed outputs, while abstractive methods risk factual inaccuracies and struggle with lengthy inputs. Utilizing the GovReport dataset, we demonstrate significant improvements in summary quality, achieving higher ROUGE scores, better factual consistency, and enhanced semantic alignment compared to baseline models. Our system introduces a novel pipeline that extracts key sentences, transforms them into structured factual constraints, and guides abstractive generation, offering a scalable solution for summarizing complex, long-form documents such as government reports.

We used GovReport dataset for training HEADS. [Click](https://drive.google.com/drive/folders/1dJ-f1vgMDG3R-XWCyWdYF68xXjseEOyS?usp=sharing) here to access the raw dataset. We have generated intermediate dataset to train both Longformer and BART, [click](https://drive.google.com/drive/folders/1pwtrx7N_66hJAMwOgub6IrlembLI0-Uy?usp=drive_link) here to access it.


.
Here is the comparision among HEADS and other state of the models

![Picsart_25-09-06_09-53-46-468](https://github.com/user-attachments/assets/6e50879d-671a-42a3-b077-f970b9fce907)
![Picsart_25-09-06_09-56-23-310](https://github.com/user-attachments/assets/ede34de2-05ce-41da-8670-48949d26a68f)
![Picsart_25-09-06_09-57-46-929](https://github.com/user-attachments/assets/90715457-c1da-4b90-8e52-436ca72cc054)
![Picsart_25-09-06_10-00-11-456](https://github.com/user-attachments/assets/7d89d87b-6188-4992-82a7-d7533c7e32eb)
