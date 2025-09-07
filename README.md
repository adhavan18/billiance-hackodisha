📌 overview

billiance is an ai-powered shoplifting detection system that leverages computer vision and machine learning to enhance retail security. by monitoring cctv footage in real-time, the system assigns confidence scores to customer-product interactions and detects suspicious activities, such as product concealment or unauthorized removal. when potential shoplifting is identified, an email alert with video evidence is immediately sent to the shopkeeper.

🚀 features

- real-time cctv monitoring – detects customers and their interactions with products
  
- confidence scoring system – flags unusual product movements or concealment behavior
  
- shoplifting detection – identifies attempts to hide or steal products
  
- email notifications – sends instant alerts with video snapshots to store owners
  
- scalable security solution – can be deployed in supermarkets, retail outlets, or malls
  
- tech stack

programming language: python

deep learning frameworks: tensorflow / pytorch

computer vision: opencv, yolo / faster r-cnn (for object detection)

database: sql (for storing alerts & logs)

backend: flask / django (api integration)

notification system: smtp for email alerts

📂 project structure
billiance-shoplifting/
│── data/                # training datasets & video samples
│── models/              # pre-trained & custom ml models
│── src/                 # core detection and tracking code
│   ├── detection.py     # shoplifting detection logic
│   ├── tracking.py      # person & object tracking
│   ├── notify.py        # email alert system
│── requirements.txt     # dependencies
│── app.py               # main application
│── README.md            # project documentation
