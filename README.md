# Checking Coregistration
- Protocol Developed by Tyler Hein
- Webpage Developed by Andie Bulbin

1. Open MATLAB on computer with the brain images
2. Enter into MATLAB command window
- $ addpath(genpath(‘PATH TO SPM12’))
- $ cd /PATH FOR IMAGING DATA DIRECTORY
- $ spm fmri
3. Click the "Check Reg" button on the green window that pops up

![Image](checkreg.png)

4. Click on the desired participant
5. Click "anatomy" then "t1spgr_110sl" then "eht1spgr_110.nii,1"
6. Click the ".." on the left side of the window to return until seeing "func", then click that. Next click "faces", then "run_01", then "rtrun_or.nii,1"
7. Click "done"
8. Click around the periphery of the top right brain image that pops up, watching to see if each click aligns with the periphery of the bottom right image.

### Examples

![Image](example1.png)
![Image](example2.png)
![Image](example3.png)

9. Open excel recording spreadsheet to enter the results of each participant's coregistration
10. To start a new participant, exit out of the window with the brain images, click "Check Reg" again, and repeat the same steps
