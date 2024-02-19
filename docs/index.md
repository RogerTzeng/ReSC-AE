Deep learning techniques have shown promising results in automatic respiratory sound classification. However, distinguishing respiratory sounds in real world noisy conditions pose challenges for the system to be used in clinical settings. Instead of noise injection augmentation that is conventionally done, we propose an audio enhancement (AE) pipeline prior to the respiratory sound classification system. Our AE pipeline is an adversarial network that is trained on real-world clinical noise.
Integrating this pipeline improved the ICBHI classification score by 4.24% on ICBHI respiratory sound dataset and by 3.57% on our recently-collected Formosa Archive of Breath Sounds (FABS) in multi-class noisy scenarios, compared to the baseline method of noise injection data augmentation. More importantly, the enhanced audio aids adoption by clinicians. In our physician validation study, we quantitatively demonstrate improvements in efficiency, diagnostic confidence, and trust during model-assisted diagnosis with our system over raw noisy recordings. Workflows integrating enhanced audio increased 11.61% diagnostic sensitivity and reached high-confidence diagnoses. Our system showcases audio enhancement as an effective methodology for increasing robustness and clinical utility of AI-assisted respiratory sound analysis. 

## Normal Samples: 

We recommend using headphones for this section.

|            | Noisy                                                                              | Target                                                                             |  MANNER | CMGAN|
|------------|------------------------------------------------------------------------------------|------------------------------------------------------------------------------------|---------|------|
|            | ![](samples/origin/p360_001_mic1.png)                                              | ![](samples/origin/p361_002_mic1.png)                                              |         |      |
| Sample N0  | <audio src="samples/origin/p360_001_mic1.wav" controls="" preload=""></audio>      | <audio src="samples/origin/p361_002_mic1.wav" controls="" preload=""></audio>      |         |      |
|            | ![](samples/x2-nuwave/p360_001_mic1.png)                                           | ![](samples/x2-nuwave/p361_002_mic1.png)                                           |         |      |
| Sample N1  | <audio src="samples/x2-nuwave/p360_001_mic1.wav" controls="" preload=""></audio>   | <audio src="samples/x2-nuwave/p361_002_mic1.wav" controls="" preload=""></audio>   |         |      |
|            | ![](samples/x2-nuwave+/p360_001_mic1.png)                                          | ![](samples/x2-nuwave+/p361_002_mic1.png)                                          |         |      |
| Sample N2  | <audio src="samples/x2-nuwave+/p360_001_mic1.wav" controls="" preload=""></audio>  | <audio src="samples/x2-nuwave+/p361_002_mic1.wav" controls="" preload=""></audio>  |         |      |
|            | ![](samples/x2-nuwave2/p360_001_mic1.png)                                          | ![](samples/x2-nuwave2/p361_002_mic1.png)                                          |         |      |
| Sample N3  | <audio src="samples/x2-nuwave2/p360_001_mic1.wav" controls="" preload=""></audio>  | <audio src="samples/x2-nuwave2/p361_002_mic1.wav" controls="" preload=""></audio>  |         |      |
|            | ![](samples/x2-nuwave2+/p360_001_mic1.png)                                         | ![](samples/x2-nuwave2+/p361_002_mic1.png)                                         |         |      |

## Crackle Samples:

We recommend using headphones for this section.

|            | Noisy                                                                              | Target                                                                             |  MANNER | CMGAN|
|------------|------------------------------------------------------------------------------------|------------------------------------------------------------------------------------|---------|------|
|            | ![](samples/origin/p360_001_mic1.png)                                              | ![](samples/origin/p361_002_mic1.png)                                              |         |      |
| Sample N0  | <audio src="samples/origin/p360_001_mic1.wav" controls="" preload=""></audio>      | <audio src="samples/origin/p361_002_mic1.wav" controls="" preload=""></audio>      |         |      |
|            | ![](samples/x2-nuwave/p360_001_mic1.png)                                           | ![](samples/x2-nuwave/p361_002_mic1.png)                                           |         |      |
| Sample N1  | <audio src="samples/x2-nuwave/p360_001_mic1.wav" controls="" preload=""></audio>   | <audio src="samples/x2-nuwave/p361_002_mic1.wav" controls="" preload=""></audio>   |         |      |
|            | ![](samples/x2-nuwave+/p360_001_mic1.png)                                          | ![](samples/x2-nuwave+/p361_002_mic1.png)                                          |         |      |
| Sample N2  | <audio src="samples/x2-nuwave+/p360_001_mic1.wav" controls="" preload=""></audio>  | <audio src="samples/x2-nuwave+/p361_002_mic1.wav" controls="" preload=""></audio>  |         |      |
|            | ![](samples/x2-nuwave2/p360_001_mic1.png)                                          | ![](samples/x2-nuwave2/p361_002_mic1.png)                                          |         |      |
| Sample N3  | <audio src="samples/x2-nuwave2/p360_001_mic1.wav" controls="" preload=""></audio>  | <audio src="samples/x2-nuwave2/p361_002_mic1.wav" controls="" preload=""></audio>  |         |      |
|            | ![](samples/x2-nuwave2+/p360_001_mic1.png)                                         | ![](samples/x2-nuwave2+/p361_002_mic1.png)                                         |         |      |

## Wheeze Samples: 

We recommend using headphones for this section.

|            | Noisy                                                                              | Target                                                                             |  MANNER | CMGAN|
|------------|------------------------------------------------------------------------------------|------------------------------------------------------------------------------------|---------|------|
|            | ![](samples/origin/p360_001_mic1.png)                                              | ![](samples/origin/p361_002_mic1.png)                                              |         |      |
| Sample N0  | <audio src="samples/origin/p360_001_mic1.wav" controls="" preload=""></audio>      | <audio src="samples/origin/p361_002_mic1.wav" controls="" preload=""></audio>      |         |      |
|            | ![](samples/x2-nuwave/p360_001_mic1.png)                                           | ![](samples/x2-nuwave/p361_002_mic1.png)                                           |         |      |
| Sample N1  | <audio src="samples/x2-nuwave/p360_001_mic1.wav" controls="" preload=""></audio>   | <audio src="samples/x2-nuwave/p361_002_mic1.wav" controls="" preload=""></audio>   |         |      |
|            | ![](samples/x2-nuwave+/p360_001_mic1.png)                                          | ![](samples/x2-nuwave+/p361_002_mic1.png)                                          |         |      |
| Sample N2  | <audio src="samples/x2-nuwave+/p360_001_mic1.wav" controls="" preload=""></audio>  | <audio src="samples/x2-nuwave+/p361_002_mic1.wav" controls="" preload=""></audio>  |         |      |
|            | ![](samples/x2-nuwave2/p360_001_mic1.png)                                          | ![](samples/x2-nuwave2/p361_002_mic1.png)                                          |         |      |
| Sample N3  | <audio src="samples/x2-nuwave2/p360_001_mic1.wav" controls="" preload=""></audio>  | <audio src="samples/x2-nuwave2/p361_002_mic1.wav" controls="" preload=""></audio>  |         |      |
|            | ![](samples/x2-nuwave2+/p360_001_mic1.png)                                         | ![](samples/x2-nuwave2+/p361_002_mic1.png)                                         |         |      |