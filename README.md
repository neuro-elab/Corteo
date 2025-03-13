# Corteo: a Novel Software for Integrated Multimodal Brain Network Analysis


https://github.com/user-attachments/assets/8438037c-36fe-4c93-ad68-fa7c41b6f793


## Demo data
Available here: https://filesender.switch.ch/filesender2/?s=download&token=cd15d664-1372-4f93-81b8-b0413899b01c


## Folder structure
    [MySubjectDirectory]

    |- Electrodes     <-- mandatory
    
      |- Lookup.xlsx  <-- needed for electrodes imaging + traces
    
    |- Imagery        <-- needed for imaging module
    
      |- Raw
    
        |- anat_t1.nii
    
        |- postop_ct.nii
    
      |- NativeRegistration
      
        |- anat_t1.nii    <-- needed for native imaging. can be obtained with Corteo pipeline from Raw/anat_t1.nii
      
        |- postop_ct.nii  <-- needed for native CT imaging. can be obtained with Corteo pipeline from Raw/postop_ct.nii
      
      |- Parcellation  <-- needed for 3D imaging + needed for contact labelisation
      
        |- ... _folders_and_files_from_freesurfer_ ... 
      
      |- MNINormalization
      
        |- anat_t1.nii    <-- needed for average imaging. can be obtained with Corteo pipeline from NativeRegistration/anat_t1.nii

First, load a subject -> this is the directory [MySubjectDirectory].

For electrophy data, select a .h5 file that can be located wherever you want on your computer/external hard drives

    
## License & Usage Restrictions
This software is currently under development and is made available only for collaborators of e-Lab, University Hospital of Bern or CCN lab, University of Bern (Bern, Switzerland). 
It is not open-source and cannot be used, copied, modified, or distributed without explicit written consent from Prof. Dr. Maxime Baud at Inselspital, University Hospital of Bern, CH or Prof. Athina Tzovara, University of Bern, CH.

If you are interested in using this software, please contact us at camille.mignardot.inselspital[at]gmail.com. 
Unauthorized use or distribution is strictly prohibited.
