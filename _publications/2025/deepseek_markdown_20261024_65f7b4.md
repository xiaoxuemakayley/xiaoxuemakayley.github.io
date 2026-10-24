---
title: "On the value of imbalance loss functions in enhancing deep learning-based vulnerability detection"
selected: true
pub: "Expert Systems with Applications (ESWA)"
pub_date: "2025"
abstract: >-
  To address the bias in previous studies regarding class imbalance in deep learning-based vulnerability detection (DLVD), this paper comprehensively evaluates nine imbalance loss functions alongside standard cross-entropy loss. By testing on two DLVD models across four public datasets using the Scott-Knott ESD test, we provide key insights and recommendations, finding that LDAM achieves the highest Precision, LA loss yields the best Recall, and CB-Focal loss excels on extremely imbalanced datasets.
authors:
  - <b>Xiaoxue Ma</b>
  - Yanzhong He
  - Jacky Keung
  - Cheng Tan
  - Chuanxiang Ma
  - Wenhua Hu
  - Fuyang Li
links:
  Paper: "https://pdf.sciencedirectassets.com/271506/1-s2.0-S0957417425X00233/1-s2.0-S0957417425021232/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjENv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJHMEUCIQCe4WP%2FNrCO6YFPy2sBnG0dZySVlex17e7o1iZqhzpykAIgL9NsRG5aG7NBUHXyYTWk2wlfaCboqyx0HUkQ2e%2F0WQEqvAUIpP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAFGgwwNTkwMDM1NDY4NjUiDI6XhFbgEXaz1BIGwCqQBVFBP4n%2BAInt%2F6G%2FbsyMQBxDebLxPgiIgDR8Ob7FVu7HN%2B5HDOwOju7ixYXBeuGBBofS8Ay728skbnv%2FhXViK2QFMZNPKPoLNs0GHOZedLRe7PMjR3PtmSkSFb4RFGUyKq1%2BPhoBrAjj0EuuSVx0dZk15MW8t6cnseVFLUEZ2c9ppqU0eqdW0STBdDSaFJ%2FkX7M69uS03NleTwKc6lbxLjcOx%2FdOl4%2BZxk6uGqPPKtC7lP47iws5HkIfLU%2FknginmNAmj%2FTRlHZ8lL5r5hrnDBqmm418r0gtC5VCmBfgQBxGXJ7zXsZAuKJ630lEoc%2BUJCDx0GkvA6BGxqhatLmummDsC%2FUH8Z9VFOToroZ15fRPGjEZcT7qTAVP%2FA0halUAWzMFT4VapvyGqowcLlh%2FEue6AgkK%2B9nug4bQzaIQYO%2FcPdFKFfOFoGSpvESbSf84%2BW8EKoBPftFzXiHONlnT7Z1QwK85scje5oMwXL2D%2F63PjRwn9x3yTTztxhO1MmW%2FYLypmE2xhw0wFcgGs%2FC3YifLUEiOUwtYJ%2BrxLk1Z9lS0sLJDbs27q4SyPeH1fI4TPlE2Q7exHfxQRHqaF4E5AV10mZxx%2B8b4rAMmfjQ5NhJ1uKUnTmTANHpYb9fvdRatJ962sGfb4uTFuWSL2I1RlSvDSw9Js9%2FB04I%2B5mfzdUJ6Wbm%2BqPHdnvspjqe68jI2yTWpk27GA3RijtAIvVEsYpI0Yb5Bp%2F%2FwVnfGUjrx0hDVHzzdl4%2BWJmLbffq9YoAA43Ux2qEaOjwf%2FBKhjK8bypBwlm3w35X7iosoan2qMVlN%2B9io9g6S1ZPxoodMG2i%2F9iK%2F3bDiIx1tauHBpFbn5%2B8DO0iy8Dp%2BP%2BYxTb0rbsggMIuQ8tYGOrEBcl5EyfeM3Fi6bVYKW6s9%2BH98jja%2Fjzn4q9HgldoQZgplE8w8WC1WAsQ%2BS%2BGmNEA46kOzABj5FYrHG18qxYTBEleLEooiB0nGz3%2Fkt%2Ft5WTlVWGEkialQoQvMiFq7%2FjGBnHWQpCbBcKTyDTTHDMv4xjUlSkUUHnjYgjW%2B5koCOWJy49mSz0hZH%2Fr1TfPLjRzjoFqh7Gn1daAgKAO5cSXwl0c%2F951qRSFtXtk2qwartVJy&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20261024T111601Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY7VHEIXBV%2F20261024%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=2797e96c3aba68b83eef6e42ff4a440efa32b438b2b2901c03ab6e320aee0d40&hash=bde170f4ae13e8a05cc578d9f0dfe77c6977b2be5f97fbcdef9051196f3f1f5c&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0957417425021232&tid=spdf-7888ca20-842c-4ba6-804a-02bc0718ddf2&sid=a605a93a2363754848484443167250eadaedgxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&rh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=120d0352065a5b56535b00&rr=a4f89124e9c11483&cc=hk&kca=eyJrZXkiOiI0MmRSN3hLa09qajhGK1Y5WktVMTJmNnc0akJtbnpCLzhHZ3ZieTYra2lBZDI1NUhja0FHQjU1QTR6WUJIbzdXVFJINTFVOHI3KzVXdEpMVi9OVkVmZXVJblEzdmMxMHF0dFFIcXdIWkd5bDBVRnVWSjU1RnRFWkJYU0t4dGptMVNMNGcyQjY5OWQxcG5mT3lRZ3grbzJ3UHVTbjkwRXpTeGFTdjZIMEIvdk5RRDVQQSIsIml2IjoiZWVkMjgyOGZiNzdiZTJlYWNiZmFkNzBkYTY2Nzc0OTUifQ==_1792840565543"
---
