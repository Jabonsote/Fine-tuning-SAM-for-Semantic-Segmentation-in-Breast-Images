<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />

  <h1 align="center"></h1>

  <p align="center">
  Fine tuning SAM for Semantic Segmentation in breast images

</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

<!-- [![Product Name Screen Shot][product-screenshot]](   ) -->

This repository contains implementations and models related to the semantic segmentation of breast images. The main goal is to apply fine-tuning to the Semantic-SAM model to enhance accuracy in the segmentation of mammary structures.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

[![PyTorch][PyTorch.io]][PyTorch-url]
[![Python][Python.org]][Python-url]
[![Jupyter Lab][JupyterLab.org]][JupyterLab-url]
[![MLflow][MLflow.org]][MLflow-url]


<p align="right">(<a href="#readme-top">back to top</a>)</p>




## Getting Started
This repository provides an example of how to set up your project locally. Follow these simple steps to get a local copy up and running.

## Prerequisites
Make sure you have the following prerequisites installed:

Python (recommended version: 3.6 or higher)
Required Python packages (specified in requirements.txt):
´´´
pip install -r requirements.txt
´´´
## Structure
The starter code supports input in Coco format with the following directory structure:

   ```
|   ├── dataset_/
│   ├── train/
│   │   ├── _annotations.coco.json  # COCO format annotation
│   │   ├── 000001.png              # Images
│   │   ├── 000002.png
│   │   ├── ...
│   ├── val/
│   │   ├── _annotations.coco.json  # COCO format annotation
│   │   ├── xxxxxx.png              # Images
│   │   ├── ...

   ```


Ensure that your dataset adheres to this structure for seamless compatibility.

Download Model Checkpoints
Download the necessary Semantic-SAM (SAM) model checkpoints and organize your repository as follows:


   ```
├── dataset_name/                # Dataset structure as detailed above
│   ├── ...
├── segment-anything/            # The FAIR SAM repository
│   ├── ...
├── SAM/                         # SAM pretrained checkpoints
│   ├── sam_vit_h_4b8939.pth
│   ├── ...
├── finetune.py
├── ...

   ```




Feel free to adapt this structure to your specific use case. Happy coding! 🚀🔍

Remember to replace placeholders like dataset_name with your actual dataset name and customize the instructions according to your project’s needs.

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._


1. Clone the repo
   ```
   git clone https://github.com/your_username_/Project-Name.git](https://github.com/Jabonsote/Fine-tuning-SAM-for-Semantic-Segmentation-in-Breast-Images.git
   ```
2. 
   ```
   
   ```
3. 
   ```
   
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage



_For more examples, please refer to the [Documentation](https://segment-anything.com/)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [x] Code Fine-tuning
- [] Implementation ML FLow


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch
3. Commit your Changes 
4. Push to the Branch 
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

javier.ramirez.gonzalez@uabc.edu.mx


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/Jabonsote/Fine-tuning-SAM-for-Semantic-Segmentation-in-Breast-Images
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png

[Pytorch.io]: https://raw.githubusercontent.com/github/explore/224672533a7f836ad6bf142e4dee61217cfc100e/topics/pytorch/pytorch.png
[Pytorch-url]: https://pytorch.org/
[Python.org]: https://www.python.org/static/community_logos/python-logo.png
[Python-url]: https://www.python.org/
[JupyterLab.org]: https://nanohub.org/app/site/groups/29044/uploads/jupyter.png
[JupyterLab-url]: https://jupyter.org/
[MLflow.org]: https://mlflow.org/docs/latest/_static/MLflow-logo-final-black.png
[MLflow-url]: https://mlflow.org/
