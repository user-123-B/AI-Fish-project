# 組別:B05
# 專題題目: AI Fish:3D視覺化魚群模擬與觀測健康系統
# 指導教授: 楊泰寧
# 組員: 資工3B張育嘉、 資工3B猶韋森
# 研究背景:
魚類養殖每年都有因密度過高、水質突變及投餵不精準所造成的死亡。傳統2D監控無法捕捉3D魚群行為，決策延遲達數小時。
系統透過AI深度學習融合。                                                         
# 動機:
傳統養殖面臨勞力短缺、環境變異及決策延遲等挑戰，AI深度學習結合3D模擬
 可實現即時監測與優化決策，提升產量。
# 工具軟體:
Visual studio code
*深度學習框架：PyTorch 2.1
理由：靈活性強、ONNX匯出、社群大

*3D平台：
最終方案：Unity（上手快，但效能較低）Visual studio 2022
適合初學者

*AI模型：
roboflow 呈現
YOLOv8 Nano：魚類偵測（15ms/frame）
CNN-BiLSTM：健康特徵分析（5ms/frame）
簡單MLP：快速異常二分類

# 系統架構圖:
<img width="1135" height="643" alt="image" src="https://github.com/user-attachments/assets/ac91ff77-5ad7-4ef1-9b2e-8d290d834ef3" />

#模擬層:
<img width="800" height="900" alt="架構-第 1 页 drawio" src="https://github.com/user-attachments/assets/2442e992-5e3e-49a9-a141-1a73ab3de4d9" />

#AI分析層:
<img width="800" height="700" alt="image" src="https://github.com/user-attachments/assets/ab3dd525-1cfb-4344-b4c5-1a9b4a9e08cb" />

#視覺化層:
<img width="800" height="700" alt="image" src="https://github.com/user-attachments/assets/9e8cfa1d-cd32-42c1-8eac-c523b159e488" />
