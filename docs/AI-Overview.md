# Artificial Intelligence Overview

This document will explain the basics of Artificial Intelligence (AI), providing a foundational understanding of what AI is, its core concepts, and its importance in today's world.

# What is AI?

Artificial intelligence (AI) is the intelligence exhibited by machines, encompassing the ability to perceive, synthesize, and infer information. This stands in contrast to intelligence displayed by non-human animals and humans. AI performs a wide range of tasks, including speech recognition, computer vision, translation between natural languages, and various other mappings of inputs. (Source: [Wikipedia](https://en.wikipedia.org/wiki/Artificial_intelligence))

## A Brief History of AI

This is a brief history of the AI:

![AI History](img/AI-History.png)

- In 1950, Alan Turing published "Computing Machinery and Intelligence," which laid the groundwork for the concept of AI.
- In 1956, John McCarthy coined the term "Artificial Intelligence" and organized the Dartmouth Workshop, a pivotal moment in AI history.
- In 1957, Frank Rosenblatt constructed the Mark 1 perceptron, an early form of a machine learning algorithm inspired by the human brain.
- The 1960s and 1970s saw significant AI research, including the development of expert systems and the introduction of the LISP programming language for AI applications.
- In the 1980s, neural networks became widely used for pattern recognition and prediction, leading to advancements in AI capabilities.
- A groundbreaking moment occurred in 1997 when IBM Deep Blue defeated Garry Kasparov, the world chess champion, in a historic chess match.
- In 2011, IBM Watson demonstrated its prowess by beating champions in the quiz show Jeopardy, showcasing AI's ability to understand natural language and generate answers.
- In 2016, DeepMind's AlphaGo made headlines by defeating the world Go champion, highlighting the potential of AI in complex strategic games.

## Understanding Artificial Intelligence

To grasp the essence of artificial intelligence, it's essential to explore three fundamental aspects:

* **What AI can do?**
* **How does AI do it?**
* **What are its limits?**

## What AI Can Do?

To understand what AI can do you need to classify AI by Capabilities, Types, and Functionalities.

* **Capabilities**: Narrow AI, General AI, Super AI.
* **Functionalities**: Interactive AI, Functional AI, Analitic AI, Visual AI, Text AI.
* **Types**: Reactive Machine, Limited Memory, Theory of Mind, Self Awareness

![What AI Can Do?](img/What-AI-Can-Do.png)

### AI Capabilities

In artificial intelligence, ANI, AGI, and ASI are acronyms that refer to different capabilities of artificial intelligence:

* **Artificial Narrow Intelligence (ANI)**, which refers to AI systems that are able to perform specific tasks autonomously, but lack general cognitive abilities like those of humans. An example of ANI is voice recognition on a smartphone. ChatGPT is in this class.
* **Artificial General Intelligence (AGI)**, which refers to AI systems that have the ability to perform generic intellectual tasks, such as the ability to learn and solve problems, similar to human intelligence. AGI is considered a step beyond ANI and is still largely a theoretical concept.
* **Artificial Superintelligence (ASI)**, which refers to hypothetical AI systems that would surpass human intelligence in all areas. ASI is currently purely hypothetical, and its development could potentially lead to a technological singularity.

![AI Capabilities](img/AI-Capabilities.png)

### AI Types

The type of AI in operation based on functionalities can be classified into:

* **Reactive Machines**, designed for a specific task, this AI receives input, and acts on this input. They cannot be applied to different tasks, and past experience doesn’t affect the current decision. Examples are AI chess players.
* **Limited Memory AI**, this types of AI receives current input, and add pieces of this input to its programmed representation of the world. This can change the way the AI makes current or new decisions. Examples are virtual assistant like Siri, Alexa, etc.
* **Self Aware**, this is advanced artificial intelligence with self-awareness and self-monitoring capabilities, raising ethical and philosophical questions about artificial consciousness.
* **Theory of Mind**, which refers to hypothetical AI systems that would surpass human intelligence in all areas. ASI is currently purely hypothetical, and its development could potentially lead to a technological singularity.

![AI Types](img/AI-Types.png)

### AI Functionalities

AI serves various functionalities across domains:

* **Interactive AI:** These AI systems can interact with users naturally and provide assistance. Examples include Siri and Alexa, which respond to voice commands and queries.
* **Functional AI:** AI is developed to perform specific functions in various domains, such as recommendation systems that suggest products or content and chatbots that engage in conversation with users.
* **Analytic AI:** AI algorithms are employed to analyze large datasets and extract meaningful insights, applied in market analysis, fraud detection, medical diagnostics, and more.
* **Visual AI:** Visual AI processes and interprets visual data, including facial and image recognition, enabling applications like security systems and autonomous vehicles.
* **Text AI:** Text AI specializes in processing and analyzing textual data, including natural language understanding and text generation. It's the foundation for chatbots, sentiment analysis, and language translation.

### Traditional AI areas and tasks

Artificial Intelligence encompasses a wide range of tasks and capabilities, typically categorized into six major areas:

* **Computer Vision**: This field focuses on enabling machines to interpret and understand visual information from images and videos, including tasks like image classification, object detection, and facial recognition.
* **Natural Language Processing (NLP)**: NLP deals with enabling machines to understand and generate human language. Tasks within NLP include sentiment analysis, language translation, and text summarization.
* **Multi-Modal AI**: Multi-modal AI combines information from various sources, such as text, images, and audio, to gain a deeper understanding of data and context, enabling applications like multimedia content analysis.
* **Audio Processing**: This area involves processing and analyzing audio data, including speech recognition and music recommendation systems.
* **Reinforcement Learning**: Reinforcement learning is a subset of machine learning that focuses on training agents to make sequential decisions in an environment, commonly used in robotics and game AI.
* **Tabular Data Analysis**: Tabular data analysis involves working with structured data in tables or databases, commonly used in financial analysis and data reporting.

Within each of these areas, there are specific tasks and algorithms that enable AI systems to perform various functions. These tasks, when combined with classical programming algorithms, contribute to the automation and bridge the gap between human and machine capabilities, ushering in an era of increased automation and intelligent decision-making.

![AI Task Areas](img/AI-Task-Areas.png)

## How does AI Work?

Once we've clarified what AI can do and understood that AI applications are essentially combinations of classical programming algorithms and basic AI tasks, it's important to recognize that there isn't a single approach to achieving these tasks. Over the years, several distinct areas have developed, all falling under the umbrella of Artificial Intelligence.

* **Expert Systems**: Expert systems rely on pre-defined rules and knowledge bases to make decisions and solve problems. They excel in well-defined domains and are commonly used in areas like medical diagnosis and decision support systems.
* **Evolutionary Computation**: This branch harnesses the principles of natural selection to evolve solutions to complex problems. Genetic algorithms, a prominent example, optimize solutions through simulated evolution.
* **Machine Learning (ML)**: Machine learning, the most prominent and widely applied branch of AI, empowers computers to learn from data and improve their performance over time. Within machine learning, one area has garnered significant attention: Deep Learning.

Deep learning is a subset of machine learning that has revolutionized AI capabilities, particularly in tasks related to perception and understanding. At its core, deep learning involves artificial neural networks inspired by the human brain. These networks consist of interconnected layers of neurons that can automatically learn to represent data.

Within the realm of deep learning, two crucial subfields have emerged:

* **Generative AI**: Generative models have the remarkable ability to create new data that resembles existing data. They are employed in tasks like image generation, text-to-speech synthesis, and data augmentation.
* **Foundation Models**: These are large-scale deep learning models that serve as the basis for a wide range of AI applications. Examples include BERT (Bidirectional Encoder Representations from Transformers) for natural language understanding and GPT (Generative Pre-trained Transformer) for various language generation tasks.

![AI Areas](img/AI-Areas.png)






AI systems operate through algorithms and data processing methods, often involving machine learning and deep learning techniques. These algorithms enable AI to make predictions, recognize patterns, and provide meaningful outputs. Key components of AI include:

- **Data:** AI requires large amounts of data for training and fine-tuning its models. Datasets are essential for building AI systems that can generalize from examples.

- **Algorithms:** AI algorithms are the mathematical and computational engines that drive machine learning. They include decision trees, neural networks, support vector machines, and more.

- **Training:** AI models learn from data through a process called training, where they adjust their parameters to minimize errors and improve performance.

### AI's Limits

While AI has made significant strides, it has limitations that are important to consider:

- **Data Dependency:** AI heavily relies on high-quality, diverse datasets for training. Biased or incomplete data can lead to biased or inaccurate AI outcomes.

- **Lack of Common Sense Reasoning:** Most AI lacks true common sense reasoning abilities, which humans possess naturally. AI may struggle with understanding context and making judgments based on broader knowledge.

- **Ethical and Societal Concerns:** The ethical use of AI, including issues of privacy, fairness, and bias, remains a crucial challenge.

In this article, we will delve deeper into each of these aspects to provide a comprehensive overview of the fascinating field of artificial intelligence. We'll explore the latest developments, applications, and future possibilities in the world of AI.

