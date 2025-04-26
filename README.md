🧠 Brain-Tumor-MRI_upscale 
이미지 업스케일링 모델을 뇌종양 MRI 데이터셋에 적용하여 저해상도 이미지를 고해상도로 복원하여 판별 성능을 높이는 것을 목표로 함   
   
모델 후보   
   
1. ESRGAN ( https://github.com/xinntao/ESRGAN )   
이미지 해상도를 높이는 데 효과적인 GAN 기반 모델로, 매우 자연스러운 세부 사항을 생성하는 것으로 유명   
장점: 고해상도 이미지 복원이 가능하고, 세밀한 구조를 잘 복원합니다.   
   
2.  Deep Image Prior ( https://github.com/DmitryUlyanov/deep-image-prior )   
이미지 복원 및 향상에 매우 유용한 모델로, 이미지 복원에 특화된 네트워크 구조를 사용   
딥러닝 모델이 이미지의 "prior" 정보를 학습하고, 이미지를 향상시키는 방식   
GAN 기반의 복잡한 학습 없이도 뛰어난 성능을 보임   
   
3.  SWINIR ( https://github.com/JingyunLiang/SwinIR )   
최근 Swin Transformer를 기반으로 한 SWINIR 모델은 이미지 향상 및 복원에서 매우 뛰어난 성능 발휘    
특히 Transformer 아키텍처를 활용해 이미지를 복원하는 데 매우 효과적   
SWINIR는 특히 의료 영상에서 뛰어난 성능을 보임   
   
4.  Med-SRNet (Medical Super-Resolution Network)    
(https://pmc.ncbi.nlm.nih.gov/articles/PMC9210125/?utm_source=chatgpt.com)   
   
  GAN 기반의 SR 모델로, 의료 영상의 고해상도 표현 학습에 초점을 맞추어 설계됨     
  MRI와 같은 의료 영상에서의 해상도 향상에 효과적   


5. MRBT-SR-GAN (Magnetic Resonance Brain Tumor Super-Resolution GAN)   
(https://aapm.onlinelibrary.wiley.com/doi/full/10.1002/acm2.13758?utm_source=chatgpt.com)   
   
뇌종양 MRI 영상에 특화된 SR 모델로, 종양의 경계와 구조를 더욱 명확하게 복원함

   
    
   

참고   

데이터셋 : https://huggingface.co/datasets/dwb2023/brain-tumor-image-dataset-semantic-segmentation
