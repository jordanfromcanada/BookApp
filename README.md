# Book Spine Reader

https://user-images.githubusercontent.com/65370643/154761427-1719807e-7049-4c16-8767-2ecde6d1c982.mp4

- Tool for scanning a library shelf with an iPhone to infer the order of books based on the call number printed on the book spine, enabling rapid sorting by librarians
- Book spine labels are detected with a MobileNetSSD model trained on dataset generated from over 1,000 annotations of book spine labels (320x320)
- Text is inferred from spine labels with an end-to-end trained Keras OCR model

<img width="500" alt="Screen Shot 2022-02-18 at 12 53 52 PM" src="https://user-images.githubusercontent.com/65370643/154761170-9e5f14d4-e4d1-4cab-a980-359979b0e26a.png">
<img width="500" alt="Screen Shot 2022-02-18 at 12 54 49 PM" src="https://user-images.githubusercontent.com/65370643/154761145-a68386a3-dbaa-4a4e-9d9c-5eda0c5e789d.png">
<img width="500" alt="Screen Shot 2022-02-18 at 12 54 14 PM" src="https://user-images.githubusercontent.com/65370643/154761154-57bad5b4-d5a7-48c0-9b37-fb73dc924e96.png">
