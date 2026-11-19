# ID-Extraction-Model
this model can be used to extract text based information when provided with an ID card (e.g aadhar/ PAN)
id-card-extraction/
│
├── app/
│   ├── main.py
│   │
│   ├── routes/
│   │   └── extraction.py
│   │
│   ├── preprocessing/
│   │   ├── file_handler.py
│   │   └── image_preprocessor.py
│   │
│   ├── ocr/
│   │   └── paddle_ocr.py
│   │
│   ├── extraction/
│   │   ├── aadhaar_front.py
│   │   ├── aadhaar_back.py
│   │   └── pan_card.py
│   │
│   ├── models/
│   │   └── layoutlmv3/
│   │
│   └── schemas/
│       └── response.py
│
├── dataset/
│   ├── aadhaar_front/
│   ├── aadhaar_back/
│   └── pan_card/
│
├── training/
│   ├── annotations/
│   └── train_extraction.py
│
├── requirements.txt
└── README.md
