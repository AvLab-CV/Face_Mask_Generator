# Face_Mask_Generator

Overview:
--
The code can add on a synthetic mask to each face in a dataset, offering an efficient solution to the lack of facial mask databases. This solution is helpful to the studies on face detection and recognition against facial masks.

Result:
--
<p align="left"><img width="95%" src="result/result.png" /></p>

Pre-requisites:
--
- Python3
- Opencv
- Pandas

How to use:
--
1. Clone the Repository to preserve Directory Structure.
2. In **/sample/** directory, we provide 3 images to test the mask generator.
3. In **/landmark/test.csv**, we provide the 68 landmarks and face types for 3 samples. 
4. To geneate the masks for samples, run the following commands:
```python make_mask.py.py ```


```bash
Definition of the face types : 

Example : 0_1 
The first number "0" means the facial image is frontal and "1" means the facial image is profile.
The second number "0" means the facial image is clear and "1" means the facial image is blur.
```

Citation:
