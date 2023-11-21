# BetterSearch 🔎

This is the repository where the user interface of the BetterSearch system would be released soon.
Paper Link: [An Interactive Query Generation Assistant using LLM-based Prompt Modification and User Feedback](https://arxiv.org/abs/2311.11226)
Video: [Better Search IARPA Demonstration](https://www.youtube.com/watch?v=d1bN6vcQ4Lc)

BetterSearch, a cross-lingual search interface that supports automatic and interactive query generation over the [BETTER](https://www.iarpa.gov/research-programs/better) dataset. BetterSearch provides a simple document search interface that displays documents in their original language along with their English translations, making it simple for researchers to navigate and analyze search results. The tool also supports diverse query generation, allowing users to explore search results more comprehensively. More importantly, it combines search with a prompting-based query generation interface which permits users to refine their queries and prompts with retrieval information. The BetterSearch interface could work as an effective starting template for performing qualitative analysis over other information retrieval experiments and datasets as well as serve as a tool to incorporate retrieval feedback and Human-In-The-Loop (HITL) studies. 

Our lab developed the BetterSearch User Interface which is made up of 3 subsystems. Each of them are described below. Check this [video](https://youtu.be/d1bN6vcQ4Lc) for a complete demonstration.
- Cross-Lingual Event based Retrieval
- Automatic Query Generation
- Prompting Based Interactive Query Generation & Feedback
Each of the systems have been described on the [IRLab webpage](https://youtu.be/d1bN6vcQ4Lc) in detail.

## Code
We recommend running the colab code shared as a part of the [Query Explorer repository](https://github.com/emory-irlab/query-explorer/tree/main) - which is a general version of this project and provides seamless integration with HuggingFace (for generation) and PyTerrier (for retrieval).

### Citation

```bibtex
@misc{dhole2023interactive,
      title={An Interactive Query Generation Assistant using LLM-based Prompt Modification and User Feedback}, 
      author={Kaustubh D. Dhole and Ramraj Chandradevan and Eugene Agichtein},
      year={2023},
      eprint={2311.11226},
      archivePrefix={arXiv},
      primaryClass={cs.AI},
      url={https://arxiv.org/abs/2311.11226}
}
```
Kaustubh Dhole, Ramaraj Chandradevan, Eugene Agichtein (Emory IR Lab) and the JHU Team

The project is funded by the Intelligence Advanced Research Projects Activity ([IARPA](https://www.iarpa.gov/)).
