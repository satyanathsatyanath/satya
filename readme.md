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


| S.No | Project / PocName | Deployed On | FrontEnd URL | Description | BackEnd URL | MLFLOW URL | Status | OpenSource/ 3rd Party API | Remarks |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1.0 | Swift Insights ChatBot | AWS Lambda | nan | nan | https://st2rqlvrnub57t52ahnze5sn3y0mqnlh.lambda-url.ap-south-1.on.aws/ | nan | Active | OPENAI - GPT 3.5 Turbo | nan |
| 2.0 | SI Q&A - Demo | AWS Lambda | nan | nan | https://btsxutmstdmwbmgf5acb3iuzsu0hfxci.lambda-url.ap-south-1.on.aws/ | http://43.204.54.237:8081/ | Active | OPENAI - GPT 3.5 Turbo | used in newdevapp.swiftinsights.ai |
| 3.0 | SI Q&A - Playground | AWS Lambda | nan | nan | https://iejf46tynfiuydxbhw5iifvs340jnwbm.lambda-url.ap-south-1.on.aws/ | http://43.204.54.237:8081/ | Active | OPENAI - GPT 3.5 Turbo | used in dsapp.swiftinsights.ai |
| 4.0 | SI Baijnath Jewellers | AWS Lambda | nan | nan | nan | nan | nan | nan | nan |
| 5.0 | St Marks Living chatbot | AWS EC2 | http://13.126.165.42:5884/stmarkvillageQA | nan | http://13.126.165.42:7199/website_chat | http://13.126.165.42:5000/ | Not Active | nan | on demand |
| 6.0 | Amnet Digital website chatbot(Swift Insights) | AWS Lambda | nan | nan | https://4vo6otqcd6qgqrpkl6pig6rmxe0vnxik.lambda-url.ap-south-1.on.aws/ | nan | Active | Runpod | used in www.swiftinsights.ai/ |
| 7.0 | Swift Extract Demo | AWS EC2 | nan | nan | nan | nan | nan | nan | nan |
| 8.0 | Image tampering Detection | nan | nan | nan | nan | nan | nan | nan | nan |
| 9.0 | MAM | DGX | http://10.10.0.212:4888/dashboard | Downscale input video resolution to 416*416 | http://10.10.0.212:6996/get_video/
 | nan | Not Active | nan | nan |
| nan | nan | nan | nan | Product and background detection | http://10.10.0.212:8006/infer | nan | Not Active | nan | nan |
| nan | nan | nan | nan | Athlete detection  | http://10.10.0.212:8099/get_faces/ | nan | Not Active | nan | nan |
| nan | nan | nan | nan | Display People present in Image DB | http://10.10.0.212:8222/get_img_db/ | nan | Not Active | nan | nan |
| nan | nan | nan | nan | Add person image to screen  and verify input images | http://10.10.0.212:8199/get_face_bbox/ | nan | Not Active | nan | nan |
| nan | nan | nan | nan | Match the input images with existing image db and store to db | http://10.10.0.212:8024/verify_store/ | nan | Not Active | nan | nan |
| nan | nan | nan | nan | Delete face in db | http://10.10.0.212:8979/del_face/ | nan | Not Active | nan | nan |
| nan | nan | nan | nan | Video Summarization | http://10.10.0.212:8005/process_video/ | nan | Not Active | nan | nan |
| nan | nan | nan | nan | Club responses from all apis | http://10.10.0.212:9022/club_responses/ | nan | Not Active | nan | nan |
| nan | nan | nan | nan | Update new videos meta data | http://10.10.0.212:8520/update_db/ | nan | Not Active | nan | nan |
| nan | nan | nan | nan | View videos meta info | http://10.10.0.212:8963/get_view_details/ | nan | Not Active | nan | nan |
| nan | nan | nan | nan | Remove cache | http://10.10.0.212:9696/remove_cache/ | nan | Not Active | nan | nan |
| 10.0 | LDS | DGX | http://10.10.0.212:4888/dashboard | Downscale input video resolution to 416*416 | http://10.10.0.212:6996/get_video/
 | nan | Active | nan | nan |
| nan | nan | nan | nan | Product and background detection | http://10.10.0.212:8006/infer | nan | Active | nan | nan |
| nan | nan | nan | nan | Athlete detection  | http://10.10.0.212:8099/get_faces/ | nan | Active | nan | nan |
| nan | nan | nan | nan | Display People present in Image DB | http://10.10.0.212:8222/get_img_db/ | nan | Active | nan | nan |
| nan | nan | nan | nan | Add person image to screen  and verify input images | http://10.10.0.212:8199/get_face_bbox/ | nan | Active | nan | nan |
| nan | nan | nan | nan | Match the input images with existing image db and store to db | http://10.10.0.212:8024/verify_store/ | nan | Active | nan | nan |
| nan | nan | nan | nan | Delete face in db | http://10.10.0.212:8979/del_face/ | nan | Active | nan | nan |
| nan | nan | nan | nan | Video Summarization | http://10.10.0.212:8005/process_video/ | nan | Active | nan | nan |
| nan | nan | nan | nan | Club responses from all apis | http://10.10.0.212:9022/club_responses/ | nan | Active | nan | nan |
| nan | nan | nan | nan | Update new videos meta data | http://10.10.0.212:8520/update_db/ | nan | Active | nan | nan |
| nan | nan | nan | nan | View videos meta info | http://10.10.0.212:8963/get_view_details/ | nan | Active | nan | nan |
| nan | nan | nan | nan | Remove cache | http://10.10.0.212:9696/remove_cache/ | nan | Active | nan | nan |

    

