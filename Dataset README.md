


  <h3 align="center">Charades Multi Label Activity Recognition</h3>

  <p align="center">
    Trained models and results for Charades Activity Recognition Datasets
	</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents
- [Table of Contents](#table-of-contents)
- [About the project](#about-the-project)
<!--- [Getting Started](#getting-started)-->
<!--- [Usage](#usage)-->
- [Dataset Description](#dataset-description)  
	- [Dataset Summary](#dataset-summary)
    - [Languages](#languages)



<!-- ABOUT THE PROJECT -->
## About The Project

In this project we try to solve the problem of multi label activity recognition task on Charades dataset using Probabilistic Graphical Models. Multiple PGMs were tried to improve the performance - 

1. Markov Network. Inference Done using 
	1. 	MAP inference - using ILP
	2. Variable Elimination
	3. Iterative Join-Graph Propagation (IJGP)
2. Markov Networks with additional information (coming from NLP)
3. Mixture Models 
4. Dependency Networks 
5. Joint Learning between Dependency Networks and SlowFast

We use the SlowFast network as the feature extraction method for these. 

### Citing
When using this code, kindly reference:


```bibtex
@article{sigurdsson2016hollywood,
    author = {Gunnar A. Sigurdsson and G{\"u}l Varol and Xiaolong Wang and Ivan Laptev and Ali Farhadi and Abhinav Gupta},
    title = {Hollywood in Homes: Crowdsourcing Data Collection for Activity Understanding},
    journal = {ArXiv e-prints},
    eprint = {1604.01753}, 
    year = {2016},
    url = {http://arxiv.org/abs/1604.01753},
}
```
and
```bibtex
@misc{fan2020pyslowfast,
  author =       {Haoqi Fan and Yanghao Li and Bo Xiong and Wan-Yen Lo and
                  Christoph Feichtenhofer},
  title =        {PySlowFast},
  howpublished = {\url{https://github.com/facebookresearch/slowfast}},
  year =         {2020}
}
```

[Charades Multi Label Activity Recognition](https://github.com/IRVLUTD/Charades-Multi-Label-Activity-Recognition.git)


<!-- GETTING STARTED -->
<!--## Getting Started

In this section you should provide instructions on how to use this repository to recreate your project locally.

### Dependencies

Here, list all libraries, packages and other dependencies that need to be installed to run your project. Include library versions and how they should be installed if a special requirement is needed.

For example, this is how you would list them:
* Transformers 4.8.0
  ```sh
  conda install -c conda-forge transformers
  ```
* OpenCV 4.5.2
  ```sh
  conda install -c conda-forge opencv
  ```
### Alternative: Export your Environment

Alternatively, you can export your Python working environment, push it to your project's repository and allow users to clone it locally. This way, anyone can install it and they will have all dependencies needed. Here is how you export a copy of your Python environment:

  ```sh
  conda env export > requirements.yml
  ```

The user will be able to recreate it using:

  ```sh
  conda env create -f requirements.yml
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/catiaspsilva/README-template.git
   ```
2. Setup (and activate) your environment
  ```sh
  conda env create -f requirements.yml
  ```
-->
<!-- USAGE EXAMPLES -->
<!--## Usage

Use this space to show useful examples of how a project can be used. For course projects, include which file to execute and the format of any input variables.

Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_-->

## Dataset Description
- **Homepage:** https://prior.allenai.org/projects/charades
- **Repository:** https://github.com/gsig/charades-algorithms
- **Paper:** https://arxiv.org/abs/1604.01753
- **Leaderboard:** https://paperswithcode.com/sota/action-classification-on-charades
 
### Dataset Summary
Charades is dataset composed of 9848 videos of daily indoors activities collected through Amazon Mechanical Turk. 267 different users were presented with a sentence, that includes objects and actions from a fixed vocabulary, and they recorded a video acting out the sentence (like in a game of Charades). The dataset contains 66,500 temporal annotations for 157 action classes, 41,104 labels for 46 object classes, and 27,847 textual descriptions of the videos

### Languages
The annotations in the dataset are in English.

<!-- CONTRIBUTING -->
## Contributing

Any contributions you make are **appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.


<!-- Authors -->
## Authors

Your Name - [@ShivvratA](https://twitter.com/ShivvratA) - Shivvrat.Arya@utdallas.edu

Project Link: [Charades Multi Label Activity Recognition](https://github.com/IRVLUTD/Charades-Multi-Label-Activity-Recognition.git)


<!-- ACKNOWLEDGEMENTS -->
<!--## Acknowledgements

You can acknowledge any individual, group, institution or service.
* [Catia Silva](https://faculty.eng.ufl.edu/catia-silva/)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Pages](https://pages.github.com)
* [Animate.css](https://daneden.github.io/animate.css)
* [Loaders.css](https://connoratherton.com/loaders)
* [Slick Carousel](https://kenwheeler.github.io/slick)-->

## Thank you

<!--If this is useful: [![Buy me a coffee](https://www.buymeacoffee.com/assets/img/guidelines/download-assets-sm-1.svg)](https://www.buymeacoffee.com/catiaspsilva)-->
