# CUTRUN
## Usage
```
# download picard.jar, samtools, and Trimmomatic
bash download.sh
# download the mm10 index files
bash download_index.sh
# build the apptainer which contains rest of necessary packages
# change `~/docker/src` in `build.sh` to the `src` directory created by the above scripts
bash build.sh
```
# cutrun.sh is the script to run last and with create the .bw file
