---
title: "Deep learning-based medical image segmentation methods"
FirstAuthor:
- Jun Shi
OtherAuthors:
- Tiantong Wang
- Ziqi Zhu
- Minfan Zhao
- Bingxun Wang
- Junshi Chen
- Hong An

ConfJournal: "中国图象图形学报" # 投稿出版社/会议
ConfJournalAbbr: "JIG"
IsAConference: "no" # 会议填yes，期刊写 no
IsOutofCS: yes # 其他领域会议，填yes (比如医疗影响领域会议)
OutofCSLabel: "中文期刊B" # 不在CCF分类，但在其他领域分类的排名，如 CAAI B
CCFLevel: "B" # 必填,用于排序。 期刊1234区，对应A B C D
JournalLabel: "CCF 中文期刊B" # SCI Q1, IF=5.7 
Year: 2025
Award: ""
Abstract: ""

KeyWords:
- deep learning
- medical image segmentation
- convolutional neural network 
- vision transformer 
- vision mamba
Link: https://www.cjig.cn/thesisDetails#10.11834/jig.240467&lang=zh # 官网链接 
PDF: # pdf文件位置
SLIDE:  # PPT文件位置
video: # 会议视频
---

Medical image segmentation is a crucial component of clinical medical image analysis, aiming to accurately identify and delineate anatomical structures or regions of interest, such as lesions, within medical images. This process provides objective and quantitative support for decision-making in disease diagnosis, treatment planning, and postoperative evaluation. In recent years, the rapid expansion of available annotated datasets has driven the swift development of deep learning-based medical image segmentation methods. These methods have demonstrated superior accuracy and robustness compared to traditional segmentation techniques, establishing themselves as the mainstream technology in the field. Extensive research has been dedicated to improving the structural designs of segmentation models and further enhancing segmentation accuracy, leading to the development of various segmentation approaches. Current deep learning-based medical image segmentation methods can be classified into three main structural categories: convolutional neural networks (CNNs), Vision Transformers, and Vision Mamba. As a representative neural network architecture, CNNs effectively capture spatial features in images due to their unique local receptive fields and weight-sharing mechanisms. These characteristics make CNNs particularly suitable for image analysis and processing tasks. Since 2015, CNN-based methods, such as U-Net, have dominated the field of medical image segmentation, consistently achieving state-of-the-art performance across various downstream segmentation tasks. Many studies have focused on modifying and innovating the U-Net structure to further improve segmentation accuracy, resulting in several derived segmentation methods. Despite these advancements, CNN-based methods are still limited by the inherent constraints of convolutional operators, particularly the local nature of their receptive fields. These limitations restrict the capability of the model to capture global contextual dependencies, which are crucial for handling complex medical images and performing fine-grained segmentation. While techniques such as attention mechanisms and specialized convolutions have been introduced to address these challenges and help the model focus on global information, their effectiveness remains limited. Since 2020, researchers have begun introducing Transformer architectures, originally developed for natural language processing (NLP), into computer vision tasks, including medical image segmentation. Vision Transformers use self-attention mechanisms to effectively model global dependencies, drastically improving the quality of semantic feature extraction and facilitating the segmentation of complex medical images. Transformer-based methods for medical image segmentation mainly include hybrid approaches that combine Transformers with CNNs, as well as pure Transformer methods, each displaying unique advantages and disadvantages. Hybrid approaches capitalize on the strengths of CNNs in local feature extraction while leveraging the capabilities of Transformers in modeling global context. This combination enhances segmentation accuracy while maintaining computational efficiency. However, these hybrid methods remain dependent on CNN structures, which may limit their performance in complex scenarios. In contrast, pure Transformer methods excel at capturing long-range dependencies and multiscale features, leading to remarkable improvements in segmentation accuracy and generalization. However, pure Transformer architectures typically require substantial computational resources and high-quality training data, posing challenges, especially in the medical field, where large-scale annotated datasets are often difficult to obtain. Despite the notable advantages of Transformer architectures in capturing long-range dependencies and global contextual information, their computational complexity grows quadratically with the length of the input sequence, which limits their applicability in resource-constrained environments. Researchers are developing new methods that can model global dependencies with linear time complexity to overcome this challenge. For instance, Mamba introduces a novel selective state-space model that uses a selection mechanism, hardware-aware algorithms, and a streamlined architecture to reduce computational complexity while maintaining efficient performance in long-sequence modeling. Since 2024, numerous studies have started applying the Mamba structure to medical image segmentation tasks, achieving promising results and positioning it as a potential alternative to traditional Transformer structures. The hybrid method, combining Mamba with CNNs, enhances segmentation accuracy and robustness by leveraging the feature extraction capabilities of CNN alongside the capability of Mamba to handle long-range dependencies. However, this approach may introduce additional computational complexity. In contrast, pure Mamba methods excel in tasks that require global contextual information but still face limitations in capturing spatial features within images and may demand higher computational resources during training. Overall, this paper systematically reviews and analyzes the development trajectory, advantages, and limitations of deep learning-based medical image segmentation methods from a structural perspective for the first time. First, all surveyed methods are categorized into three structural classes. Then, a brief overview of the structural evolution of different segmentation methods is provided, and their structural characteristics, strengths, and weaknesses are analyzed. Subsequently, the major challenges and opportunities encountered in the field of medical image segmentation are analyzed from multiple perspectives, including algorithm structure, learning methods, and task paradigms. Finally, an in-depth analysis and discussion of future development directions and application prospects are conducted.





