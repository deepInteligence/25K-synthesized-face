# Human Faces Dataset Generated by Stable Diffusion

## Overview
This dataset contains over 25,000 high-quality synthetic human face images generated using the Stable Diffusion model. It is designed to support research and development in computer vision, machine learning, and related fields. The images represent diverse demographics, including variations in age, gender, ethnicity, and facial expressions.
![Alt text](Logo.jpg)

## Motivation
Creating datasets for face analysis often involves ethical concerns regarding privacy and consent. Synthetic data generated by models like Stable Diffusion addresses these concerns while still providing realistic and diverse samples. This dataset aims to:
- Facilitate research in face recognition, analysis, and generation.
- Provide a resource free from ethical constraints associated with real human data.
- Enable testing and validation of models in applications like emotion recognition, demographic analysis, and more.

## Dataset Details
- **Number of Images**: 25,000 including 12,500 images for male and 12,500 images for female
- **Resolution**: 512x512 pixels (consistent for all images).
- **Format**: png
- **Content**: Each image features a single synthetic human face.
- **Variations**: Includes a wide range of attributes:

# age
| This   | range       |
| ---    | ------     |
| childhood | [1,3] |
| child part one | [3,6] |
| child part two | [6,8] |
| child part three | [9,11] |
| adolescence | [12,20] |
| youth | [20,35] |
| middle age | [35,50] |
| adulthood | [50,80] |
| late adulthood | [80,101] |

# face emotions 
```
happy, sad, afraid, angry, surpriesd, disgusted, neutral, faer, crying, yelling, pissed off face
```
# special prompts
```
wearing glasses, wearing sun glasses, eatnig, wearing headphones, 
long hair, highly make up, Freckle, make up", , scar on face, 
eyeshadow, put Hand in front of hair, Bald, put hand in back of head
(sleepy,close eyes:1.4), wearing Hejab, with a hat
```
# hair colors
```
Black hair, Dark brown hair, Dark brown hair, Natural brown hair, Light brown hair, Chestnut brown hair,
Light chestnut brown hair, Auburn hair, Red hair, Orange red hair, Copper hair, Titian hair,
Strawberry blond hair, Light blond hair,  Golden blond hair, Medium blond hair,
Gray hair, White hair, fantasy color, fashion color
```
# human races
```
Caucasian, African, Asian, Hispanic, Iranina, Arabian, American, Irish, Sout american, chinese, korean, Mongols
```

## Dataset Structure
The dataset is organized as follows:
```
- dataset/
  - images/
    - picture_0000001c1c1c7e7f.png
    - picture_c190b8f17470f3f1.png
    - ...
```
- **images/**: Contains all face images.
- **readme.md**: all information about dataset

## Generation Process
The dataset was generated using the Stable Diffusion model, a state-of-the-art text-to-image diffusion model. Custom prompts were crafted to ensure diversity in demographic and stylistic attributes. Post-processing was performed to ensure uniform resolution and quality.

## Usage
This dataset is free to use for academic and commercial purposes under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. Users are required to provide appropriate credit if using this dataset in their work.

## Potential Applications
- Training and testing face recognition algorithms.
- Research on bias in facial analysis models.
- Development of generative models.
- Applications in augmented reality, virtual reality, and gaming.

## Limitations
While synthetic data eliminates privacy concerns, it is not a perfect replacement for real-world data. Models trained solely on synthetic datasets may not generalize well to real-world scenarios. Users are advised to combine this dataset with other sources for better performance.

## Citation
If you use this dataset, please cite it as follows:
```
@dataset{synthetic human face,
  title={Human Faces Dataset Generated by Stable Diffusion},
  author={deepintelligence},
  year={2025},
  publisher={deepintelligence},
  url={https://deepintelligence.ir/}
}
```

## Contact
For any questions or feedback, please contact [deep.intelligence.team@gmail.com].


