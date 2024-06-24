# SLInterpreter-Demo

### VIS 2024 submission: 1368

### This is a Demo for SLInterpreter.

Due to the large size (above 3GB) of the model prediction result files from **KR4SL**, and the double-blind platform's limitation of a maximum single file upload size of **8MB**, the prediction results in this demo only include the cases mentioned in the paper. Other data such as the Knowledge Graph, which are relatively smaller in size, are provided in full. After the double-blind period, we will release all source code and datasets through other platforms.

### Important:

Data files exceeding 8MB have been uploaded in compressed form. Therefore, before using this demo, **ensure that all files listed in the unzipped list are correctly extracted to their respective locations**, otherwise the functionality will not work properly.

#### Files to be unzipped:

- `static/KG/facts_full_type.zip`
- `static/KG/facts_full_type_index.zip`
- `static/knownSL/facts.zip`
- `static/knownSL/predicted_gene_all.zip`

### User Notice:

1. Since this demo is a build version, we recommend using the **Go Live** plugin of **VScode** for running it. Directly opening the `.html` file may not work correctly.
2. This demo only includes the prediction result data from the Cases mentioned in the paper. Therefore, selecting other genes **will not display the Interpretative Path View correctly**. Please first enter `CDK1` in the Primary Gene search box and select `CDK1` to reproduce the Case in the paper or explore freely.
3. **As this demo is a trial version**, the system does not have access to the full data from our test runs. Therefore, unexpectable bugs may occur during operation. You can raise issues on our subsequent open-source homepage. We greatly appreciate your understanding!


### Dataset Links:
1. [SynLethDB](https://synlethdb.sist.shanghaitech.edu.cn/v2/#/) is a comprehensive synthetic lethality knowledge base towards discovery of selective and sensitive anticancer drug targets.

2. [ProteinKG25](https://www.zjukg.org/project/ProteinKG25/) is a large-scale KG dataset with aligned descriptions and protein sequences respectively to GO term and proteins entities. It contains about 612,483 entities, 4,990,097 triples (including 4,879,951 protein-go triplets and 110,146 Go-Go triplets). 