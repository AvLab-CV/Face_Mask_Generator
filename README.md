# Face_Mask_Generator

Overview:

Result:

Pre-requisites:
--
- Python3
- Opencv
- Pandas

How to use:
--
1. 下載github
2. 下載fan github，將圖片輸入至fan獲得68點landmark
3. In **/sample/** directory, we provide 3 images to test the mask generator.
4. In **/landmark/test.csv**, we provide the 68 landmarks and face types for 3 samples. 
5. To geneate the masks for samples, run the following commands:
```python make_mask.py.py ```

```bash
Definition of face types : 

Example : 0_1 
The first number "0" means the facial image is frontal and "1" means the facial image is profile.
The second number "0" means the facial image is clear and "1" means the facial image is blur.
```

Citation:
