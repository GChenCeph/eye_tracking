# Eye Tracking Project

This project focuses on gaze estimation using fine-tuned and proxy-tuned models.

## Files

- `gaze_tracking.ipynb`: Jupyter notebook with the project code.
- `train_labels.csv`, `vali_labels.csv`, `test_labels.csv`: CSV files with the labels for training, validation, and testing.
- `ft_combined.pth`, `ft_combined_tl.csv`, `ft_combined_vl.csv`: Fine-tuned model files and losses.
- `pt_best.pth`, `pt_final.pth`, `pt_pt_tl.csv`, `pt_pt_vl.csv`: Proxy-tuned model files and losses.
- `ft_test_results.csv`, `pt_test_results.csv`: Test results for fine-tuned and proxy-tuned models.

## Dataset

The dataset used in this project is the Columbia Gaze Data Set. Due to the file size, it is not included in this repository. You can download it from the following link:

[Columbia Gaze Data Set](http://www.cs.columbia.edu/CAVE/databases/columbia_gaze/)

Once downloaded, place it in the appropriate directory and adjust the pathing in the notebook.
