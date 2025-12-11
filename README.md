Kaggle Competition：https://www.kaggle.com/competitions/recodai-luc-scientific-image-forgery-detection

本專案以 Recod.ai/LUC 科學圖像資料集為基礎，針對生物醫學圖像中的複製－移動偽造進行像素級分割偵測。我們實作並比較五種模型：ResNet-UNet、Hybrid Transformer-UNet、Swin Transformer + Mask2Former、DINOv2 與 DeepLabV3，探討局部卷積、全域注意力與多尺度特徵在偽造偵測中的作用。
實驗結果顯示，Transformer 架構能顯著提升長距離相似區塊的辨識能力，其中 Swin Transformer + Mask2Former 表現最佳；DeepLabV3 與 U-Net 則分別在多尺度與邊界細節上具備優勢。本研究證實 SOTA Transformer 分割模型能有效提升科學圖像偽造偵測的可靠度。
