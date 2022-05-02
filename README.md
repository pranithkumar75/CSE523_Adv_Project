# Handwriting recognition using AWS Textract API

# Prerequisites to run the application

1. Please ensure below files are available in the same directory where `extract_handwritten_text.py` before running the application,
    1. CCW9_blank.jpg
    2. CCAD_blank.jpg
    3. CCDD_blank.jpg
    4. PUVC_blank.jpg
    5. CCW9_config.json
    6. CCAD_config.json
    7. CCDD_config.json
    8. PUVC_config.json
2. Update AWS credentials `aws_access_key_id` and `aws_secret_access_key` in `extract_handwritten_text.py`
3. Run `extract_handwritten_text.py` which produces an excel sheet of extracted key value pairs in the same location of given input file
4. Command to run the application (See sample command below):
```
python extract_handwritten_text.py --document_type PUVC --file_name ".\PUVC\PUVC_1.
pdf"
```
Workflow:

	![](https://github.com/pranithkumar75/CSE523_Adv_Project/blob/main/workflow.png)
