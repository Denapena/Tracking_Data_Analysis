# Tracking_Data_Analysis

Using tracking data for the Champions League 2023 final between Manchester City and Inter Milan to compare Edin Džeko's and Romelu Lukaku's attacking runs. A project summary is in the pdf file with the plots of the attacking runs, the boxplots of distance and angle of the runs, and a short interpretation of the RunDžeko.mp4 file.

## Main tools used

* Pandas, Matplotlib and Numpy
* FFmpeg (for video animation)
* seaborn (for boxplots)
* Mplsoccer

## Getting started

* To run this program, you need Jupyter Notebook, Visual Studio Code, tracking data for the CL Final 2023, and an intermediate knowledge of Python
* The pitch plots and boxplots are made in the Jupyter File which has a step-by-step explanation of the coding process
* For the mp4 file Tracking_Data_Animation.py file is used which is taken and slightly modified from the Soccermatics Tracking Data Repository linked down below
* The biggest problem faced is the FFmpeg module which needs to be properly installed for the animation to be saved, linked below is the Stack Overflow solution that helped me fix my issues with the module 

## Author

Contributors names and contact info:
Denis Dervishi, denisdervishi@gmail.com

## License

This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [Soccermatics](https://soccermatics.readthedocs.io/en/latest/)
* [Soccermatics Tracking Data Repository](https://github.com/twelvefootball/twelve-respovision-CL-final)
* [Stack Overflow ffmpeg solution](https://stackoverflow.com/questions/60033397/moviewriter-ffmpeg-unavailable-trying-to-use-class-matplotlib-animation-pillo)
