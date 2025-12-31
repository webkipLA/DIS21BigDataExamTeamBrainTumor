Leon:
### Intial Exploration of the Data (Taking a look at the different images with my own eyes looking for patterns or characteristics):
The Pictures are from many Different Perspectives, a meningioma is always a differently lighter colored mass, sizes vary from very small barly noticeable to very large
In Preprocessing we could label our images with the type of Image such as sideprofil, topdown, crossection, behind, etc (Cluster analysis?)
Researching the Different types of Tumors we have and their characteristics aswell as how they appear in our training Data, Pituitary Tumor(Typically small, at the base of the brain), Meningioma Tumor( well-defined, solid mass, attached to the brains outer lining), glioma(les well defined mass often lacking clear borders(spread diffusely in the brain), shows up as darker or lighter in our Training Data)
Certain Brain TUmors apparently Originate from Certain places in the brain such as the Glioma being assumed to orriginate from the subventricular zone until recent studies

### Glioma
"When viewed with MRI, glioblastomas often appear as ring-enhancing lesions. The appearance is not specific, however, as other lesions such as abscess, metastasis, tumefactive multiple sclerosis, and other entities may have a similar appearance.[61] Definitive diagnosis of a suspected GBM on CT or MRI requires a stereotactic biopsy or a craniotomy with tumor resection and pathologic confirmation. Because the tumor grade is based upon the most malignant portion of the tumor, biopsy or subtotal tumor resection can result in undergrading of the lesion. Imaging of tumor blood flow using perfusion MRI and measuring tumor metabolite concentration with MR spectroscopy may add diagnostic value to standard MRI in select cases by showing increased relative cerebral blood volume and increased choline peak, respectively, but pathology remains the gold standard for diagnosis and molecular characterization.[citation needed]"


### Different Types of MRI Brain Scans
![alt text](Images\image.png)
![alt text](Images\image-1.png)
![alt text](Images\image-2.png)
![alt text](Images\image-3.png)
source https://www.adveva.co.uk/en/clinical-corner/different-types-of-mri.html#:~:text=The%20image%20on%20the%20left,if%20a%20treatment%20is%20working.
https://www.youtube.com/watch?v=6Hlx6Fe_vBc
a/b versions of coronal sagital and axial


### Considerations Data Preprocessing 
1. We have way more images or training Data for Gliomas 826, meningioma822 and pituitary 827, than no Tumor 395 so our model might be biased towards recognising a tumor where there is none
2. Image Size Shape and format: Landscape vs upright 


### Researh (supported by LLM's)