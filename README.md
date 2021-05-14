

# end-to-end Image augmenter

This is an end-to-end Image augmenter that inputs google search keyword you want and outputs augmented images as many as you want. First, download all dependencies by typing below command in the shell.

```shell
pip install -r requirements.txt
```

The program inputs four information:

* Image to crawl: Keyword you want to search on google
* Number of Images: Number of *original* images you want to crawl
* Image size wanted: Expected augmented Image size in pixel (width=height)
* How many augmentations per image?: Number of augmentations per *original* images

![terminal](C:\Users\82103\Desktop\Github\crawler\img\terminal.PNG)

After the program has been executed. two directories `augimg`  and  `img` directories will be created in C: drive.

* `augimg` : directory for augmented images
*  `img` : *original* images searched from google

```shell
C:
├── ...
├── augimg                    
│   ├── Ponyo             
│   |	 ├── 16920492723932.12536.png 
│   |	 └── ...
│   └── Kirby        
└── img         
│   ├── Ponyo             
│   |	 ├── 1.png 
│   |	 └── ...
│   └── Kirby                   
└── ...
```

**Original Image**

![original](C:\Users\82103\Desktop\Github\crawler\img\original.png)

**Examples of randomly augmented images with 224px fixed size**

![original](C:\Users\82103\Desktop\Github\crawler\img\aumented.png)



