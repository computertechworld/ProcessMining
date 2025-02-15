# ProcessMining
A curated list of open source tools and resources for process mining
# Awesome Open-Source Process Mining Resources

This curated list of 40 resources is designed for developers and process analysts eager to get started with process mining. All resources listed here are free to use—most come with open‐source code (or detailed implementation guides) and provide comprehensive overviews of the tool landscape. Whether you’re looking for frameworks, algorithms, log converters, visualization tools, or supporting libraries, this list has you covered!

> **Note:** If an open‐source GitHub repository is available, the link is provided. Otherwise, a website or reference link is given.

---

## 1. Comprehensive Process Mining Suites & Frameworks (6 Resources)
1. **ProM Framework** – The seminal Java-based suite offering a rich plug-in architecture for process discovery, conformance, performance analysis, and simulation.  
   • [Website & Documentation](http://promtools.org/)
2. **RapidProM** – Integrates ProM’s algorithms into RapidMiner, blending data mining with process analytics in an accessible, open‐source environment.  
   • [GitHub Repository](https://github.com/rapidprom/rapidprom)
3. **PM4Py** – A comprehensive Python library for process discovery, conformance checking, performance analysis, and visualization.  
   • [GitHub Repository](https://github.com/pm4py/pm4py-core)
4. **bupaR** – An ecosystem of R packages that enable process mining, discovery, and performance analysis using the powerful R data science environment.  
   • [GitHub Repository](https://github.com/BupaR/bupaR)
5. **OpenXES** – A Java library implementing the XES standard for event logs, ensuring interoperability between process mining tools.  
   • [GitHub Repository](https://github.com/openxes/openxes)
6. **ProM-Plugins** – A community-driven collection of plug-ins that extend the capabilities of the ProM framework with innovative algorithms and tools.  
   • [GitHub Repository](https://github.com/PromPlugins/ProM-Plugins)

---

## 2. Process Discovery Algorithms & Tools (8 Resources)
7. **Inductive Miner** – A robust algorithm for discovering sound process models from event logs; several open-source implementations exist (e.g., in PM4Py).  
   • [PM4Py Inductive Miner](https://github.com/pm4py/pm4py-inductive-miner)
8. **Heuristics Miner** – An algorithm adept at handling noise and infrequent behavior in event logs; widely implemented in open-source projects like PM4Py.  
   • [PM4Py Heuristics Miner](https://github.com/pm4py/pm4py-heuristics-miner)
9. **Fuzzy Miner** – Simplifies complex processes by filtering out less significant behavior; originally available as a ProM plug-in with open documentation.  
   • [ProM Fuzzy Miner Info](http://promtools.org/) (see ProM documentation)
10. **Split Miner** – Balances simplicity and accuracy in process discovery by effectively handling noisy event logs.  
    • [PM4Py Split Miner](https://github.com/pm4py/pm4py-split-miner)
11. **Evolutionary Tree Miner** – Uses evolutionary algorithms to discover process trees from complex logs; an excellent resource for advanced research.  
    • [PM4Py Evolutionary Tree Miner](https://github.com/pm4py/pm4py-evolutionary-tree-miner)
12. **Inductive Visual Miner** – Enhances the Inductive Miner with interactive visualization, aiding model exploration and validation.  
    • [GitHub Repository](https://github.com/ivm/inductive-visual-miner)
13. **Trace Clustering Techniques** – Resources and sample implementations for clustering event log traces to uncover process variants (often available within PM4Py).  
    • [PM4Py Trace Clustering](https://github.com/pm4py/pm4py-trace-clustering)
14. **Process Cube Miner** – Mines multidimensional process models to capture variations across different process perspectives.  
    • [PM4Py Process Cube Miner](https://github.com/pm4py/process-cube-miner)

---

## 3. Conformance Checking & Performance Analysis Tools (6 Resources)
15. **Alignment-Based Conformance Checker** – Uses alignment techniques to measure deviations between event logs and process models.  
    • [PM4Py Alignment Checker](https://github.com/pm4py/pm4py-alignment-checker)
16. **Token-Based Replay Analyzer** – Evaluates process conformance and identifies performance bottlenecks by replaying event logs on process models.  
    • [PM4Py Token Replay](https://github.com/pm4py/pm4py-token-replay)
17. **Conformance Checker for bupaR** – An R module for detailed conformance and deviation analysis, integrated within the bupaR ecosystem.  
    • [GitHub Repository](https://github.com/BupaR/bupaR-conformance)
18. **Performance Analysis Dashboard** – An interactive dashboard that visualizes performance metrics extracted from event logs.  
    • [PM4Py Performance Dashboard](https://github.com/pm4py/pm4py-performance-dashboard)
19. **Deviation Analysis Tool** – Provides detailed insights into deviations between observed behavior and prescribed process models.  
    • [PM4Py Deviation Analysis](https://github.com/pm4py/deviation-analysis)
20. **Conformance Visualization Toolkit** – A set of visualization techniques for displaying conformance checking results, helping to pinpoint areas of non-compliance.  
    • [PM4Py Conformance Visualizer](https://github.com/pm4py/conformance-visualizer)

---

## 4. Event Log Handling & Data Conversion (6 Resources)
21. **CSV2XES Converter** – Converts CSV-based event logs into the XES standard to facilitate process mining analysis.  
    • [GitHub Repository](https://github.com/pm4py/csv2xes)
22. **MXML2XES Converter** – Transforms legacy MXML logs to the XES format, ensuring seamless integration with modern process mining tools.  
    • [GitHub Repository](https://github.com/pm4py/mxml2xes)
23. **XES Standard & Documentation** – Comprehensive documentation and resources on the XES standard, essential for understanding event log formats.  
    • [XES Standard Website](http://www.xes-standard.org/)
24. **EventLog Explorer** – A tool for exploring, cleaning, and pre-analyzing raw event logs before applying mining algorithms.  
    • [GitHub Repository](https://github.com/pm4py/eventlog-explorer)
25. **Log Preprocessing Techniques** – Open-source code samples and tutorials for preprocessing and normalizing event logs.  
    • [PM4Py Log Preprocessor](https://github.com/pm4py/log-preprocessor)
26. **XES Processing Utilities** – A collection of utilities for filtering and manipulating XES logs to enhance analysis quality.  
    • [GitHub Repository](https://github.com/openxes/xes-utils)

---

## 5. Visualization & Dashboard Tools (4 Resources)
27. **Apromore Community Edition Dashboard** – An advanced, interactive process mining platform offering comprehensive dashboards and visual analytics.  
    • [GitHub Repository](https://github.com/apromore/ApromoreCore) or [Website](https://apromore.org/)
28. **Process Mining Dashboard** – A sample, open-source dashboard built using PM4Py that visualizes key performance indicators and process insights.  
    • [GitHub Repository](https://github.com/pm4py/process-mining-dashboard)
29. **ProM Visualizer** – A plug-in for the ProM framework designed to render process models and conformance
