# Savings_vs_Long_Term_Memory
Data for "A Double Dissociation between Savings and Long-Term Memory in Motor Learning"

These .mat files contain data collected for Experiments 1-4. Data for each experiment are in the form of a Matlab structure, with each field consisting of a [Num_trials x Num_participants] matrix.

The fields are:

**TN:** Trial Number

**VF:** Whether visual feedback was given during the trial (1: online visual feedback; 2: no visual feedback)

**Rotation:** The visuomotor rotation imposed on each trial (in degrees). CCW is positive, CW is negative. 

**Wait:** Whether, right before the trial, a wait time was imposed (1) or not (0). Trials immediately following breaks are indicated by (2).

**Instruction:** Whether an instruction was given for the trial (1) or not (0). Only present in Experiment 3. Note that Experiment 3 includes:

-> Two specific instruction trials during learning and and two during relearning, before and after the 1-minute wait ("Move your hand to the center of the target","Move your hand to the far end of the target")

-> Six random instruction trials before initial learning and six before relearning ("Move your hand to the left/right/near/far end of the target"), to familiarize participants with the instruction process

**ITI:** Time (in seconds) since the last trial (regardless of direction).

**theta_target:** Target direction (in degrees) relative to the 12 o'clock position. Only included for Experiment 4: target is always at 12 o'clock for Experiments 1-3.

**theta:** = reaching direction relative to theta_target, measured 150ms into the movement. Note that this is flipped based on the rotation sign so that adaptation towards the imposed visuomotor rotation is always positive.

**theta_end:** = reaching direction relative to theta_target, measured at the end of movement. Only included for Experiment 4: it is to be used for the no visual feedback blocks in Experiment 4.

Note for **Experiment 4**: the last two blocks (last 114 trials) were done on day 2.
