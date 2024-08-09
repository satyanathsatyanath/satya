---
# AWS Projects README

## Projects

### Project 1: [SE_Website_QA (stmarkvillageQA)]
- **Description**: [All the UI,mlflow,backend URL's related to SwiftExtract]
- **AWS Services Used**: [EC2, Lambda]
- **EC2 URL(BACKEND)**: [http://13.126.165.42:7199/website_chat]
- **EC2 URL(UI)**: [http://13.126.165.42:5884/stmarkvillageQA]
- **EC2 URL(MLFLOW)**: [http://13.126.165.42:5000/]
- **LAMBDA FUNCTION NAME(BACKEND)**:[Website_QA]
  - **LAMBDA URL(BACKEND)**: [https://gqbwty27frkykn3vxj7hnlbppi0unkyq.lambda-url.ap-south-1.on.aws/]
- **Structure**: The input should be in JSON format with the following structure:
  - **Example**:
    ```json
    {
      "Question":""
    }
    ```

### Project 2: [Visualization_Chatbot] 
- **AWS Services Used**: [Lambda]
- **LAMBDA FUNCTION NAME(BACKEND)**:[visualization_chatbot_test]
  - **LAMBDA URL**: [https://btsxutmstdmwbmgf5acb3iuzsu0hfxci.lambda-url.ap-south-1.on.aws/]
- **Structure**: The input should be in JSON format with the following structure:
  - **Example**:
    ```json
    {
      "Question":""
    }
    ```

    

|   S.No | Project / PocName                             | Deployed On   | FrontEnd URL                              | BackEnd URL                                                            | MLFLOW URL                 | Status     | OpenSource/ 3rd Party API   | Remarks                            |\n|-------:|:----------------------------------------------|:--------------|:------------------------------------------|:-----------------------------------------------------------------------|:---------------------------|:-----------|:----------------------------|:-----------------------------------|\n|      1 | Swift Insights ChatBot                        | AWS Lambda    | nan                                       | https://st2rqlvrnub57t52ahnze5sn3y0mqnlh.lambda-url.ap-south-1.on.aws/ | nan                        | Active     | OPENAI - GPT 3.5 Turbo      | nan                                |\n|      2 | SI Q&A - Demo                                 | AWS Lambda    | nan                                       | https://btsxutmstdmwbmgf5acb3iuzsu0hfxci.lambda-url.ap-south-1.on.aws/ | http://43.204.54.237:8081/ | Active     | nan                         | used in newdevapp.swiftinsights.ai |\n|      3 | SI Q&A - Playground                           | AWS Lambda    | nan                                       | https://iejf46tynfiuydxbhw5iifvs340jnwbm.lambda-url.ap-south-1.on.aws/ | http://43.204.54.237:8081/ | Active     | nan                         | used in dsapp.swiftinsights.ai     |\n|      4 | St Marks Living chatbot                       | AWS EC2       | http://13.126.165.42:5884/stmarkvillageQA | http://13.126.165.42:7199/website_chat                                 | http://13.126.165.42:5000/ | Not Active | nan                         | on demand                          |\n|      5 | Amnet Digital website chatbot(Swift Insights) | AWS Lambda    | nan                                       | https://4vo6otqcd6qgqrpkl6pig6rmxe0vnxik.lambda-url.ap-south-1.on.aws/ | nan                        | nan        | Runpod                      | nan                                |\n|      6 | Swift Extract Demo                            | nan           | nan                                       | nan                                                                    | nan                        | nan        | nan                         | nan                                |\n|      7 | Image tampering Detection                     | nan           | nan                                       | nan                                                                    | nan                        | nan        | nan                         | nan                                |\n|      8 | MAM                                           | DGX           | nan                                       | nan                                                                    | nan                        | nan        | nan                         | nan                                |\n|      9 | LDS                                           | DGX           | nan                                       | nan                                                                    | nan                        | nan        | nan                         | nan                                |
