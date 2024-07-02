| 模型名字      | 模型ID | 调用接口     |
| :--:        |    :----:   |          :--: |
| c10_lightv2_mse40_mix.cvimodel      |   CVI_TDL_SUPPORTED_MODEL_SOUNDCLASSIFICATION_V2|   CVI_TDL_SoundClassification_V2|
| cviface-v6-s.cvimodel   | CVI_TDL_SUPPORTED_MODEL_FACERECOGNITION | CVI_TDL_FaceRecognition |
| hand_det_qat_640x384.cvimodel     | CVI_TDL_SUPPORTED_MODEL_HAND_DETECTION | CVI_TDL_Hand_Detection |
| hand_kpt_128x128.cvimodel  | CVI_TDL_SUPPORTED_MODEL_HAND_KEYPOINT | CVI_TDL_HandKeypoint |
| hand_kpt_cls9.cvimodel     | CVI_TDL_SUPPORTED_MODEL_HAND_KEYPOINT_CLASSIFICATION | CVI_TDL_HandKeypointClassification |
| hardhat_detection_v2.cvimodel   | CVI_TDL_SUPPORTED_MODEL_YOLOV8_HARDHAT | CVI_TDL_YOLOV8_Hardhat |
| mask_classifier.cvimodel     | CVI_TDL_SUPPORTED_MODEL_MASKCLASSIFICATION | CVI_TDL_MaskClassification |
| mobiledetv2-pedestrian-d0-ls-448.cvimodel   | CVI_TDL_SUPPORTED_MODEL_MOBILEDETV2_PEDESTRIAN | CVI_TDL_MobileDetV2_Pedestrian |
| pet_det_640x384.cvimodel      | CVI_TDL_SUPPORTED_MODEL_PERSON_PETS_DETECTION | CVI_TDL_PersonPet_Detection |
| pipnet_mbv1_v8.cvimodel  | CVI_TDL_SUPPORTED_MODEL_FACELANDMARKERDET2 | CVI_TDL_FaceLandmarkerDet2 |
| ppyoloe_coco80_cv181x.cvimodel      | CVI_TDL_SUPPORTED_MODEL_PPYOLOE | CVI_TDL_PPYoloE |
| scrfd_768_432_int8_1x.cvimodel   | CVI_TDL_SUPPORTED_MODEL _SCRFDFACE | CVI_TDL_ScrFDFace |
| topformer_tiny.cvimodel      | CVI_TDL_SUPPORTED_MODEL _TOPFORMER | CVI_TDL_Topformer |
| yolov5m_coco80_cv181x.cvimodel  | CVI_TDL_SUPPORTED_MODEL_YOLOV5 | CVI_TDL_Yolov5 |
| yolov6n_coco80_cv181x.cvimodel    | CVI_TDL_SUPPORTED_MODEL_YOLOV6 | CVI_TDL_Yolov6 |
| yolov7_tiny_coco80_cv181x.cvimodel | CVI_TDL_SUPPORTED_MODEL_YOLOV7 | CVI_TDL_Yolov7 |
| yolov8n_384_640_person_vehicle.cvimodel    | CVI_TDL_SUPPORTED_MODEL_PERSON_VEHICLE_DETECTION | CVI_TDL_PersonVehicle_Detection |
| yolov8n_coco80_cv181x.cvimodel   | CVI_TDL_SUPPORTED_MODEL_YOLOV8_DETECTION | CVI_TDL_YOLOV8_Detection |
| yolov8n_headperson.cvimodel     | CVI_TDL_SUPPORTED_MODEL_HEAD_PERSON_DETECTION | CVI_TDL_HeadPerson_Detection |
| yolox_m_coco80_cv181x.cvimodel  | CVI_TDL_SUPPORTED_MODEL_YOLOX | CVI_TDL_YoloX |
| yolox_s_coco80_cv181x.cvimodel     | CVI_TDL_SUPPORTED_MODEL_YOLOX | CVI_TDL_YoloX |


| 模型名字      | ION/FlASH | 推理耗时（ms） |     模型性能   |
| :--:        |    :----:   |          :--: |          :--: |
| c10_lightv2_mse40_mix.cvimodel      | 0.62 MB/587KB | 3.12 | 3.12 |
| cviface-v6-s.cvimodel   | 2.97 MB/2.36MB | 7.96 | FMR:0.1 FNMR:0.0141 |
| hand_det_qat_640x384.cvimodel     | 2.82MB/913KB |      16.6      | mAP(0.5): 82.1% |
| hand_kpt_128x128.cvimodel  | 0.84MB/809KB | 0.829 | pck@0.05:0.886 |
| hand_kpt_cls9.cvimodel     | 0.05MB/54KB | 0.255 | Acc: 91.0% |
| hardhat_detection_v2.cvimodel   | 7.48MB/1.05MB | 38.4 | mAP(0.5)=92.42% |
| mask_classifier.cvimodel     | 3.11MB/2. 30MB | 4.88 | Acc: 97.2% |
| mobiledetv2-pedestrian-d0-ls-448.cvimodel   | 2.12MB/441KB | 10.3 | mAP(0.5): 66.4% |
| pet_det_640x384.cvimodel      | 6.5MB/2.99MB | 32.8 | mAP(0.5):87.0% |
| pipnet_mbv1_v8.cvimodel  | 0.58 MB/512KB | 0.449 | x_loss: 0.029 y_loss: 0.015 |
| ppyoloe_coco80_cv181x.cvimodel      | 14.55MB/8.9MB | 101.15 | mAP(0.5): 55.4% |
| scrfd_768_432_int8_1x.cvimodel   | 4.50 MB/742KB | 10.9 | mAP(0.5)：easy: 89.4% medium: 86.5% hard:65.9% |
| topformer_tiny.cvimodel      | 5.2 MB/1.66MB | 27.6 | mean IoU:0.754(12类) |
| yolov6n_coco80_cv181x.cvimodel    | 31.35MB/4.9MB | 49.11 | mAP(0.5): 49.8% |
| yolov7_tiny_coco80_cv181x.cvimodel | 70.66MB/7.7MB | 70.41 | mAP(0.5): 53.4% |
| yolov8n_384_640_person_vehicle.cvimodel    | 5.58 MB/3.13M | 28.5 | mAP(0.5)：72.0% |
| yolov8n_coco80_cv181x.cvimodel   | 31.56MB/3.5MB | 45.62 | mAP(0.5): 51.2% |
| yolov8n_headperson.cvimodel     | 5.29M/3.13M | 26.5 | mAP(0.5): 78.5% |
| yolox_s_coco80_cv181x.cvimodel     | 95.44MB/10.0MB | 127.91 | mAP(0.5): 52.4% |