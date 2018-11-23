# Chinese Herbs Dataset

![Examples of Main Categories in CNH-98 and their Corresponding Examples in TCNH-98. From left to right, the left examples in CNH-98 corresponds to the right in TCNH-98 from top to bottom.](./imgs/exhibition.png)

The Chinese-Herbs Dataset (CNH-98) is a collection of 9184 images of 98 classes, which can be divided into 8 categories including Fruits & Seeds, Rhizome, Flowers, Bark, Thallphyte, Whole Herbs, Leaves, Resin, whose examples (left) are shown in the above figure.  

The Tiny-Chinese-Herbs Dataset (TCNH-98) including 51198 images are cropped from CNH-98 dataset with the size of $32 \times 32$ and we ensure that there is no overlapping. From the exhibition in the above figure (right), we can see that although examples in TCNH-98 are just local parts, each example in TCNH-98 almost contains one herb with integrated shape at least, thanks to repeatability of examples in CNH-98.

Here we exhibit two sample datasets of 20 classes, [Chinese-Herbs-98_Sample](./Chinese-Herbs-98_Sample/) and [Tiny-Chinese-Herbs-98_Sample](./Tiny-Chinese-Herbs-98_Sample/), and the folder name is **label name** of class.

If you need the CNH-98 dataset for non-commercial use, please contact us.

## Distribution

The distribution of the number of Chinese herbs classes in the 8 categories (left) and images quantities between 98 classes (right) are shown : 

![](./imgs/pie&bar.png)

Main categories of CNH-98 dataset and their corresponding example name: 

| Main Categories | Herbs Examples                                               |
| --------------- | ------------------------------------------------------------ |
| Fruits & Seeds  | Star Anise, Siraitia Grosvenorii, Ginkgo, Chinese Wolfberry, SElfheal, Fructus Arctii, etc. |
| Rhizome         | Liquorice, Thorowax Root, Rhizoma Alismatis, Unibract Fritillary Bulb, etc. |
| Flowers         | Saffron, Flos Daturae, Cloves, Magnolia, Coltsfoot, Flos Jasmine, Lily, etc. |
| Bark            | Cinnamon, Cortex Moutan, Eucommia Ulmoides, etc.             |
| Thallophyte     | Glossy Ganoderma, Tremella, Cordyceps Sinensis, etc.         |
| Whole Herbs     | Abrus cantoniensis, Anoectochilus roxburghii, etc.           |
| Leaves          | Lophatherum Gracile, etc.                                    |
| Resin           | Frankincense, Myrrh, etc.                                    |

## Details of CNH-98

+ Source: Hospitals, Medicinal herbs stores,  [Google images](https://images.google.com/) and so on.
+ Quantities: 
  + 9184 images in total, 
  + 94 images on average for each class, 
  + 14 - 246 images per class
+ Classes: 98

## Details of TCNH-98

- Source: crops of the image in CNH-98
- Quantities: 
  - 51198 images in total, 
  - 522 images on average for each class, 
  - 100 - 1921 images per class
- Classes: 98
- Size: $32\times 32$