# A New Transfer Learning Based Traffic Classification Algorithm for a-Multi Domain SDN Network
This is the source code and experiment results in the paper ['A New Transfer Learning-Based Traffic Classification Algorithm for a Multi-Domain SDN Network'](https://dl.acm.org/doi/10.1145/3628797.3628804), published in the SOICT 2023 conference.

However, this is not the code that we used in the original paper. This is the code and results that were created in the Researchs of HUCE students, which included one original author of the paper (which is me :D), in order to re-run the experimetals.

This research is conducted along with Hải, Duy, Đạt, Phúc.

Raw data: [ETC Data](https://drive.google.com/drive/folders/15mljCBCCjsINtjM3CqB-afy2xZ0Shgp2)

## Abstract
To enhance the efficiency and resource utilization of a computer
network, it is imperative to classify network traffic and implement
distinct priority policies. Network traffic classification plays a pivotal role across various domains, including network administration,
cybersecurity, and network resource optimization. As encrypted
network data undergoes diverse evolution, as evident in datasets
from tech giants like Google, Facebook, and YouTube, traditional
traffic classification methods have given way to machine learningbased approaches. Given that computer networks are primarily
deployed as distributed multi-domain systems, employing machine
learning for traffic classification becomes challenging when a new
network domain appears with a limited dataset. One potential remedy is to employ transfer learning, allowing knowledge transfer
from a pre-trained model in an established domain to a new one. In
this paper, we present two contributions. First, a novel algorithm called Multi-class TrAdaBoost-CNN is introduced to tackle the challenge of cross-domain classification in encrypted network services.
This algorithm extends the Multi-class TrAdaBoost approach by
incorporating a Convolutional Neural Network (CNN) as a weak
learner. Secondly, extensive experiments are conducted on two
distinct domains characterized by imbalanced data distributions
to assess the efficacy of our proposed method. The experimental
results clearly demonstrate that our algorithm outperforms the traditional CNN model, achieving remarkable accuracy improvements
of up to 16%, even when dealing with extremely limited data.
