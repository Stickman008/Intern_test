# Intern_test

# dataset site
https://bop.felk.cvut.cz/datasets/

# dataset download
%wget http://ptak.felk.cvut.cz/6DB/public/bop_datasets/lm_train_pbr.zip

export SRC=http://ptak.felk.cvut.cz/6DB/public/bop_datasets
wget $SRC/lm_base.zip         # Base archive with dataset info, camera parameters, etc.
wget $SRC/lm_models.zip       # 3D object models.
wget $SRC/lm_test_all.zip     # All test images ("_bop19" for a subset used in the BOP Challenge 2019/2020).
wget $SRC/lm_train_pbr.zip    # PBR training images (rendered with BlenderProc4BOP).

unzip lm_base.zip             # Contains folder "lm".
unzip lm_models.zip -d lm     # Unpacks to "lm".
unzip lm_test_all.zip -d lm   # Unpacks to "lm".
unzip lm_train_pbr.zip -d lm  # Unpacks to "lm".

# note
https://github.com/ybkscht/EfficientPose
https://drive.google.com/drive/folders/1VcBLcIBhuT5MmXfE9NMrFdAk2xzF3mP5
https://arxiv.org/pdf/2011.04307.pdf

# other
