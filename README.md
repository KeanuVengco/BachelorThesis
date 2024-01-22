# Edge AI: Deploying Computer Vision at the Edge for Optical Sorting of Recyclables

![BSc 002](https://github.com/KeanuVengco/BachelorThesis/assets/150190271/f9d4e60a-28f4-4fde-94b1-fda901e8fbdc)

<b> Abstract </b> <br>
The thesis explores the domain-intersection of digital signal processing, artificial intelligence, and edge computing, to provide a robust theoretical foundation for the practical application of computer vision at the edge. The methodology comprises training an object detection model on detecting recyclable materials and optimizing its deployment for an edge device. The Raspberry Pi 4 will serve as the edge device and is equipped with a USB-camera and a Coral Edge TPU accelerator. The approach consists of a machine learning pipeline ranging from data collection, data processing, model training, model deployment, and evaluation. The tests will be evaluated on key performance metrics in respect to optical sorting on a recyclable waste data set. The proof of concept seeks to demonstrate the feasibility and evaluate the performance of applying advanced AI technology in a cost-effective manner to provide a scalable and extensible solution for visual operations.

<b> Problem Statement </b> <br>
As environmental pressures increase, governments are adopting policies and the private sector is increasing investments to address evolving threats. A Bain & Company research reveals that 55% of large businesses are committed to circularity, driving innovative solutions across the value chain [1]. The United Nations calls for action to ensure improved solid waste management in its Sustainable Development Goals (SDGs) [2]. This is challenged by the surge in e-waste, projected to more than double by 2050. This uptick is due to shorter product lifecycles and an increase in the number of Internet-connected devices. BCG research highlights that only 20% of this e-waste is currently recycled, with barriers being the labor intensive manual separation of mixed waste [3]. A lack of consistent and reliable waste data also limits improvements in waste management and recycling. The Wall Street Journal reports on an increase of investments in waste management and sorting since the passing of the US Climate Bill in 2022 [4]. McKinsey & Company identifies AI as a key role for accelerating the transition to a circular economy [5]. Due to high variable costs, lack of efficiency and health hazards, the use of manual labor for waste sorting is limited. Analysis show that automated systems are more economical in the long run and reduce overall recycling costs [6]. AI has the potential to optimize sustainability efforts for the circular infrastructure.

<b> Concept Solution </b> <br>
The proposed conceptual solution is a vision system for optical waste sorting. It comprises a custom-trained and deployed computer vision model to detect and classify different categories of waste and recyclables, including paper, plastics, metal and glass among others. The concept aims to prove the feasibility of integrating advanced AI technology at the edge, with the potential to increase efficiency by reducing reliance on manual labor, and advance efforts towards scalable solutions for sustainability.

<b> Proof of Concept </b> <br>
The Pipeline.ipynb provides the code documentation and serves as a proof of concept for the thesis. It encompasses the entire process from initial setup to final model deployment, demonstrating the practical application of Edge AI in the field of optical waste sorting. Each section of the notebook — Setup, Data Collection, Data Processing, Model Training, Model Deployment, and Testing & Evaluation — is designed to showcase the development of an object detection model optimized for edge computing devices.

References: <br>
[1] Bain & Company. Joshua Hinkel et al. Strategy in a circular world. Sept. 2023. url: https://www.bain.com/insights/strategy-in-a-circular-world/. <br>
[2] Lars Carlsen and Rainer Bruggemann. “The 17 United Nations’ sustain- able development goals: A status by 2020”. In: International Journal of Sustainable Development & World Ecology 29.3 (2022), pp. 219–229. <br>
[3] BCG. Janice Lee et al. Don’t throw away the opportunity in e-waste. June 2023. url: https://www.bcg.com/publications/2023/seizing-opportunity-ewaste-recycling. <br>
[4] WSJ. Ryan Dezember. Wall street’s next big play is Garbage. May 2023. url: https://www.wsj.com/articles/wall-streets-next-big-play-is-garbage-b7b2ff4d. <br>
[5] McKinsey. Jan. 2019. url: https://www.mckinsey.com/capabilities/sustainability/our-insights/artificial-intelligence-and-the-circular-economy-ai-as-a-tool-to-accelerate-the-transition. <br>
[6] McKinsey. Wenting Gao et al. Addressing the challenges of plastic waste: Circu- larity and leakage. Sept. 2022. url: https://www.mckinsey.com/industries/chemicals/ourinsights/addressing-the-challenges-of-plastic-waste-circularity-and-leakage.


