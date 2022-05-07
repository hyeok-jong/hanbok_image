# Hanbok image crawling and segmentation for style transfer

## 1. Crawling  
[google-image-download](https://github.com/hyeok-jong/google_image_crawling)

## 2. clothes segmenation  
[U2Net Clothes segmentation](https://github.com/hyeok-jong/u2net_clothes)

But doing this is not enough.  

## 3. Human Segmenation  

Different from before clothes segmentation, no cuda memory erorr.  
So I commented out line 17 ~ which deletes big size images, in custom_delete.py  
But, somehow there could be problem with memory so I added `print(raw_image_np.shape, pred_np.shape)` line 51 in `custom_u2net_human_seg_test.py`

for some crawled images 

## 4. Face Segmentation 



