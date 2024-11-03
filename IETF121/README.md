# Large Language Model (LLM) for Networking
* Topic: Large Language Model (LLM) for Networking
* Time: 15:00-16:30 Nov 5, Tuesday (Dublin, Ireland time)
* Location: Wicklow Hall 2A
* Host: Yong Cui (Tsinghua University), Xiaohui Xie (Tsinghua University)
* IETF Side Meeting wiki: https://wiki.ietf.org/en/meeting/121/sidemeetings#meeting-tuesday
* Online access method (videoconference): https://ietf.webex.com/meet/ietfsidemeeting2

## Motivations
Large language models (LLMs), exemplified by GPT, have achieved remarkable performance in various tasks, such as machine translation, text-to-image generation, and embodied intelligence. Thanks to their vast number of parameters, LLMs can memorize a massive amount of knowledge and utilize tools based on commands. We believe that LLMs can also assist with tasks within networking scenarios. This side meeting will explore the transformative potential of LLMs in the networking domain and open the discussion on potential standards for this topic. 

## Agenda
* [2 minutes] Opening
* [15 minutes] The Practical Application and Future Prospects of AISecOps
  * Speaker: Zhan Shu (NSFOCUS)
  * Abstract: At our AI Security Operations Center, we have successfully implemented a multi-model system for noise reduction and alert triage, using small models to handle initial filtering and prioritization. Building on this, we deployed a large model to automate the analysis of filtered alerts, resulting in a fully operational, intelligent security framework. While this system has achieved significant progress, we continue to encounter challenges in practical deployment. Here, we present insights on the role of AI in security operations and share solutions that leverage AI to enhance operational efficiency and resilience.
* [15 minutes] NetLLM: Adapting Large Language Models for Networking
  * Speaker: Fangxin Wan (The Chinese University of Hong Kong)
  * Abstract: Deep learning (DL) is increasingly used in networking tasks to tackle complex prediction and optimization problems. However, the current approach requires significant engineering effort due to the need for manual design of deep neural networks (DNNs) for various tasks, often leading to poor generalization on unseen data. Inspired by the success of large language models (LLMs), we investigate the adaptation of LLMs for networking, aiming for a more sustainable design philosophy. LLMs, with their robust pre-trained knowledge, have the potential to function as a universal model for multiple tasks, enhancing performance and generalization. We introduce NetLLM, the first framework designed to leverage the capabilities of LLMs with minimal effort to address networking challenges. NetLLM enables LLMs to process multimodal data effectively and generate task-specific responses efficiently while significantly lowering the costs of fine-tuning for domain knowledge. Through three networking use cases—viewport prediction, adaptive bitrate streaming, and cluster job scheduling—we demonstrate that LLMs adapted via NetLLM considerably outperform existing state-of-the-art algorithms, showcasing the framework's effectiveness and the promise of LLMs in advancing networking solutions.
* [15 minutes] Do Large Language Models Dream of Sockets?
  * Speaker: Jari Arkko (Ericsson)
  * Abstract: This talk will discusses the concept of protocol Large Language Models (LLMs). These are models capable of conversing in native protocol messages. These models could potentially be used to help understand protocols, e.g., diagnose errors from packet traces. Our ongoing research investigates the feasibility of these models, their applications, and limitations. We present our preliminary results, including how LLMs understand the behavior of example systems such as web servers. Our contribution focuses on testing how and how well an LLM can diagnose protocol traces, receive and send protocol messages over sockets, and handle complex protocol fields and interfaces.
* [15 minutes] AI for Network Technology Innovation and Practice
  * Speaker: Liang Zhang (Huawei)
  * Abstract: Generative AI, led by models like ChatGPT, has rapidly transformed the AI application landscape, driving industry innovation. Large Language Models (LLMs) are now central to emerging AI applications, including intelligent Q&A, content and code generation, and AI agents. Two main trends are evident: (1) In networking, LLMs are primarily applied to intelligent operations and maintenance (O&M) and secure operations, with companies like Microsoft and FT releasing dedicated products. (2) The demand for AI in edge devices is accelerating the miniaturization of LLMs, making model quantization and knowledge distillation essential techniques for this evolution. This talk will aslo introduce three technology challenges of AI4Net.
* [15 minutes] iBNG: Empowering Broadband Network Gateways with AI
  * Speaker: Shengnan Yue (China Mobile)
  * Abstract: The Broadband Network Gateway (BNG) is a key anchor for the development of network intelligence services. iBNG empowers the BNG with AI, introducing  computation platform and intelligent plane as an intelligent brain, and applies AI to enhance network operations, services, and security.
* [15 minutes] LLM for Network Management
  * Speaker: Xiaohui Xie (Tsinghua University)
  * Abstract: In the rapidly evolving field of network management, integrating Large Language Models (LLMs) offers transformative potential. This talk explores how LLMs can enhance various aspects of network management, including configuration, fault detection, performance optimization, and security. We will examine case studies and practical applications where LLMs have successfully improved network efficiency and reliability. Additionally, we will discuss the challenges and future directions in implementing LLMs for network management.
* [20 minutes] Free Discussion (Several open questions will be provided soon)
