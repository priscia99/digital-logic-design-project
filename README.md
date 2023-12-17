# Digital Logic Design Project [A.Y. 2020/2021]
This is the final project for the course **Reti Logiche (*Digital Logic Design*)** at Politecnico di Milano, A.Y. 2020/2021.

## 💡 Overview
This project aims to create a *network* of logic gates that implements a simplified version of the standard algorithm for the **histogram equalization** method of an image, by recalibrating the contrast of an image when the range of intensity values is very close together. This method redistributes the intensity values across the entire range of intensities, thereby enhancing the contrast.

The simplified version of the equalization algorithm is applied to images with a maximum size of **128x128 pixels** in grayscale with 256 levels (8 bits per pixel).

The network was created by using the software **Vivado** and **VHDL** language to define the digital circuit design and its behavior.

The performance of the digital circuit was evaluated by testing the entire system using different **benchmarks**:
- 2x2 image containing random pixel values in $[0,255]$
- Full-range images with random pixel values in $[0,255]$
- Empty images (0x0, 0x128, 128x0)
- Images with minimum (1x1) and maximum (128x128) sizes
- Black images (all pixels values are 255)
- White images (all pixels values are 0)

## 📚 Useful Links
- [Final Report](https://github.com/priscia99/digital-logic-design-project/blob/main/Report/relazione.pdf) (containing the algorithm, modules, components, datapath and experimental evaluation) 🇮🇹
