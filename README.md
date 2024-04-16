<div align="justify">

# Computational Techniques in Performance-Based Architectural Design: A Comprehensive Case Study

## Introduction
This repository showcases a comprehensive application of computational design techniques in architectural design, focusing on a commercial complex in Shanghai. By harnessing the capabilities of EvoMass, a C# based plugin for Rhino-Grasshopper developed by Prof. Likai Wang, this project represents a paradigm shift in architectural design processes. The research encapsulates a full-cycle computational design process, where the iterative generation and optimization of building massing are driven by performance factors such as daylighting, solar exposure, and thermal comfort using advanced genetic algorithms.

The novelty of this project lies in its systematic approach to integrating various computational techniques to address multiple design challenges concurrently. Unlike traditional methods that treat different design stages as isolated tasks, our approach synergizes massing, spatial layouts, and facade design into a cohesive workflow. This holistic methodology ensures that performance considerations are embedded at every stage, enabling the creation of buildings that are not only aesthetically pleasing but also environmentally responsive and sustainable.

Further, the project explores the potential of computational tools to push the boundaries of architectural design towards novel solutions that challenge conventional design norms. By leveraging tools like DIVA for performance simulation alongside EvoMass, the project demonstrates how computational design can lead to innovative building forms and functional spaces that adapt to their urban and environmental context. This study not only highlights the practical applications of these tools but also reflects on the limitations of current technologies, providing a critical analysis of the gap between research and practical implementation in architectural design. 

In doing so, the project aims to foster a new design ethos that prioritizes performance and sustainability, encouraging future architects to embrace computational design as a core element of the creative process. This case study not only serves as a model for future research but also as a benchmark for integrating scientific methods into the art of building design.

## Research Background
Performance-based architectural design (PBAD) is becoming essential, particularly in densely populated urban environments where sustainability is a priority. Traditional design practices often result in segmented stages of development that can hinder integrated performance outcomes. Our research addresses this gap by employing a full-circle application of computational techniques, from the initial conceptual design phase to detailed facade development. This approach is exemplified in our case study, which not only utilizes tools like EvoMass for dynamic building massing and DIVA for environmental performance simulation but also systematically incorporates architectural aesthetics, functionality, and regulatory compliance into the design process. This methodology fosters a comprehensive design strategy that enhances both the efficiency and the sustainability of the built environment, promoting a new paradigm in architectural design that is deeply rooted in research and practical application. The study presented in this repository reflects on existing limitations and explores new research design paradigms for performance-based architectural design in real-world scenarios, providing valuable insights into the integration of computational techniques across all key design issues.

## Key Contributions
- Demonstrates the effective use of computational tools like EvoMass and DIVA throughout the architectural design process.
- Presents a methodology for integrating performance criteria into the design process through computational design and optimization tools.
- Explores the impact of building form and facade design on overall building performance, with a focus on the practical application in a dense urban environment.

## Repository Structure
- **Code/**: Contains all scripts, including `Computational Techniques in Performance-Based Architectural Design A Comprehensive Case Study.gh` for the overall design process and `Computational Techniques in Performance-Based Architectural Design A Comprehensive Case Study(Fenestration generation with interference point).gh` for the facade design logic.
- **Data/**: Includes datasets like `CHN_SH_Shanghai-Hongqiao.Intl.AP.583670_TMYx.zip` used for climate analysis and performance simulations.
- **Docs/**: Contains the full research paper `From_Separation_to_Incorporation_-_A_Full-Circle_A.pdf` and additional documentation.
- **Examples/**: Demonstrates various applications of the computational tools in the design stages highlighted in the case study. This includes initial massing options, optimization of building form for performance, and detailed facade development.
- **LICENSE**: Details the terms under which this research and its associated code and data can be used.

## Installation and Usage
### Prerequisites
- **Rhino**: Ensure that Rhino is installed on your system as it hosts the Grasshopper environment.
- **Grasshopper**: A graphical algorithm editor integrated with Rhino's 3D modeling tools.
- **EvoMass and DIVA**: These plugins must be installed within Grasshopper to run the provided `.gh` files.

### Setting Up Your Environment
1. Install Rhino from the [official website](https://www.rhino3d.com/), it is recommended that its version is 6.0 or above.
2. Within Rhino, install Grasshopper (usually included with Rhino), Grasshopper comes with rhino 6.0 and above.
3. Download and install EvoMass and DIVA plugins following their respective installation guides.

### Running the Scripts
- Open Rhino and then launch Grasshopper.
- Load the provided `.gh` files into Grasshopper.
- Inputs can be modified in the Grasshopper interface to customize the design according to specific needs or constraints. This allows users to explore various design scenarios based on their unique requirements.

## Authors and Contributions
- **Yuhan Chen & Zhirui Bian**: Primarily responsible for the design and optimization simulations.
- **Tianyi Gu  & Youyu Lu**: Mainly focused on the drafting and preparation of the manuscript.
- **Likai Wang & Ziyu Tong**: Supervisors and advisors providing guidance throughout the research and development process.

## Conclusion and Future Directions

This study has demonstrated the efficacy of integrating computational design techniques across all stages of architectural design, from conceptualization to detailed facade development. By employing tools like EvoMass and DIVA, we were able to significantly enhance building performance, emphasizing the crucial role of computational methods in modern architectural practices.

Despite the advancements showcased in this research, there are several areas where further investigation could yield even more significant improvements:

1. **Integration of Machine Learning**: Future research could explore the integration of machine learning algorithms to predict and optimize building performance more dynamically, adapting to changing environmental conditions and user needs.

2. **Holistic Design Solutions**: There is a potential to develop more holistic design solutions that incorporate not only architectural considerations but also structural and environmental engineering aspects, providing a more integrated approach to sustainable building design.

3. **User-Centric Design Studies**: Further studies could focus on the impact of architectural design on user behavior and well-being, incorporating human-centered design principles into the computational design process.

4. **Scalability and Generalization**: Investigating the scalability of the proposed methods to different types of buildings and varying scales—from individual residential units to large commercial complexes—could broaden the applicability of our findings.

5. **Material Innovation**: Incorporating advanced material science into computational design processes could further optimize the sustainability and performance of buildings.

### Looking Forward: Collaboration Opportunities

We are keen to collaborate with academic peers, industry professionals, and technology developers to expand the scope of our research. Collaborative efforts could focus on refining computational tools, developing new materials, and testing these innovations in real-world settings. We invite interested parties to join us in pushing the boundaries of architectural design towards more sustainable and innovative futures.

Should you be interested in collaborating or wish to discuss potential projects, please do not hesitate to contact us.

## Citation
Please cite this research if it assists or influences your work:
```plaintext
Chen, Y., Lu, Y., Gu, T., Bian, Z., Wang, L., & Tong, Z. (2022). Computational Techniques in Performance-Based Architectural Design: A Comprehensive Case Study. DigitalFUTURES. https://doi.org/10.1007/978-981-16-5983-6_18

