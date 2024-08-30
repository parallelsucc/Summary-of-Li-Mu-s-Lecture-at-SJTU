# Summary of Li Mu's Lecture at SJTU

[简体中文](README.zh.md) | English

## Part 1: Language Models

The construction of language models revolves around three core elements: computational power, data, and algorithms. Li Mu vividly compares machine learning to traditional Chinese medicine, with deep learning and language models likened to "alchemy": data serves as the raw materials, computational power as the furnace, and algorithms as the alchemical formula. While deep learning is tailored to specific domain problems, language models possess broad cross-domain adaptability.

### Hardware Development Trends

Hardware plays a crucial role in the development of language models, presented here in decreasing order of importance:

1. **Bandwidth**

   * As language models scale up, distributed training becomes necessary. The current speed of each optical fiber is 400 Gb, transitioning to 800 Gb (Infiniband Ethernet).
   * The GB200 72NVL model integrates 72 GPUs, each with a speed of 1.8 TB/s. Despite using optical fiber for data transmission, even nanosecond-level delays can impact performance in distributed training.

2. **Memory**

   * Modern models are large and require substantial memory. Current technology supports 192GB of memory per chip, but this has reached its limit. Without technological breakthroughs, the memory limit for future chips may cap at 200GB, directly limiting model size.

3. **Computational Power**

   * As Moore's Law advances, processor nanotechnology becomes more refined, and frequency increases. The mature application of 8-bit floating-point numbers and the introduction of 4-bit floating-point numbers enhance bandwidth utilization, further boosting computational power.

4. **Resources**

   * Larger chips demand more power and cooling. One thousand chips require one megawatt of power. Without effective cooling solutions, liquid cooling may become necessary.

5. **Alternative Solutions**

   * Other chip manufacturers like Google TPUv6, Intel Habana 3, and AMD Mi350 perform well in inference tasks but struggle to compete with NVIDIA in training.

### Model Development

Moore's Law drives the growth of model sizes, reducing training costs and shortening training time annually.

1. **Language Models**

   * Current pre-training scales range from 10-50T tokens, with parameter sizes between 100-500B. While larger closed-source models exist, they often use MoE (Mixture of Experts), with an effective size still around 500B.

2. **Speech and Voice Models**

   * End-to-end models excel in emotion and tone expression, with latency reduced from 1s to 300ms, significantly enhancing human-computer interaction.

3. **Music Generation**

   * The technology is mature, with current challenges primarily related to copyright issues. Large companies resolve this by purchasing copyrights, while smaller companies face more restrictions.

4. **Image Generation**

   * Resolution has surpassed 1MP, but generating images with a "soul" remains a new challenge.

5. **Video Generation**

   * Training costs for video generation are currently high, with continuity and consistency between frames being key difficulties.

6. **Multimodal Models**

   * The trend is towards integrating data from multiple modalities such as text, images, audio, and video, with text information showing particularly strong generalization capabilities.

### Application Scenarios

1. **Liberal Arts Professionals**

   * Language models greatly enhance the efficiency of liberal arts professionals, with applications in personal assistants, customer service, document processing, gaming and entertainment, and education.

2. **Engineering Professionals**

   * While language models cannot yet fully replace engineering professionals, they significantly reduce workload, especially in software engineering.

3. **Blue-Collar Workers**

   * Language models perform exceptionally in autonomous driving, but progress in robotics is slower due to a lack of data and high training difficulty.

|          |    Simple Tasks    |    Complex Tasks    |
|:--------:|:--------------:|:--------------:|
| Liberal Arts |     😄    | 😞 |
| Engineering | 😞 | 😭 |
| Blue-Collar  | 😭 | 😭 |

### Conclusion and Outlook

1. **Pre-training and Post-training Are Equally Important**

   * Pre-training has transitioned from a technical issue to an engineering challenge, while post-training still requires technical exploration.

2. **Challenges in Vertical Domain Models**

   * Domain-specific models that focus on complex rule adherence, reasoning, and mathematical calculations need to possess general domain skills.

3. **Evaluation Is Crucial**

   * The complexity of real-world applications demands precise evaluation; simple evaluations often fail to accurately reflect model performance.

4. **The Importance of Data**

   * Data determines the upper limit of a model, while algorithms determine the lower limit. Current research is still far from achieving AGI (Artificial General Intelligence), with future efforts likely focusing heavily on data.

5. **Computational Power**

   * Building GPUs in-house versus renting them shows little difference in cost due to NVIDIA's monopoly. However, owning GPUs may be beneficial when handling massive data volumes.

### The Future of Language Models

The development of language models is gradually pushing beyond the boundaries of traditional machine learning. The challenges and opportunities coexist, with future research focusing on improving data quality, optimizing algorithms, and deepening the application of multimodal integration and vertical domain models.

## Part 2

For insights into Li Mu's experiences in personal development and career planning, please refer to the following Zhihu articles:

- [Reflection on Five Years of Work](https://zhuanlan.zhihu.com/p/374777591)
- [PhD Journey Over Five Years](https://zhuanlan.zhihu.com/p/25099638)
- [One Year of Entrepreneurship, Three Years of Life](https://zhuanlan.zhihu.com/p/714533901)

---

If there are any inaccuracies or areas for improvement in this summary, your feedback is welcome.
