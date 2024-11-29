<p align="center">
  <picture>
    <img alt="DirectionAI" src="./IMG/new_label.png" width="660" height="100" style="max-width: 100%;">
  </picture>
</p>

<p align="center">
  🔅 <a href="./README.md" target="_blank">Chinese</a> &nbsp;| &nbsp;
  🌐 <a href="http://www.directionai.cn/" target="_blank">Online access link</a> &nbsp; | &nbsp;
  🔖 <a href="./Test_Account.md" target="_blank">Obtain a test account</a> &nbsp;
</p>

***

👋 Welcome to the **DirectionAI Teaching Practice Platform**, where you can experience your intelligent education assistant.👋 

  DirectionAI offers intelligent education services powered by cutting-edge AI technology, designed for scenarios in higher education, vocational training, and corporate training. It aims to create an intelligent and personalized teaching environment for educators and learners. Built on advanced domain-specific large models, self-evolution, and reasoning-enhanced core algorithms, DirectionAI supports and provides a full range of features such as **intelligent lesson plan generation, PPT creation, assignment guidance and assessment, AI-assisted learning, AI teaching assistants, video course tutoring, and programming guidance**, making teaching and learning more efficient and engaging.
  
  As an intelligent teaching assistant, DirectionAI can help educators optimize course design, generate personalized lesson plans and teaching materials, and achieve intelligent assignment evaluation. It also provides students with real-time learning assistance, video course tutoring, and customized recommendations based on their individual learning progress and performance, ensuring a deep understanding and mastery of key concepts. DirectionAI is committed to building an AI-powered educational ecosystem, creating a better teaching and learning experience for both teachers and students, and driving educational innovation. Here, every user can receive professional support from the AI assistant, making the learning process easier and more enjoyable, while ensuring more effective teaching outcomes.
  
https://github.com/user-attachments/assets/ed9e9aaa-57a3-486f-811a-d700c845bbe9


# News
🔥 Upcomings: SaaS service interfaces provided for AI education.

🔥 2024.11.21 DirectionAI is officially launched.


# Underlying model introduction

The DirectionAI platform integrates a series of algorithmic achievements from the DIRECT team, enabling efficient training and application of large models in the education sector. The education field is characterized by multi-disciplinary, cross-domain, high-difficulty knowledge, and multi-scenario features. Therefore, the DIRECT team, based on large model technology, focuses on researching the challenges in the intelligent education domain and has made breakthrough achievements. First, the team studied the large model [forgetting mechanism](https://arxiv.org/abs/2411.11932v1) and the [token-level domain transfer mechanism](https://arxiv.org/abs/2406.14828), guiding the training and inference of large models in the education sector for DirectionAI's educational services; Next, to enhance the capabilities of large educational models, we utilize the concept of [vertical domain model evolution](https://arxiv.org/abs/2411.11933) to train small-scale educational models and deploy them on the DirectionAI platform, supporting core functions such as AI teaching assistants, PPT generation, video course tutoring, and lesson plan generation; Finally, to address the complex reasoning and programming issues that may arise in courses, the DirectionAI platform also deploys mathematically enhanced reasoning models optimized through [process reasoning optimization](https://arxiv.org/abs/2411.11681), as well as [self-evolving code generation](https://arxiv.org/abs/2411.11053) programming guidance models, offering specialized functionality. The key papers are as follows:

- **Domain Knowledge Activation**: Based on the research findings in [Reviving Dormant Memories: Investigating Catastrophic Forgetting in Language Models through Rationale-Guidance Difficulty](https://arxiv.org/abs/2411.11932v1), we explored the knowledge activation mechanism of large models during domain transfer, addressing the critical issue of recalling and applying domain-specific knowledge in models.
- **Vertical Domain Capability Evolution**: We adopt the large model vertical domain evolution training scheme proposed in [METEOR: Evolutionary Journey of Large Language Models from Guidance to Self-Growth](https://arxiv.org/abs/2411.11933). This scheme consists of three stages: first, building foundational capabilities through domain knowledge distillation; second, iterative training under guidance to acquire self-judgment abilities; and finally, enabling the model's autonomous evolution. This progressive training approach ensures steady improvement in model capabilities.
- **Process Reasoning Alignment Optimization**: We implemented reasoning enhancement techniques from [PSPO: An Effective Process-supervised Policy Optimization for Reasoning Alignment](https://arxiv.org/abs/2411.11681). Traditional reinforcement learning algorithms have limited effectiveness in enhancing the model's reasoning ability. By adding nonlinear reward alignment on top of original reasoning alignment algorithms (such as PPO), we can further improve reasoning capabilities.
- **Self-evolving code generation：** We adopt the code enhancement technique proposed in [SRA-MCTS: Self-driven Reasoning Augmentation with Monte Carlo Tree Search for Enhanced Code Generation](https://arxiv.org/abs/2411.11053). This technique guides the model to self-generate high-quality intermediate reasoning paths during the code-generation process without adding extra supervised training.
  
# Research Details 
| Research Content | Github | Paper Link
|---------|--------|---------|
| 🌟 **SRA-MCTS** | 📖 [Github]() | 📄 [Paper](https://arxiv.org/abs/2411.11053)|
| 🌟 **Reviving Dormant Memories** | 📖 [Github]() | 📄 [Paper](https://arxiv.org/abs/2411.11932)|
| 🌟 **METEOR** | 📖 [Github]() | 📄 [Paper](https://arxiv.org/abs/2411.11933)|
| 🌟 **PSPO\*** | 📖 [Github]() | 📄 [Paper](https://arxiv.org/abs/2411.11933)|
| 🌟 **PSST** | 📖 [Github](https://github.com/shs910/PSST/tree/main?tab=readme-ov-file#psst-a-benchmark-for-evaluation-driven-text-public-speaking-style-transfer) | 📄 [Paper](https://aclanthology.org/2024.findings-emnlp.495.pdf)|
| 🌟 **TemplateGEC** | 📖 [Github](https://github.com/li-aolong/TemplateGEC) | 📄 [Paper](https://aclanthology.org/2023.acl-long.380/)|
| 🌟 **Word Matters** | 📖 [Github](https://github.com/li-aolong/Word-Matters) | 📄 [Paper](https://arxiv.org/abs/2406.14828)|
| 🌟 **In-Context Alignment** | 📖 [Github](https://github.com/li-aolong/how-far-can-ica-go) | 📄 [Paper](https://arxiv.org/abs/2406.11474)|

----
<p align="center"> <img src="./IMG/DIRECT.png" style="width: 80%;" id="title-icon">       </p>

# **Future Research Plans**

1. **Cognitive-Based Multi-Dimensional Evaluation**: The core of education is the person, and providing intelligence is one of the methods. The goal is to truly assist in the growth and education of individuals. Therefore, it is crucial to objectively and accurately assess the rationality of intelligent tools, evaluating students' abilities, learning stages, learning extension, learning potential, and the rationality of learning paths through AI education.
2. **Complex Problem/Task Planning and Reasoning**：Providing a goal-oriented, student-ability-appropriate learning path plan, involving key aspects of large models such as ability assessment, complex problem-solving and reasoning, and self-evolution.
3. **Contextual Long Text Generation**：Treating the student’s learning process or the teaching process as a complete story, in interactive scenarios, introducing knowledge and learning content into teaching sessions through story-based planning. This approach stimulates learning interest and inspires students to think deeply.
4. **Stylized/Emotional Dialogue**: Offering contextual, companion-style chat dialogues that help alleviate learning pressure and enhance the fun of learning.
5. **Value Alignment**: Guiding students toward goodness, learning, and knowledge acquisition.

👏 Welcome to join us and conduct research together!

🎈 [DIRECT Lab](https://github.com/DIRECT-BIT)

# FAQ
❓ [Engineering problem Q&A](https://github.com/DIRECT-BIT/DirectionAI/issues/new?assignees=&labels=&projects=&template=bug_report.md&title=)

❓ [Algorithm problem Q&A]()

