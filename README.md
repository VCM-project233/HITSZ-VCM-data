## Learning Modal-Invariant and Temporal-Memory for Video-based Visible-Infrared Person Re-Identification

### This is the page for HITSZ-VCM dataset. 
### HITSZ-VCM is a large scale video-based cross-modal dataset for person re-identification.

#### Usage

- Download the [Train data](https://drive.google.com/file/d/16codXQuXcgOLtr2ADLzCRMu2FI5zKmSG/view?usp=sharing), [Test data](https://drive.google.com/file/d/1UGot89JorJif3MY5o2o9gnM50KudIeTX/view?usp=sharing) and [info](https://drive.google.com/file/d/1BApfA5k995wcjW9Ok6Xl6QOY03IOWG05/view?usp=sharing) from Google Drive or from [Baidu Netdisk](https://pan.baidu.com/s/1oFYQIJoxCCD1Wk9WTbhbxA) (password: kxzs).


- Unzip the data and put the data in the same directory. The path to the data is placed in ```data_manager.py```.

- Data structure.
            
	    
		|____ data/
		     |____ 0001/
		          |____ ir/
		          |____ rgb/
		     |____ 0002/
		     …
		     |____ 0927/
		     |____test_name.txt
		     |____track_test_info.txt
		     |____query_IDX.txt
		     |____train_name.txt
		     |____track_train_info.txt
		 

#### License 
- Data is available for academic only. This means that it cannot be used to train models for commercial use.
- You may NOT redistribute the dataset. This includes posting it on a website or sending it to others.
- Models trained using our data may only be distributed (posted on the internet or given to others) under the condition that the model can only be used for non-commercial uses.
- Any publications utilizing this dataset should reference our paper.

##### By downloading or using any of these files, you agree to be bound by and comply with the license agreement.

```
@inproceedings{lin2022learning,
  title={Learning Modal-Invariant and Temporal-Memory for Video-Based Visible-Infrared Person Re-Identification},
  author={Lin, Xinyu and Li, Jinxing and Ma, Zeyu and Li, Huafeng and Li, Shuang and Xu, Kaixiong and Lu, Guangming and Zhang, David},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={20973--20982},
  year={2022}
}
```
