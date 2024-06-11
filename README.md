I defined submerged vegetation as two types: 1. Upright; 2. Benthic (I saw that they are divided into tall and short)


Code include 
1. read UAV RGB
2. save numpy to TIFF
3. RGB to HSV (HSV calculations may be more efficient than RGB)
4. map abundance by NFINDR, NNLS and RGB
5. map abundance by NFINDR, NNLS and HSV
6. map abundance by manually determine clean pixels,NNLS and RGB
7. map abundance by manually determine clean pixels,NNLS and HSV
8. fcls
9. flcs and GMM

![image](https://github.com/xinnix73/abundance-of-submerged-vegetation-by-UAV-RGB-images/assets/70842125/3dbf33b0-cfaf-4b1c-9af0-2ee9f43eb7a9)
UAV
![image](https://github.com/xinnix73/abundance-of-submerged-vegetation-by-UAV-RGB-images/assets/70842125/076a785a-3689-4d51-b0ca-40e9f953faad)
abundance Upright by flcs and GMM
![image](https://github.com/xinnix73/abundance-of-submerged-vegetation-by-UAV-RGB-images/assets/70842125/7731092b-b8ef-43d7-9227-6c1c0b56f98f)
abundance Benthic by flcs and GMM



