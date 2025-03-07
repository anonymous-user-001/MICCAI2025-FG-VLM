# MICCAI2025-FG-VLM (submission #4469)

FG-VLM: A Fact-Guided Vision-Language Model
for Visual Grounding and Binary Factual
Question Answering in Chest X-ray Analysis

# Model
![miccai_2025_model](https://github.com/user-attachments/assets/05e087c7-2aee-4720-a1bb-72305a4a281c)

# Results on VinDr-CXR (original  labels)

### Classification
![auprc_macro_per_image_encoder_and_architecture_vindrcxr_test_set__random_removed](https://github.com/user-attachments/assets/e30c9d04-bbfb-40bb-b415-ca4713f97af9)

### Detection
![detection_metrics_vindrcxr_test_set__random_and_iou_removed](https://github.com/user-attachments/assets/5ee9287b-0750-439e-bb8c-b9a9812918dc)

### Classification (breakdown per class)
![auprc_per_class_vindrcxr(original)_test_set](https://github.com/user-attachments/assets/23d512a6-8df7-4647-852d-a6b42407b2a6)

# Results on VinDr-CXR (modified  labels) + MIMIC-CXR (positive & negative facts + GPT-4 labels)

### Overview results
<img width="1175" alt="mimiccxr+vindrcxr(modified)_metrics" src="https://github.com/user-attachments/assets/a822fa28-c8b6-4a48-9698-9655ef9133da" />

### Lung Opacity recall improvement after modification

<img width="400" alt="lung_opacity_recall_before_after" src="https://github.com/user-attachments/assets/2c7617da-d8c2-4c71-902b-961410f6823f" />

### Classification on VinDr-CXR modified (breakdown per class)
![auprc_per_class_vindrcxr(modified)_test_set](https://github.com/user-attachments/assets/80d08e0f-3f1e-4d5f-b8a5-f159071524ae)

### Classification on MIMIC-CXR GPT-4 labels (breakdown per class)
![auprc_per_class_mimiccxr_test_set_gpt4_labels](https://github.com/user-attachments/assets/f51cfe2f-b205-41b5-aeb5-11375e2f1ef0)

# Comparison with the state of the art

### Classification on VinDr-CXR
<img width="677" alt="miccai_2025_classification_table" src="https://github.com/user-attachments/assets/07b74935-7efe-473e-9d42-d70a3fc507b6" />

### Detection on VinDr-CXR
<img width="677" alt="miccai_2025_detection_table+example" src="https://github.com/user-attachments/assets/0ca05698-b87e-4361-9b0c-1c45da8c17ca" />

# MIMIC-CXR report annotation example

### Report with strong positive facts, strong negative facts, weak negative facts, GPT-4 labels (positve and negative)
<img width="1025" alt="miccai_2025_report_example" src="https://github.com/user-attachments/assets/e1d703e4-7c38-43c1-8191-cce50d7af42c" />

### Screenshot of OpenAI's playground with GPT-4's prediction for the class "Nodule/Mass"
<img width="719" alt="miccai_2025_GPT-4_example" src="https://github.com/user-attachments/assets/2f6934c2-f1cd-412e-af6e-53c4555c0df3" />

