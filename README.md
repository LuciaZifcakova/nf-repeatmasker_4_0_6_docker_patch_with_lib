# nf-repeatmasker_4_0_6_docker_patch_with_lib

Download the reapetmasker https://www.repeatmasker.org/RepeatMasker/ version RepeatMasker-open-4-0-6.tar.gz and save it to folder X. This version has 2011 library of repetetive sequences.
Create .tar from the folder "Libraries" in folder X.
Build docker image using Dockerfile from this repo (copy it into folder X) in the folder X, so the software can find the .tar library file.
