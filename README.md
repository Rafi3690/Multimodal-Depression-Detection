# Multimodal-Depression-Detection







## Abstract
>  The source code is accessible at https://github.com/Rafi3690/Multimodal-Depression-Detection.

----

**python implementation**

<!-- ```python
Version :   0.0.1  
Author  :   M.A.Rafi
Email   :   190125.cse@student.just.edu.bd
``` -->
---
### **Related resources**:

**LOCAL ENVIRONMENT**  
```python
OS          :   Windows 11
Memory      :   64.0 GiB
Processor   :   AMD Ryzen 9 3900X
Graphics    :   GeForce RTX 3090
CPU(s)      :   24 (AMD Ryzen 9 3900X
```
---

### Prepare Datasets

We use the [D-Vlog](https://doi.org/10.1609/aaai.v36i11.21483) dataset, proposed in this paper. For the D-Vlog dataset, please fill in the form at the bottom of the [dataset website](https://sites.google.com/view/jeewoo-yoon/dataset), and send a request email to the [author](mailto:yoonjeewoo@gmail.com). Following D-Vlog's setup, the dataset is split into train, validation and test sets with a 7:1:2 ratio. 

---

**python requirements**
* **pip requirements**: ```pip install -r requirements.txt``` 

### Execution (Depression Detection)
- ```$ conda activate your_env```

- To train and validate:

    ```$ python mainkfold.py```

- To inference:
    ```$ python infer_mainkfold.py```


This project is licensed under the [MIT License](LICENSE).

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
