
# Principal Orthogonal Decomposition on Schlieren Images

Used POD to analyze the most influencing modes in the fully developed fluid flow using a schlieren imaging dataset generated
from a supersonic wind tunnel. Further implemented ESRGAN model and performed Canny Edge Deatection and Hough Transform to gain the physical entities associated with the fluid i.e Mach No. and Fluid velocity.



## Tools Required

- **Pandas** - Python data manipulation libraries

- **Open-CV** - Working with images

- **Scipy** - Performing SVD

- **Matplotlib** - Visualizing the images

- **ESRGAN** - Enhance the image resolution

- **Canny Edge Detection** - Generates boundaries from image

- **Hough Tranform** - Detects line and provide angle between two lines





## Roadmap

1. File Description
- [SVD(POD).ipynb](https://github.com/aman-095/Principal-Orthogonal-Decomposition-on-Schlieren-Images/blob/main/SVD(POD).ipynb)
    This contains the SVD model generated using the Schlieren Images.
- [Fluid_wave_angle.ipynb](https://github.com/aman-095/Principal-Orthogonal-Decomposition-on-Schlieren-Images/blob/main/Fluid_wave_angle%20(1).ipynb) This contains the image tranformation to binary pixel image and application of the Canny Edge Detection and Hough Transform.
- [POD.pdf](https://github.com/aman-095/Principal-Orthogonal-Decomposition-on-Schlieren-Images/blob/main/POD.pdf) This contains the significance of how SVD system works and the matrices associated to it with the physical significance as well.  
    
2. Pipeline
- Installing libraries and dependency
- Schlieren dataset generated is of High Resolution and SVD model generates a covariance matrix which makes computation difficult as the space required is huge in Tbs.
- Reduced the dimensions of the images which also reduced the quality of the images.
- Perform SVD with the code mentioned in [SVD(POD).ipynb](https://github.com/aman-095/Principal-Orthogonal-Decomposition-on-Schlieren-Images/blob/main/SVD(POD).ipynb) which would generate the top modes of the fluid flow.
- Apply ESRGAN model to re-enhance the resolution.
- Run the code file [Fluid_wave_angle.ipynb](https://github.com/aman-095/Principal-Orthogonal-Decomposition-on-Schlieren-Images/blob/main/Fluid_wave_angle%20(1).ipynb) which would lead to edge generation and further the properties associated with the fully developed flow.



## LR Top Node
![Sentiment](https://i.postimg.cc/Y2gv1W6h/pod-cov-1.jpg)
## HR Top Node
![Sentiment](https://i.postimg.cc/P5FfGXWg/pod-cov-1-out.jpg)

## Generated Edge
![Sentiment](https://i.postimg.cc/Y9XBF8dJ/POD.png)

## Report

[Report](https://github.com/aman-095/Principal-Orthogonal-Decomposition-on-Schlieren-Images/blob/main/POD.pdf)


## Feedback

If you have any feedback, please reach out to us at bhansali.1@iitj.ac.in


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://aman-095.github.io/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aman-bhansali-b4aa26228/)

