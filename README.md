## Learning Modal-Invariant and Temporal-Memory for Video-based Visible-Infrared Person Re-Identification

### Usage
- This project is based on DDAG[1] ([paper](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123620222.pdf) and [official code](https://github.com/mangye16/DDAG)).

- Usage of this code is free for research purposes only. 

- First, the training and testing code and part of the testing data are announced. We promise that the complete datasets will be released after the paper is accepted.

- Testing.  
	1. Preparing the dataset[Google Drive](https://drive.google.com/drive/folders/1luubCWowzvq6hpAbt9BKHrlC0AXXxQ1m?usp=sharing). The path to the data is placed in ```data_manager.py```.  
	
		```
		|____ data/
		     |____ 0572/
		          |____ ir/
		          |____ rgb/
		     |____ 0573/
		     …
		     |____ 0584/
		     |____test_name2.txt/
		     |____track_test_info2.txt/
		     |____query_IDX2.txt/
		     |____train_name1.txt/
		     |____track_train_info1.txt/
		```  
	2. Downloading the parameter files trained in this paper.[Google Drive](https://drive.google.com/drive/folders/1luubCWowzvq6hpAbt9BKHrlC0AXXxQ1m?usp=sharing).  
	3. To begin testing.(See the code for more details).  
		```
		python test.py
		```

- Reference
	```
	[1]Ye M, Shen J, J. Crandall D, et al. Dynamic dual-attentive aggregation learning for visible-infrared person re-identification[C]//Computer Vision–ECCV 2020: 16th European Conference, Glasgow, UK, August 23–28, 2020, Proceedings, Part XVII 16. Springer International Publishing, 2020: 229-247.
	```
