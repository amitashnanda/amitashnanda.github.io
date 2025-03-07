---
layout: archive
title: "Projects"
permalink: /projects/
body_class: projects-page
author_profile: true
---

<div class="experience-section">

  <!-- Current Experience -->
  <div class="experience-entry">
    <img src="{{ '/images/p1.gif' | relative_url }}" alt="LBNL Logo" class="company-logo">
    <div class="experience-details">
      <h3>
        <a target="_blank" style="text-decoration: none;">Dynamic Load Balancing Algorithms in AMReX</a>
      </h3>
      <p><strong><a href="https://github.com/amitashnanda/ACM_PEARC_2025_Paper_Artifact.git">GitHub</a></strong></p>
      <p><span class="icon">📍</span> NERSC, LBNL </p>
      <!-- <p><span class="icon">📅</span> <em>June 2024 – Present</em></p> -->

  <ul class="experience-list">
        <li>Investigated the current-state of load balancing algorithms suitable for dynamic load balancing in domain decomposition based high-performance computing (HPC) simulations.</li>
        <li>Developed a novel hybrid load-balancing algorithm combining <strong>SFC and Knapsack</strong>, and an improved <strong>SFC bisection strategy</strong> using the <strong>painter’s</strong> algorithm.</li>
        <li><strong>painter’s</strong> partition-based algorithm outperform the original SFC-based strategies across all tested cases. Additionally, combination algorithms outperform their single-algorithm counterparts and should be evaluated for potential use in production-scale simulations. </li>
      </ul>
    </div>
  </div>


  <!-- Current Experience -->
  <div class="experience-entry">
    <img src="{{ '/images/p2.gif' | relative_url }}" alt="LBNL Logo" class="company-logo">
    <div class="experience-details">
      <h3>
        <a target="_blank" style="text-decoration: none;">CHAI-KTQ: A Novel Framework for Scalable Large Language Models and Efficient Inference</a>
      </h3>
      <p><strong><a href="https://github.com/amitashnanda/CHAI-KTQ.git">GitHub</a></strong></p>
      <p><span class="icon">📍</span> Boolean Lab, UCSD </p>
      <!-- <p><span class="icon">📅</span> <em>June 2024 – Present</em></p> -->

  <ul class="experience-list">
        <li> Developed <strong>CHAI-KTQ</strong>, a novel framework designed to enhance efficiency while maintaining robust performance. It introduces three key extensions: <strong>CHAI Quant, CHAI Target, and CHAI Knowledge Distillation (CHAI KD)</strong>. </li>
        <li>CHAI Quant employs mixed-precision quantization for clustered attention heads, reducing Key-Value (K, V) cache size by up to <strong>55%</strong> and improving latency by <strong>40%</strong>, all while keeping accuracy deviations below <strong>1%</strong>.</li>
        <li>CHAI Target focuses on targeted fine-tuning of sensitive layers identified through attention sensitivity analysis, ensuring robust predictions and reducing uncertainty in critical tasks. </li>
        <li>CHAI KD enables efficient knowledge transfer from large teacher models to lightweight student models, achieving speed gains of <strong>3000</strong> inferences/sec for <strong>125M</strong> models with competitive performance on knowledge-intensive tasks like PIQA and RTE.</li>
      </ul>
    </div>
  </div>
  
  <!-- Current Experience -->
  <div class="experience-entry">
    <img src="{{ '/images/p3.gif' | relative_url }}" alt="LBNL Logo" class="company-logo">
    <div class="experience-details">
      <h3>
        <a target="_blank" style="text-decoration: none;">CPTQuant - A Novel Mixed Precision Post-Training Quantization Techniques for Large Language Models</a>
      </h3>
      <p><strong><a href="https://github.com/amitashnanda/Mixed_Precision_Quantization.git">GitHub</a></strong></p>
      <p><span class="icon">📍</span> Boolean Lab, UCSD </p>
      <!-- <p><span class="icon">📅</span> <em>June 2024 – Present</em></p> -->

  <ul class="experience-list">
        <li>Developed <strong>CPTQuant</strong>, a comprehensive strategy that introduces correlation-based <strong>(CMPQ)</strong>, pruning-based <strong>(PMPQ)</strong>, and Taylor decomposition-based <strong>(TDMPQ)</strong> mixed precision techniques.</li>
        <li>CMPQ adapts the precision level based on canonical correlation analysis
            of different layers. PMPQ optimizes precision layer-wise based on their sensitivity to sparsity. TDMPQ modifies precision using Taylor decomposition to assess each layer's sensitivity to input perturbation
        .</li>
        <li>CPTQuant demonstrates up to <strong>4x</strong> compression and a <strong>2x-fold</strong> increase in efficiency with minimal accuracy drop compared to Hugging Face <strong>FP16</strong>.</li>
        <li>PMPQ demonstrates an <strong>11%</strong> higher compression ratio than other methods for classification tasks, while TDMPQ achieves a <strong>30%</strong> greater compression ratio for language modeling tasks.</li>
      </ul>
    </div>
  </div>


  <div class="experience-entry">
    <img src="{{ '/images/p4.gif' | relative_url }}" alt="LBNL Logo" class="company-logo">
    <div class="experience-details">
      <h3>
        <a target="_blank" style="text-decoration: none;">Pruning of Clients Based on Conformal Prediction Sets in a Federated Setup</a>
      </h3>
      <p><strong><a href="https://github.com/amitashnanda/conformal_prediction_FL.git">GitHub</a></strong></p>
      <p><span class="icon">📍</span> Boolean Lab, UCSD </p>
      <!-- <p><span class="icon">📅</span> <em>June 2024 – Present</em></p> -->

  <ul class="experience-list">
        <li>Researching a practical approach to develop a framework for incorporating meaningful uncertainty quantification in a distributed and continual learning environment, enabling more reliable decision-making in federated settings. (both IID and Non-IID cases).</li>
        <li>Experimented Federated Learning approaches <strong>(FedAvg and FedProx)</strong> combined with Conformal Prediction methods <strong>(LAC, APS, and RAPS)</strong> on <strong>CIFAR-10/CIFAR-100</strong> datasets, using a <strong>ResNet-18</strong> model pretrained on ImageNet.</li>
        <li>The study examines and compares model performance, uncertainty quantification, and robustness of prediction sets under both IID (identically and independently distributed) and non-IID client data distributions.</li>
      </ul>
    </div>
  </div>


  <div class="experience-entry">
    <img src="{{ '/images/p11.gif' | relative_url }}" alt="LBNL Logo" class="company-logo">
    <div class="experience-details">
      <h3>
        <a target="_blank" style="text-decoration: none;">FedNAMs: Performing Interpretability Analysis in Federated Learning Context</a>
      </h3>
      <p><strong><a href="https://github.com/amitashnanda/FedNAM.git">GitHub</a></strong></p>
      <p><span class="icon">📍</span> Boolean Lab, UCSD </p>
      <!-- <p><span class="icon">📅</span> <em>June 2024 – Present</em></p> -->

  <ul class="experience-list">
        <li>Federated learning is continuously evolving but faces challenges in interpretability and explainability. To address these issues, a creative approach has been introduced that employs <strong>Neural Additive Models (NAMs)</strong> within a federated learning framework.</li>
        <li>FedNAMs combine the strengths of NAMs, which allow individual networks to focus on specific input features, with the decentralized nature of federated learning. This integration results in more interpretable analysis while enhancing privacy by training on local data across multiple devices. As a result, the risks associated with data centralization are minimized, and the model's robustness and generalizability are improved.
        </li>
        <li>Research using various text and image classification tasks, such as datasets from <strong>OpenFetch ML Wine, UCI Heart Disease, and Iris</strong> demonstrates that FedNAMs achieve strong interpretability with minimal loss in accuracy compared to traditional Federated Deep Neural Networks (DNNs). The study reveals significant findings, including the identification of key predictive features both at the client level and the global level.</li>
      </ul>
    </div>
  </div>



  <div class="experience-entry">
    <img src="{{ '/images/p5.gif' | relative_url }}" alt="LBNL Logo" class="company-logo">
    <div class="experience-details">
      <h3>
        <a target="_blank" style="text-decoration: none;">Communication Efficient Asynchronous Peer-to-Peer Federated LLMs</a>
      </h3>
      <p><strong><a href="https://github.com/Sreebhargavibalijaa/Building-Communication-Efficient-Asynchronous-Peer-to-Peer-Federated-LLMs-with-Blockchain.git">GitHub</a></strong></p>
      <p><span class="icon">📍</span> Boolean Lab, UCSD </p>
      <!-- <p><span class="icon">📅</span> <em>June 2024 – Present</em></p> -->

  <ul class="experience-list">
        <li>Developed a secure, efficient, and privacy-preserving federated learning approach in a decentralized setting. Further, this work addresses the challenge of communication overhead in peer-to-peer networks by optimizing the path for weight transfer and mitigating node anomalies.</li>
        <li>Experiments were conducted to evaluate memory usage and latency in server and serverless environments. Our results demonstrate a <strong>5X</strong> decrease in latency and a <strong>13%</strong> increase in accuracy for serverless cases. </li>
        <li>Comparisons between synchronous and asynchronous scenarios revealed a <strong>76%</strong> reduction in information passing time for the latter. The PageRank method is most efficient in eliminating anomalous nodes for better performance of the global federated LLM model. </li>
      
      </ul>
    </div>
  </div>



  <div class="experience-entry">
    <img src="{{ '/images/p6.gif' | relative_url }}" alt="LBNL Logo" class="company-logo">
    <div class="experience-details">
      <h3>
        <a target="_blank" style="text-decoration: none;">Leveraging High-Performance Computing for Spatial Transcriptomic Identification of CDX2 Genes in Intestinal Crypts Using Deep Neural Network</a>
      </h3>
      <p><strong><a href="https://github.com/amitashnanda/MacST.git">GitHub</a></strong></p>
      <p><span class="icon">📍</span> Boolean Lab, UCSD </p>
      <!-- <p><span class="icon">📅</span> <em>June 2024 – Present</em></p> -->

  <ul class="experience-list">
        <li>Spatial transcriptomics provides a valuable link between gene expression patterns and specific locations within tissues. By analyzing the spatial distribution of gene expression, insights can be gained into the molecular characteristics and functional diversity of cells residing in different regions of tissues.</li>
        <li>Developed a <strong>YOLOv8-based</strong> instance segmentation model to recognize the shape of crypts and glands in the intestines tissue. Identifying these structures enables us to pinpoint genes differentially expressed along the crypt axis, specifically those influenced by immune cells, such as macrophage and epithelial genes. </li>
        <li>The <strong>Yolov8</strong> model for gland and crypt achieves an <strong>mAP50</strong> score of <strong>0.937</strong>, an <strong>mAP50-95</strong> score of <strong>0.567</strong>, as well as an <strong>mAP50</strong> score of <strong>0.748</strong> and an <strong>mAP50-95</strong> score of <strong>0.654</strong>, respectively.</li>
      
      </ul>
    </div>
  </div>


  <div class="experience-entry">
    <img src="{{ '/images/p7.gif' | relative_url }}" alt="LBNL Logo" class="company-logo">
    <div class="experience-details">
      <h3>
        <a target="_blank" style="text-decoration: none;">OrgaTuring: Accelerating Organoid Discovery with Vision-AI</a>
      </h3>
      <p><strong><a href="https://github.com/amitashnanda/OrgaTuring-Accelerating-Organoid-Discovery-with-visual-AI.git">GitHub</a></strong></p>
      <p><span class="icon">📍</span> Boolean Lab, UCSD </p>
      <!-- <p><span class="icon">📅</span> <em>June 2024 – Present</em></p> -->

  <ul class="experience-list">
        <li>Developed an interpretable CNN-based deep learning model to automate and streamline the microscopic analysis of organoid images. The model enables the real-time location, quantification, tracking, and classification of Crohn's disease organoids from 2D and 3D images.</li>
        <li>Analyzed large confocal microscopic images with small sample sizes. Implemented focal loss to handle class imbalance and G-mean for better thresholding. The DNN, trained with <strong>DenseNet-121</strong>, achieved a testing accuracy of <strong>75%</strong> and an <strong>AUC-ROC</strong> of <strong>0.67</strong>. Additionally,  incorporated model interpretability techniques using SHAP  and applied domain adaptation methods. </li>
        <li>Exploring learning  methods such as <strong>zero-shot</strong> and <strong>few-shot</strong> learning to effectively handle small sample sizes Additionally, creating patches from large images to develop a classification model  and a probabilistic method for class prediction. Also working on a novel conformal prediction technique that incorporates a dynamic level adjustment method, which computes sensitivity maps based on gradient magnitudes.</li>
      
      </ul>
    </div>
  </div>

  <div class="experience-entry">
    <img src="{{ '/images/p8.gif' | relative_url }}" alt="LBNL Logo" class="company-logo">
    <div class="experience-details">
      <h3>
        <a target="_blank" style="text-decoration: none;">Expression Gradient of Cancer Suppressor Gene using Vision-AI</a>
      </h3>
      <p><strong><a href="https://github.com/amitashnanda/Colon_Mask_RCNN">GitHub</a></strong></p>
      <p><span class="icon">📍</span> Boolean Lab, UCSD </p>
      <!-- <p><span class="icon">📅</span> <em>June 2024 – Present</em></p> -->

  <ul class="experience-list">
        <li>Introduced an original work for gland instance segmentation using <strong>Mask R-CNN</strong> and <strong>Yolo-v8</strong> on colon tissue to diagnose colon cancer. Annotated first public U-shaped colon dataset.</li>
        <li>Mask R-CNN outperformed models like SegNet and UNet, achieving <strong>F1</strong> and <strong>IoU</strong> scores of <strong>(0.98, 0.97)</strong> for backgrounds, <strong>(0.63, 0.46)</strong> for glands, and <strong>(0.59, 0.42)</strong> for crypts, respectively.</li>
        <li>Yolo-v8 model outperformed Mask R-CNN with mean Average Precision at <strong>50%</strong> overlap (mAP50) scores of <strong>0.937</strong> for glands and <strong>0.748</strong> for crypts. Additionally, differentially expressed genes along the crypts, verified on <strong>25</strong> slides, predicted over<strong>5,000</strong> U-shaped glands.</li>
      
      </ul>
    </div>
  </div>


  <div class="experience-entry">
    <img src="{{ '/images/p9.gif' | relative_url }}" alt="LBNL Logo" class="company-logo">
    <div class="experience-details">
      <h3>
        <a target="_blank" style="text-decoration: none;">Impact-of-Feature-Correlation-on-Feature-Importance-using-SHAP</a>
      </h3>
      <p><strong><a href="https://github.com/amitashnanda/Impact-of-Feature-Correlation-on-Feature-Importance-using-SHAP.git">GitHub</a></strong></p>
      <p><span class="icon">📍</span> Dey’s Lab, UCSD </p>
      <!-- <p><span class="icon">📅</span> <em>June 2024 – Present</em></p> -->

  <ul class="experience-list">
        <li>Conducted a detailed analysis to determine if Shapley interaction values effectively capture feature correlations and enhance feature ranking accuracy.</li>
        <li>This research focused on examining the correlation between blood pressure and various health behaviors like sleep, exercise, diet, and stress management.</li>    
      </ul>
    </div>
  </div>


   <div class="experience-entry">
    <img src="{{ '/images/p10.gif' | relative_url }}" alt="LBNL Logo" class="company-logo">
    <div class="experience-details">
      <h3>
        <a target="_blank" style="text-decoration: none;">Particle-Filter and Visual-Inertial SLAM</a>
      </h3>
      <p><strong><a href="https://github.com/amitashnanda/Visual-Inertial-Simultaneous-Localization-and-Mapping">GitHub</a></strong></p>
      <p><span class="icon">📍</span> ERL Lab, UCSD</p>
      <!-- <p><span class="icon">📅</span> <em>June 2024 – Present</em></p> -->

  <ul class="experience-list">
        <li>This project addresses an approach to solving the SLAM (Simultaneous Localization and Mapping) problem for autonomous vehicles. The method consists of three main steps: IMU (Inertial Measurement Unit) Localization through EKF (Extended Kalman Filter) Prediction, Landmark Mapping via EKF Update, and Visual-Inertial SLAM.</li>
        <li>Implemented the differential-drive motion and scan-grid correlation observation models for simultaneous localization and occupancy-grid mapping.</li>    
        <li>A visual-inertial simultaneous localization and mapping (SLAM) system was developed using Python’s extended Kalman filter (EKF). The EKF was prioritized over sparse SLAM approaches like Particle Filter or Factor Graph-based methods due to its dual prediction-update framework, which efficiently tracks an autonomous system’s state over time while concurrently estimating landmark positions.</li>   
      </ul>
    </div>
  </div>



</div>


