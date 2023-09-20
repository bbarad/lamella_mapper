# lamella_mapper
Map tomograms back to their lamella position

Inspired by [Anton, Cheng, Haile et al _Biorxiv_ 2023](https://www.biorxiv.org/content/10.1101/2023.09.03.556115v1.full.pdf) Figure 6. Automatically generate similar figures from a folder of PNGs or MRCs and a PACEtomo tgts.txt file. 

### Requirements
* Python 3
* Matplotlib
* Pillow

### Example usage:
```
python lamella_mapper.py --pace=TOPFOLDER/pace/L3_tgts.txt --pngfolder=TOPFOLDER/img/L3/ --rotation=90 --flipy=false
```
