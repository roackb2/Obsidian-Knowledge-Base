# Yann LeCun分享願景：讓AI系統像動物和人類一樣學習和推理

https://ai.facebook.com/blog/yann-lecun-advances-in-ai-research/


為了創建能像人類和動物一樣學習和推理的AI系統，Meta AI 的首席AI科學家Yann LeCun 提議建立能學習“世界模型”（即內部模型，揭示世界運作方式）的AI模型。在Meta AI的Inside the Lab活動中，LeCun 提出了一個用於自主智能的模塊化、可配置的架構，並強調了建立這樣一個系統需要解決的關鍵挑戰。

LeCun 提出的架構由六個可微分模塊組成：配置器、感知、世界模型、成本、行為者和短期記憶模塊。其中最為複雜的世界模型模塊，負責估算感知未提供的世界狀態信息，並預測世界的可行未來狀態。

構建具有多種可能預測並忽略無關細節的預測世界模型是一個關鍵挑戰。聯合嵌入預測架構（JEPA）是一個解決方案，它捕捉輸入之間的依賴關係並產生有關它們的信息抽象表示。分層的JEPA可以通過觀察和互動學習世界的運作方式，從而實現復雜行為的分層規劃。

尚有許多挑戰，例如訓練世界模型，確定評論家，構建和訓練配置器，以及使用短期記憶追踪世界狀態。然而，LeCun 和其他Meta AI研究人員對於持續的基礎研究能帶來更深入的對心靈和機器理解表示信心，這將使得人工智能得以受益。

In an effort to create AI systems that learn and reason like humans and animals, Yann LeCun, Chief AI Scientist at Meta AI, proposes building AI models that can learn "world models" or internal models of how the world works. During Meta AI's Inside the Lab event, LeCun presented a modular, configurable architecture for autonomous intelligence and highlighted key challenges that need to be addressed to create such a system.

LeCun's proposed architecture is composed of six differentiable modules: the configurator, perception, world model, cost, actor, and short-term memory modules. The most complex module, the world model, estimates missing information about the world and predicts plausible future states of the world.

A critical challenge lies in constructing a predictive world model that can represent multiple plausible predictions while ignoring irrelevant details. The Joint Embedding Predictive Architecture (JEPA) is a solution that captures dependencies between inputs and produces informative abstract representations of them. A hierarchical JEPA can learn how the world works through observation and interaction, allowing for hierarchical planning of complex actions.

Many challenges remain, such as training world models, defining the critic, constructing and training the configurator, and using short-term memory to track the world state. However, LeCun and other Meta AI researchers are confident that continued fundamental research will lead to a deeper understanding of minds and machines, benefiting AI development.


#WorldModelAI #YannLeCun #MetaAI #AutonomousIntelligence #FutureTech