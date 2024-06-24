# SLInterpreter-Demo

### This is a Demo for SLInterpreter.

Due to the large size of the model prediction result files from **KR4SL**, and the double-blind platform's limitation of a maximum single file upload size of **8MB**, the prediction results in this demo only include the cases mentioned in the paper. Other data such as the Knowledge Graph, which are relatively smaller in size, are provided in full. After the double-blind period, we will release all source code and datasets through other platforms.

### Please note:

Data files exceeding 8MB have been uploaded in compressed form. Therefore, before using this demo, **ensure that all files listed in the unzipped list are correctly extracted to their respective locations**, otherwise the functionality will not work properly.

#### Files to be unzipped:

- `static/KG/facts_full_type.zip`
- `static/KG/facts_full_type_index.zip`
- `static/knownSL/facts.zip`
- `static/knownSL/predicted_gene_all`

### User Notice:

1. Since this demo is a build version, we recommend using the **Go Live** plugin of **VScode** for running it. Directly opening the `.html` file may not work correctly.
2. This demo only includes the prediction result data from the cases mentioned. Therefore, clicking on other genes **will not display the explanation path views correctly**. Please enter `CDK1` in the Primary Gene search box and select `CDK1` to reproduce the case in the article or explore freely.
3. **As this demo is a trial version**, the system does not have access to the full data from our test runs. Therefore, bugs may occur during operation. This is normal, and you can raise issues on our subsequent open-source homepage. We greatly appreciate your understanding!
