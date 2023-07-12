icr-identify-age-related-conditions
===================================

The [competition](https://www.kaggle.com/competitions/icr-identify-age-related-conditions/overview) for age identification of age related condition.

[Company](https://invitrocellresearch.com/our-research) sponsored.

Files:
```
╰─➤  kaggle c files icr-identify-age-related-conditions
name                    size  creationDate         
---------------------  -----  -------------------  
sample_submission.csv   124B  2023-05-05 19:37:38  
train.csv              329KB  2023-05-05 19:37:38  
test.csv                 1KB  2023-05-05 19:37:38  
greeks.csv              18KB  2023-05-05 19:37:38 
```

# Working with submission

The submission requires notebook submission. This should work:
```
 kaggle competitions submit -c icr-identify-age-related-conditions -f icr_submission_290623.ipynb -m "second submission"                                                        2 ↵
100%|██████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████| 58.7k/58.7k [00:00<00:00, 81.6kB/s]
400 - Bad Request
```

# Exploring notebooks

> Ensure the kaggle is installed in your python
```bash
╰─➤  . ~/workspace_kaggle/venv/vKaggle-3.11.3/bin/activate
```
pull notebook with: `kaggle kernels pull <username>/<notebook-slug>`<br>
Navigate to directory to pull, usual with 3rd party notebooks, copy the username and slug form notebook url and download:
```bash
(vKaggle-3.11.3) ╭─t@NumericalCatalyst ~/workspace_kaggle/compete-icr-ident-age-rel-cond  ‹main*› 
╰─➤  cd 3rd-party-notebooks 
(vKaggle-3.11.3) ╭─t@NumericalCatalyst ~/workspace_kaggle/compete-icr-ident-age-rel-cond/3rd-party-notebooks  ‹main*› 
╰─➤  kaggle kernels pull ulrich07/tabfpn-xgb-oversampling-cv-0-18-lb-0-16
Source code downloaded to /home/t/workspace_kaggle/compete-icr-ident-age-rel-cond/3rd-party-notebooks/tabfpn-xgb-oversampling-cv-0-18-lb-0-16.ipynb
```
