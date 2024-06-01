# LifeHack2024

# Automated Knowledge Graph Creation and Querying for Terrorism Reports Using LLMs

## **Introduction**

In the context of terrorism, reports and articles often contain extensive, unstructured text that is challenging to analyze and cross-reference in an automated manner. For instance, articles about a single terror incident might arrive at different times throughout the day, each with varying details. These reports typically include crucial entities such as _persons, objects, locations, and events_.

#### **Goals**

1. Extract entities from these reports and represent them in a structured knowledge graph.
2. Develop a chatbot capable of answering questions based on the generated knowledge graph.

## Our Solution

<p align="center">
<img src="./assets/logo.png" alt="TerrorViz" width="200"/>
</p>
In an age where timely and accurate information is crucial, our solution revolutionizes how you handle the influx of articles related to terror events. Our cutting-edge system streamlines and enhances the process of extracting critical insights from a deluge of incoming reports.

First, we perform **coreference resolution** to clarify contexts and references within the articles. Then, our advanced Large Language Model (LLM) extracts specific entities and their relationships (**entity/ relationship disambiguation**), integrating them into a comprehensive **knowledge graph**. Articles are intelligently chunked, with entities **linked to their respective extracts** for precise, context-aware tracking.

For retrieval, we deploy a **Multi-agent LLM system** designed to excel in the high-stakes environment of terror event reporting. This system resolves complex relationships, **identifies key entities**, generates detailed **follow-up questions**, retrieves pertinent **extracts**, and provides concise **summaries**. Additionally, it features a **decisor** agent to make informed, real-time decisions based on the aggregated data.

Our solution transforms the overwhelming influx of terror-related articles into clear, actionable intelligence, empowering security professionals and decision-makers to respond swiftly and effectively. Stay informed, stay prepared, and make critical decisions with confidence.

## Schema of this Document

> [construct_kgraph.ipynb](https://github.com/Project-Hackathons/LifeHack2024/blob/main/construct_kgraph.ipynb) Documents how to constructing the knowledge Graph

> [retrival.ipynb](https://github.com/Project-Hackathons/LifeHack2024/blob/main/retrival.ipynb) Documents how to query the Knowledge Graph

## Watch our video!

[![LifeHack2024](/assets/logo_blackbg.png)](https://www.youtube.com/watch?v=JBG5-A4jyVk)
