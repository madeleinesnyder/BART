Shared project with Shreyas 
7.31.18
BART data
SCSNL lab

General Goal: Produce T maps (spm maps) for History Effect
8/2/18

Scripts (for MR analysis):

Task Design Generation (making the .m file FOR EACH SUBJECT that contains the onsets, durations, and pumps for each task condition)
/oak/stanford/groups/menon/projects/skbharad/scripts/tdfunctions/taskdesign_generation*

Contrast Generation (making the .mat file FOR A GROUP OF SUBJECTS that contains the task conditions to be contrasted when examining fMRI data)
/oak/stanford/groups/menon/projects/skbharad/scripts/cgfunctions/*

Individual Stats (doing the actual T tests to determine if the tasks specified in the task design and contrast mat files have significantly different activity)
/oak/stanford/groups/menon/projects/skbharad/scripts/individualstats/*

Group Stats (doing the group averaging to make the final spmT nii gz file to examine with fslview)
/oak/stanford/groups/menon/projects/skbharad/scripts/groupstats/

Scripts (for behavioral analysis):

Behavioral (HACRT.csv generating scripts)
/oak/stanford/groups/menon/projects/skbharad/scripts/behavioral/

USING FSLVIEW
to load the fsl module (use Sherlock software)
  ml biology fsl
to launch fslview
  fslview_deprecated 


 
Contrasts: wins preceded by explosions v.s. wins preceded by cashouts
           losses preceded by explosions v.s. losses preceded by cashouts
Put paths, and commands, and confluence page 

PATHS


