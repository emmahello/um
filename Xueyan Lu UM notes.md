# current plan
/// PAEZ, VIONNETTE:
BH, ETHOS, every other day, 

# print
UH-43D81V3 main
UH-2KVMYS3 west
\\Client\C$\XL
\\cgcent.miami.edu\DEPTSHARE\SCCC_Radonc\PUBLIC\PT_Setup_pictures_West\2025\2-13-25
\\Client\W$\PUBLIC\PT_Setup_pictures_West\2025\2-5-25
\\Client\W$\PUBLIC\PT_Setup_Pictures_Doral\12-26-24
\\Client\W$\PUBLIC\PT_Setup_pictures\2024 MAIN pictures\2024-10-31
\\Client\W$\PUBLIC\PT_Setup_pictures_Lennar\2024\2024-11-20
W:\ECLIPSE PLANS\XL
W:\PUBLIC\ArcCheck\2024 Patients QA\NIEVES, MARIA
\\Client\W$\ECLIPSE PLANS\XL
\\cgcent.miami.edu\DEPTSHARE\SCCC_Radonc\ECLIPSE PLANS\Ethos Adaptive\Shoemaker, Sheryl_IM105\Shoemaker, Sheryl_IM105
\\client\C$\XL
mount to W drive: This PC - Map network drive - \\cgcent.miami.edu\deptshare\sccc_radonc
V95%>=95%
V105.0%<=10.0%
Dmax<=150%
Dmin>=90.0%
V100%>=95%
Ursula Hennings
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Prostate_012425 MRI
pending
Scan Series
UM PACS
T2, ADC, Early and Late DCE


Breast
V95%>=95%
Dmax<=107%
V105.0%<=10.0%

Breast_Boost
V100%>=95%
Dmax<=110%

Breastboard 10 Deg. 
hands holding D-F. 
Head #3 
#5 under legs. 
**Chin Up.

KV: pre Tx
CBCT: pre Tx and every Tx
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
@@@@@@@@@@@@@@sending to MD:
Reference points
Dose rate
ClearCheck
F4
@@@@@@@@@@@@@@sending to Physicist:
ClearCheck report / RadCalc report
F4
Check the physician's order, if EQD2, send plans to MIM for physics and drop a task.
setup pictures

@@@@@@@@@@@@@@@@@@@@ ethos export时1、new pt foler 2.忘记选择路径 
@@@@@@@@@@@@@@@@@@@@ ethos: add setup notes and pictures
@@@@@@@@@@@@@@@@@@@@ Delta couch shift
@@@@@@@@@@@@@@@@@@@@ Reference point for lower PTVs
@@@@@@@@@@@@@@@@@@@@ Fill in RC point when printing
@@@@@@@@@@@@@@@@@@@@ Double check Dose rate. 
@@@@@@@@@@@@@@@@@@@@ Check physician's order: : Special physics consult needed. If checked then drop 'Special physics'
			While importing: Check the physician's order，if need a deformable fusion, then drop a special physics activity (Physics Consult Needed???) and paste the note;
			While printing: Check the physician's order, if need a EQD2 dose summation, then drop a special physics activity and paste the note。
***If the physician's order checks special physics consult, then drop a special physics activity. Physics will take care of it. I believe most of SBRT-EQD2 are these type of cases.
... Otherwise, if two lesions may overlap or be very close, then fuse two images, insert a plan sum, and ask MD whether need a special physics consult. May need to print a clearcheck report for physicists.

@@@@@@@@@@@@@@@@@@@@ check Rx
@@@@@@@@@@@@@@@@@@@@ If PTV overlap w previous Tx, fusion and insert a plan sum, and generate a plan sum report. May need to change OAR dose limits according to QUANTEC or ask physicists.

C1_Stomach
C1_PD
PTV3000_Stomach
greenshot: change the shortcut of 'Capture region' to Prt Sc; Setting - Destination - check 'Open in image editor' and 'Copy to clipboard'
QGenda
	MD: https://app.qgenda.com/Link/view?linkKey=84ae4a74-d1f6-4d68-9c20-94944b260e72
	Physicists: https://app.qgenda.com/Link/view?linkKey=2a3f600a-7240-4f64-ba87-4387486c6e61
Schedule: as long as there is one dsmt covering untill 5 pm

# case examples
CSI photon: BOODOO, SUNITE 22599251; CABREJA, PEDRO 24013835
HN w boost: RIOS MORA, LUIS 23922917
SRS: DE OLIVEIRA MARCIERI, BEATRIZ 23471221
HN with jaw half open: GONZALEZ, MANUEL 10139847
Different isocenter for different field and SSD setup, 3D, large volume in Edge: TEAGUE, LEIDY 24019827
Breast w electron boost:  PORTER, NELLIE 9253435
Prostate w LN 86/80/56: MANSO, JOSE 8587020
Prostate w LN 86/80/72/68/56 in Edge w two isocenters, using autocrop : BORDON FUNDORA, ROBERTO 20254084

# meeting 
Proton: Jonathan, Boris, Hayden
West/Ethos: Rene, John B, Lu
Main: William, Karen, Katherine, Ricky
Lennar: Pablo, Zach
DFB: Mike and Andrew
WEST inpatient stay at west if < 10 fractions (for replan cases)
Plantation 2 dosimetrists April 14 2025
Sole Mia 3 dosimetrists June 17 2025


# MD
Dr. Mellon: very thorough, communicate well, love SBRT. MIM only.
Dr. Portlance: could be many mistakes due to many residents. Ask other dosimetrists if you found mistakes, better not ask MD at first
Dr. Azzam: very nice, respond to text quickly
Dr. Mahal: MIM only.
Dr. Allon Pollack: William only is allowed to plan his patients.
Most MD loves eclipse, not MIM.
Jessica: chief therapist in West
Cathy: chief therapist in Miami
Dr. Iscow doesn't put dose limits, he prefers ALARA
Dr. Takita prefers good PTV conformility, eg. tight 100% IDL. Doesn't like a 3D beam perpendicular to lungs or heart.
Dr. Reveda prefers high coverage as long as OAR is fine.
Dr. Yechieli: when you plan Dr. Yechieli, you are the Doctor.
Dr. Spieler perfers 50%IDL irradiates bladder ALARA, 33%IDL irradiates rectum ALARA. Carina is best for upper and mid lung cases.


# Device
Main Linac A - Triology: Exact Couch with flat panel, rails out; 	6x, 23x;		max FOV is 40 cm
Main Linac B: IGRT, medium (thick for pelvic), 		6x, 10x, 23x		
	Main Imaging Device CT49408
West Edge: IGRT, thick??,		6x, 10x			max FOV is 22 cm
	for IMRT: field X have limit < 15 cm since MLC can't move that fast
	for 3D: field Y have limit < 22 cm but field X doesn't have any limitation
West Ethos: halcyon, 			6xFFF			max FOV is 38 cm		couch shift limits (from user origin to isocenter): 17 cm table out, 30 cm table in
	West Imaging Device **5674, 5674_pHN
	no extended SSD, only SAD setup
Lennar Linac A: IGRT, medium, 		6x, 10x, 23x 
Lennar Linac B: IGRT, medium, 		6x, 10x, 23x
Doral LinacA: IGRT, medium,	
	Doral Imaging Device **255
surface guided imaging device
	West: identify
		SRS: new structure named BODY_IDENTIFY = BODY (crop wire out) + NS_WIRE
		non-SRS DIBH: BODY_FB
	Main: osms


--------Doral---------
Therapist Martinez, Rene phone: 20150
Since the simulation CT machine has more bits (16 bits) than other CT machines (12 bits), HU could overflow in electron density curve. If got an error during calculation, then in Contouring, 
... click 'Segment High Density Artifacts', it will recognize all areas whose HU is larger than 3388, you reassign HU as 3093 or a type of material, such as Titanium (HU=8000), and steel (HU=13000?).
4DCT in Doral don't combine as a scan named 'CTSim 0% - 90%' with 2000 slices, in converse, it separates into 12?? CT scans, such as CTSim 0%, CTSim 10%,.... You choose a phase (such as 50%) to fuse PET to it.
Identify
	Some of the server are not talking to our Identify server. You can check you citrix connection center, UH01VARNCTXP01-05 usually works. Others usually doesn’t. This is not because of any connection issue, but just these servers need to reboot.

-----ethos------
use KVCBCT setup fields only, no other setup fields
no C1_PD course, ethos print will include QA parts
3D Ezfluence cases only: rc MLC - Remove Flattening Sequence, to make the beam as regular FFF curve shape PDD, otherwise it will be flat beams. It applies only 3D+Ezfluence+ethos cases.
move isocenter to avoid couch collision, give a 1 cm at least margin off the couch (from the red circle)
Y axis should <= +-6cm ???
Couch shift limitation
	•	For Halcyon, move the user origin closer to the treatment isocenter in the Treatment Planning System to reduce the Delta Couch Shift longitudinal value so that the Load button becomes available
	•	The planned longitudinal Delta Couch Shift cannot exceed: 
		o	-17.00cm (moves the couch away from the bore)
		o	OR
		o	+30.00cm (moves the couch further into bore) 
		o	These limits are documented in the Halcyon and Ethos Radiotherapy System Customer Release Note
	•	For Ethos, move the Simulation Isocenter in the Technical Structures to be within 17cm of the planned isocenter
	example:
		one lesion in superior: Y=-5cm; the other lesion in inferior: Y=-52cm. User origin: Y=-10cm
		Create a new structure named Virtual_Iso_shift: put is at Y=22cm, use brush (2 cm thick, check 3D) to contour one dot in one slice.
		Setup notes: use virtual_iso_shift as a user origin
		Ethos report: create an OAR structure virtual_iso_shift and link it.
		Simulation Isocenter - Edit - click square-arrow - choose virtual_iso_shift - Confirm

# English
There's no DICOM that we are aware of. We don't have acess to EPIC DICOM.
I apologize for using the wrong pronoun. I did not mean any disrespect.
Hi Dr. Takita, Xueyan Lu from dosimetry. WOuld you please re-approve the plan for GLORIA VELASQUEZ. 
Would you re-approve the plan? I'm sorry I didn't put a proper tracking point for QA. The plan is the same.
I see you in and out.
It (new Tx) starts at 2 pm. I just make sure you got my email.
give me an estimate??? I can talk to him
Please disregard last email.
In Annia’s absence I will be handling this case. 
This request is very time sensitive.
There are two plans ready for review. However, if you prefer to evaluate the sum prior to approval I have sent both plans to MIM so physics can generate a plan sum. I already dropped a task for them and cc'd them on this email.
From what I can see, Hayden and James are working on this patient. Adding them to the thread so they can provide updates.
The family is doing their effort on their side to expedite the process
Ask MD: The prostate is pushed up to the bladder. ... Is there any reason for that?
The second plan for one more fx retreat is 'L CW retreatment' since the patient is still in pain. 800cGy/fx * 1 fx = 800cGy.
This is Lu. I'm calling from University of Miami to request records for a patient that will be treated here. We have the physician-to-physician request form. 
...Can you please let me know what the process is? Dr. Ramon F. Arguelles.The patient's name is Llanes Capote, Isabel (24055275). Last name is Capote. DOB 11/5/1951
.. from Palmetto General? She got Radiation to the left upper lung in 2020. 
...Provider to Provider Release of Information for Treatment Purposes
...medical release form with the patient's signature
I faxed two documents to you yesterday. Did you receive my fax?
This is Lu. I'm calling from University of Miami to request records for a patient that will be treated here. I faxed two request forms on last Monday. Is there any update from the physics team? 
..Just double check the physics team is too busy to email me or they email to a wrong address
FRANCIS.SIMAC@USA.GENESISCARE.COM
Good morning Dr. Freret,
I hope you're doing well. I was wondering when you were planning to start this patient. I know you said you were going to request another MRI. I just wanted to know because I'm going to be off most of next week and I don't want anything to fall through the cracks. Please let me know. 
I've just sent you an invite via Box with the DICOM records requested. Let me know if you have any issues or if anything else is needed. Thanks!
If they tell you that the form is enough, then ask for the fax number. If not, just follow what they tell you to do. 
Per Dr. Taswell, I was advised to re-simulate the patient to get replanned. 
"Two cents" is an idiom that means to share an opinion, even if it's not asked for or considered important. eg: "If I may put my two cents in, that hat doesn't do you any favors". 



# Plan
## w Boost
Ethos:
Add two phases when print the initial plan:
	Total				Phase 1				Phase 2
	PTV4005_Breast_R 4005cGy 	4005cGy = 267 * 15
	PTV5005_Boost_R 1000cGy						1000cGy = 200 * 5
**If forgot to add two phases for the initial plan, now you are printing the boost plan, you will get an error when authorizing the plan. Now you need Create Revision:
	Click the pt information - delete the boost RT Intent - click the initial RT Intent - edit Phases - choose 'Apply changes after the last fraction' - Create Revision

Reference Point (MRN: 23925817):
	PTV4005 Total 4005, Daily 267, Session 267 --> in init plans only
	PTV5005 Total 1000, Daily 200, Session 200--> in boost plans only
	We don't need Total_Dose

ClearCheck & Aria report:
Breast R: PTV_4005 (95%-95%, max<107%, V105%<10%), OAR
Sum: PTV_4005's coverage only (95%-95%), PTV_5005's coverage (95%-95%), PTV_5005's max dose (max<107%, V105%<10%), OAR. Uncheck 'Breast_R' and 'Brst R Boost'. 
	... Karen said "Don't need to print Boost plan seperatively", but Physicists want to Boost plan reports, so just print it!
Make Plan Structure and Plan Check for Breast_R and Sum plans.

Care path:
	Drag 'SCCC West - Boost' to anywhere - Edit - change the 'Due Date' to the first Friday after the new Tx of the initial plan and before the boost Tx
	... - add Note for 'Review Approve B...': Boost to be approved
	... - add Note for 'Print Boost': 111524 Xueyan Lu REVIEW Boost ETHOS

MRN: KATSMAN, SVETLANA 23925817
ClearCheck template:
	Init: PTV4005, Lung L, Heart
	Boost: PTV5005
	Sum: Lung L, Heart
Plan Sum report
	Plan: Plan Sum
	Constraint Template: Breast L and Breast Boost
## electron
Plan
	rename the field name as 1B_Enface
	click Field - new Block - Material code: e-cutout, check Aperture, uncheck Diverging Cut, Tray ID: CustomFFDA (choose CustomFFDA6 if A06)
	rc Block - Fit to structure - If no PTV: use 1.5 - 2 cm margin from wires, 3.8cm width of aperture in total; if PTV, use 1 cm margin.
	Dose: check MD Tx Note in Documents, such as 600cGy * 3 = 1800cGy
		Treatment Percentage [100%]: 100, Plan Normalization Value: 90%
	Only one Reference Points, no RC point
	SSD: 105cm
	Calculation Models - View - Smoothing method: change from no-smooth to 3-D_Gaussian. The IDL looks zigzag if no-smooth.
	Boost plan
		if electron: norm to 95%-95% or go higher, such as 97%-96.5% as long as the max is lower than 115%. change Rx as well;
			the inferior depth of PTV is less than 5 cm, then electron is feasible.
		else if photon: norm to 100%-95%
	IpsiLung dose limit: V2000cGy < 15% (<10% is ideal).
Rx
	Prescribe to IsodoseLine 90%, Total Dose: 1800cGy, Dose Fx 600cGy
	Technique: Enface
	Bolus: 0.5 cm, Every Treatment
	No imaging
max dose around 115%
RadCalc: diff < 10%
	Prescriptions: Enter Isodose Line: 90%
	Cutout Factor Method: Sector Intergration
	cUTOUT sHAPE: Custom
	Use Bolus: Yes 0.5
	
Carepath
	Drop SCCC West - New Start 3D
	Add a new task  (not drop on any item) - Activity Category: Therapist Tasks, Activity: Cut Out， Owner: Jones, Karl
Aria report
	check the Rx Checks about "Treatment Precentage" 90% 100% -- Verfiy OK, Comment: Plan Normalization 90%
	click Report - Insert... - Screenshot - uncheck Bolus - change BODY color to pink - click 3D view - click 'Show Field Entry Shape on Body' - change to a good 3D angle - click New and take a screenshot - ...
Block
	Print: BEV view - Print - CANON@Dosimetry printer - select 'Other:100cm', use a ruler to make sure the printout size is accurate
	Cone frame with a thick side is Y2 axis ???
Billing: 1 77295, 1 77300 Basic Dos Calc, 1 77334 Tx Devices Comp
### electron breast
depth = 4.7cm, use 12E.
depth = 1.8cm, use 9E. Treatment Percentage = 90%, bold 90% IDL, make sure 90%IDL covers most of PTV. MRN 22186863
## CSI
### MRN BOODOO, SUNITE 22599251 by Gus, on Linac
PTV3000_Spine 300cGy * 10 = 3000cGy
PTV2000_Brain 200cGy * 10 = 2000cGy
PTV3000_Spine 95%-95%, max 110%, C3 - sacrum, has three parts:C-spine, T-spine, and L-spine
PTV2000_Brain 95%-90%, max 110%, including brain and C1, C2?
brainstem from prior GK
Plan (three isocenters, 24 cm apart)
	Field ID 	Coll Rtn	Field X		X1	X2	Field Y		Y1	Y2
	CSI_Brain	
		1_Arc		15		15.0		7.5	7.5	33		-19	14		X = 0.5, Y = 12, Z = -2
		2_Arc		345		15.0		7.5	7.5	33		-19	14		X = 0.5, Y = -12, Z = -2
		3_Arc		90		15.0		7.5	7.5	33		-19	14		X = 0.5, Y = -36, Z = -2
		covering brain, C-spine, T1-T4?, isocenter at the bottom of the brain
	CSI_T/L Spine	
		4_Arc		15		15.0		7.5	7.5	38		-19	19
		5_Arc		345		15.0		7.5	7.5	38		-19	19
		covering C-spine, T-spine, L1-2.5?, isocenter at the middle of T-Spine
	CSI_L/S Spine	
		6_Arc		15		15.0		7.5	7.5	30		-11	19
		7_Arc		345		15.0		7.5	7.5	30		-11	19
		covering T12, L-spine, and sacrum, isocenter at the intersection of L4 and L5.


### MRN CABREJA, PEDRO 24013835 by Boris, on Ethos
PTV2000_CSI 400cGy * 5 = 2000cGy
Make new structures: PTV2000_Brain, PTV2000_C_SPine, PTV2000_T_SPine, and PTV2000_L_SPine. All four PTVs don't overlap. Those structures are not for optimization, but only for Ref points.
Plan (four isocenters, 20 cm apart, Z is at the posterior of C Spine at the sagital view. Y is at the eyelevel at the axial view)
	1. CSI_Brain: Brain, C1-5		X = 0, Y = 10, Z = 0		3 full arcs: 45, 315, 90	Target: PTV2000_CSI			Primary Ref Point: PTV2000_Brain; RC: RC_Brain
	2. CSI_C_SPine: C6-7, T1-6		X = 0, Y = -10, Z = 0		2 full arcs: 45, 315		Target: PTV2000_C_SPine		Primary Ref Point: PTV2000_C_SPine; RC: RC_C_Spine
	3. CSI_T_SPine: T7-12			X = 0, Y = -30, Z = 0		2 full arcs: 45, 315		Target: PTV2000_T_SPine		Primary Ref Point: PTV2000_T_SPine; RC: RC_T_Spine
	4. CSI_L_SPine: L1-7			X = 0, Y = -50, Z = 0		2 full arcs: 45, 315		Target: PTV2000_L_SPine		Primary Ref Point: PTV2000_L_SPine; RC: RC_L_Spine
The plan is done, check 50% IDL.
Ethos doesn't have jaw so don't bother to set Field Y1 and Y2.
## SRS
MRN: 23385253 ROMERO many courses
MRN: 20938440
Contour
	new structure: ALL_GTVs
		New targets: X. GTV[Dose(cGy)] [Location] where X is the number of the target, prescribed dose in cGy, and location including laterality, (e.g., “1. GTV2100_R Parietal”) 1.后面有空格
	new structure: Brain - ALL_GTVs
	convert all of GTVs or PTV into high resolution segment (if OAR overlapps with PTV, then convert the OAR into high resolution too, otherwise the margin such as 'PTV - Brainstem - 0.2 cm' won't be accurate.
	insert two couches: SRS Support, and encompass support
	crop BODY from couch with 0.1 cm margin
	new structure Wire
		Modify BODY with removing wires - contour ears into BODY - new structure WIRE - change W/L to black and white only - change VOI - Image Thresholding - select all white ranges - apply 
		... - crop wires from inside of BODY
		Wire_HU_-993
	new structure named BODY_IDENTIFY = BODY (crop wire out) + NS_WIRE
	rename old PTV as 1. PTV30 High Rt Parietal^2023_12, Volume Type: None (not PTV)

External Beam Planning - Insert - New HyperArc Plan - C1_FSRT_HA - select Rx 'FSRT_HA:R0 [draft]' - check the highest one if multiple PTV - select the PTV with the highest dose - ... - Select Target Structures ([+] 1. GTV2700_brain, 
... [-] 2. GTV2700_LeftXX, [+] 3. PTV2700_LeftXX, [+] 4. GTV2700_RCB - uncheck the couch 90 degree due to no lesion is close the superior of skull
	Optimize
		Calculation: 0.125
		NTO: Auto (SRS NTO): 100
		uncheck GPU
		All GTV or PTV: 100%, 2700cGy, 100 from start, finally Hayden put as below:
			1.GTV2700_brain lower	100%	2710cGy		120
			2.PTV2700_LeftXXlower	100%	2737cGy		140
			3.GTV2700_RCB	lower	100%	2720cGy		130
			Brainstem	upper	0%	2700cGy		140
Rx: always add surface guided imaging device (pre tx and every tx) and CBCT (pre tx and every tx) 

Report
	Aria report: insert a screenshot of all PTVs and GTVs that are in Rx in the Dose Statistics.
	Export
		Identify, 
		RadCalc,
		MIM
	RadCalc: change BODY to 1.1 or 1.2 due to skull density
	New a hypofractionation Co-Sign Note, Author by radiologist, Supervised by neurosurgeon (find the neurosurgeon's name in the physician's order, if not the full name, then google it)
		Fill in the blank: Region Treated: Brain, Dose: 2700cGy, Fractions: 3. Leave the C1_PD. It's fine.
	Carepath: OSMS (ie, IDENTIFY): mark as completed

Target labelling
1.	New targets: X. GTV[Dose(cGy)] [Location] where X is the number of the target, prescribed dose in cGy, and location including laterality, (e.g., “1. GTV2100_R Parietal”) 1.后面有空格
2.	Previously treated targets: X. GTV[Dose]^tx’d_date (e.g., X. GTV[Dose]^YYYY_MM)
3.	Re-treating a previously treated target: X. GTV[Dose(cGy)] _[Location]^retx (e.g., re-treated 10. GTV2100 = 10. GTV2100_L Parietal^retx)
4.	Gross tumor recurring in a resection cavity:  X. GTVsb[Dose(cGy)]_[Location]
@Physics, when registering the MRI to the planning CT of a previously treated patient and after transferring the previous targets to the new CT, please re-label accordingly. It will simply be adding a suffix to the already labeled target with the treated date (YYYY_MM format). 
Ricky's label:
	HA18-19,22-23
	SRS HA 20-21
	FSRS1-3,11-14
FSRS is for multiple fractions; SRS is for one fraction only.

Evaluation
CI_RTOG = V_RI / TV, eg 1.12
CI_Paddick = TV_PIV^2 / ( TV * V_RI ), eg 0.9
GI_Paddick = V50% / V100%, eg 3.1? 7?
HI_ICRU83 = (D2 - D98) / D50, the smaller (close to 0), the better. eg 0.2

Arc:
the lesion is on the left side, so delete the right Arc (the 0 CW 180 at couch Rtn at 0 degree);
the lesion is on the middle vertical, then delete the superior arc (couch at 90 degree).
the lesion is on the posterior, keep all arcs.

new structures (for PTV2700 100% 2700cGy 100)
_break100: away from PTV 0.15cm at least,	0% 2680cGy 100, try to not overlap w 100%IDL
_break50:  away from PTV 0.6cm,				0% 1300cGy 100, try to not overlap w 50%IDL

## multiple lesions
MRN: THOMAS, SHIRLEY 8019910
One lesion, one plan, one course. Don't put multiple plans in one course because if the patient treats one lesion only one day, then you need to do a lot of works.
Course: C1A_Humerus_R, C1B_Femur_L
make sure therapists not forgetting any of plans to treat:
	create Alert: Summary - New under Patient Alerts - add 'two plans in total' - OK, therapists will get alerts every treatment
	Setup notes: Add 'two plans in total'
## Learn from Others
MRN: 23655765 VMAT Ethos by Rene
Breast w LN, PTV4800, PTV4256, SIM Tx, DIBH
01_CW_ARC 181 CW 50, 02_CCW_ARC 50 CCW 181, ...
NTO: pri 100, 0.3, 100%, 46%, 0.4
Select multiple PTV - 1 isocenter 4 half arcs
KVCBCT setup field only
Ethos's gantry rotation speed is 4 times than Linac
Change the half arcs's angle to 181 - 50
Ethos's big limitation is 28 cm only for FOV (Linac FOV is 40 cm); If > 28 cm, may use multiple isocenter.
Ethos has no jaw, only MLC
Two reference points, one RC in the center of PTV4800
Target is PTV4800, normalization to PTV4800 as well
Duplicate BODY in the free breath scan, Rename BODY as BODY_FB and copy it to the BH scan
Assign HU_water to scar wire if under bolus, otherwise assign HU_air to it.
OPTV_Low is PTV_combined cropped from PTV_High with NO margin
OPTV_Low upper 0% 103%Dose, lower 100% 102%Dose
PTV_High upper 0% 103%Dose, lower 100% 102%Dose
OLung is Lung
Ethos couch is at the bottom of the horizonal (not tilt) panel, double check in the saggital view
Delete the immoblization frame contour from Body near PTV, keep it only for the human body.
If the big circle of ethos touches the couch or Body (it will show a red circle), ask the therapist to re-send a new EXTENDED FIELD OF VIEW (to 850).
Double check the skin folder of the breast, if PTV includes air, un-contour the air part of the PTV. (Yes, dsmt can modify the PTV a little bit)

Tips from Katherine
PTV 100% 4800cGy 160, when in level 3, suddenly change it to PTV 100% 4900cGy 200
GTV 100% 103%Dose 100
PTV 100% 101%Dose 110
OAR               80

Tips from William
Delete the maximum dose in Rx for the lower PTV, only leave one for the higher PTV.
Delete the minimum dose at 95% in Rx, that's too much
General rules: SBRT maximum dose is around 120% - 125%. >135% is too high unless very small PTV volumes, <115% is too low unless no upper objective is added at all
		... most of time, we don't need minimum dose for all types of cases.
Check PET fusion before you start plan for HN and lung SBRT cases, in case MD miss target

Tips from Hayden
----Isotoxic plan: Learn from Hayden----
Isotoxic plan means OAR avoidance is more important than PTV coverage
ROI = OAR
OAR overlapps with CTV: crop the OAR from CTV and override it with the new OAR!
OAR overlaps with PTV:
	Create a Dueduden & PTV+1cm margin structure, put 0.1 3300cGy 70. Focus on the OAR area
	Create a Chestwall & PTV structure, put 0 100%Dose 140. Focus on the OAR area
	Create a OPTV = PTV - Chestwall, put 100% 101%Dose 150. Ignore the overlapping area's coverage. Improve other area's coverage
Add one more Arc at 90 degree. If you can, don't add more Arc.
Add PTV lower objective: 100% 102%IDSL 150??
Can't meet max < 115%, then put Body 0 112%Dose 1000 when in MR Level 3.
Can't meet V2500cGy < 0.4%, then put V2000cGy < 0.5%. Imagine there are two curves there, you try to shift the whole curve to left

-----regular plan from Hayden----
BODY:
	SBRT case: NTO 100 0.5cm 100% 50% 0.9, if 50%IDL is not ideal, change to 45% or even 40%; Ring 3/-2cm
	Non SBRT: NTO 100 0.5cm 100% 50% 0.3; no ring
Ring
	low dose spillage
		Ring wall 5cm/-2cm for conventional cases; wall 3cm/-2cm for SBRT cases
		Avoid = Body - PTV - ring (3/-2cm), put 0 49%IDL because we don't want see sporadic 50%IDL outside the ring.
	high dose spillage (100%IDL looks bad)
		Ring wall 0.8cm/-0.4cm
@@@@@SBRT&Palliative case's priority: nerve OAR (including spinal cord, brachialPlex, caudaEquina) > PTV coverage > other OAR
SBRT or weird shape PTV: start from 3 arcs by default
Avoid radiation going through arm: contour arm with 0.5cm
Spinal Cord max 1800cGy (PTV3000_spine)
	(1-18/30)*2 = 8mm
	optiPTV3000_spine = crop PTV3000_spine from spinal cord with 5mm margin
	Crop spinal cord, leave the length only the same long as the PTV with no margin
PTV2500
	100% 102%Dose 100
	0% 104%Dose 120
Heart max 2800cGy, heart overlaps with PTV:
	Heart&PTV 0% 2650cGy 70
	Heart - (PTV+0.5cm) mean 1000cGy 60 --- push not hard at all
Liver overlaps with PTV but not in constraints:
	Liver - (PTV+0.5cm) mean 400cGy 60 --- push not hard at all

-----from Gus----
HN patient MRN: 10139847
1_ARC 350	15.0 7.5 7.5
2_ARC 10	15.0 7.5 7.5
3_ARC 90	14.2 -0.5 13.7	-- it only covers PTV6600 and part of PTV5940 and parotid areas, not cover full of PTV5445.

-----VMAT Breast w LN----
DANIA, MRN: 21665995
Four half arcs
Change the gantry angle to 181-55
Fit the  collimator
Change the field size as below:
	Arc_1 181-55 	5 	Field X: 15	X1:-7.5	X2:7.5		input 15 in the field X, cover superior and inferior
	Arc_2 55-181 	355	Field X: 15	X1:-7.5	X2:7.5		input 15 in the field X, cover superior and inferior
	Arc_3 181-55 	85 	Field X: 15	X1:-3	X2:12		change the X1, cover lateral of the upper part
	Arc_4 55-181 	95 	Field X: 15	X1:-11.7 X2:3.2		change the X2, cover lateral of the lower part
Always put 100% lower object, such as 100% 93%Dose 80. If you put 99.5%, even put very high dose, small corner PTV could be not covered at all.
Put 100% lower object to PTV_SCL and PTV_CW
Put 0% upper object to PTV_CW

-----Breast 3D w boost-------
Plan name	Field name	Gantry	Colli
old		1_Med		49	356
old		2_LAO		6	4
old		3_Lat		229	4
new		1_Med		49	356
new		2_LAO		4	4
new		3_Lat		235	4
CI of old is 1.46; of new is 1.35. Lung and heart are barely different.

electron vs photon
MRN: 23975359
The conformality index was the same with new photon plan/electron plan (CI is 1.35). There was more lung/heart dose with electrons, despite slightly higher normal breast with photon new plan, we approved the new photon plan.
BTW, electron uses 12E.

## case study Prostate w LN 86/80/72/68/56 in Edge w two isocenters
Prostate w LN 86/80/72/68/56 in Edge w two isocenters, using autocrop : BORDON FUNDORA, ROBERTO 20254084, WOOD, ROBERT 0949687
One plan with two isocenters:
	1_CBCT, 1_ARC_1 (coll angle: 10, make sure covering the left side), 1_ARC_2 (coll angle: 350, make sure covering the right side), covering the superior part of PTVs
	2_CBCT, 2_ARC_1 (coll angle: 10, make sure covering the left side), 2_ARC_2 (coll angle: 350, make sure covering the right side), covering the inferior part of PTVs
	Dose pr Fx: 215, Num Fx: 40, Total Dose: 8600, Target: GTV8600_BOOST, Primary Ref Point: GTV8600_BOOST, Plan Normalization Val: 100.10% (which equals to 100%-95%)
	Reference points: PTV5600_1, PTV5600_2, PTV6800_1, PTV6800_2, PTV7200, PTV8000, GTV8600_BOOST, RC
	
1. Plan_Sup
	1_CBCT, 1_ARC_1, 1_ARC_2, covering the superior part of PTVs
	Dose pr Fx: 180, Num Fx: 40, Total Dose: 7200, Target: PTV7200, Primary Ref Point: PTV7200, Plan Normalization Val: 83.8% (=72/86)
	Reference points: PTV5600_1, PTV7200, RC_Sup
2. Plan_Inf
	2_CBCT, 2_ARC_1, 2_ARC_2, covering the inferior part of PTVs`
	Dose pr Fx: 215, Num Fx: 40, Total Dose: 8600, Target: GTV8600_BOOST, Primary Ref Point: GTV8600_BOOST, Plan Normalization Val: 100.10%
	Reference points: PTV5600_2, PTV6800_1, PTV6800_2, PTV8000, GTV8600_BOOST, RC_Inf
3. Plan_Sum
Report: two RadCalc reports, one Treatment plan of Plan Sum (need check Plan_Sup and Plan_Inf in the report)

Helper structures
1. _control_80_0.2cm: crop from GTV8600, control CI of GTV86
2. _control_80_0.5cm: crop from GTV8600, control hotspot of PTV80
	0%, 8500cGy, 100
3. _control_56: crop from PTV80 w 3 cm, PTV72 w 2 cm, PTV68 w 1.5 cm
	0%, 6100cGy (109%), 80
4. _control_86-Urethra: crop from Urethera w 0.2 cm
5. _loop_56: crop PTV56 w 0.3 margin
6. NTO: automatic 100
7. Anorectum Rx V4000cGy<35%; Optimization: V3500cGy<30%, and V4000cGy<20%., priority: 100. and 0%, 8100cGy, 100.
8. Bowel_Bag Rx V4000cGy<150cc; Optimization: 71cc(2%), 3800cGy, 100; 540cc(15%), 1500cGy, 50.

ISL: check 4000cGy as the lowest ISL

GTV86 100%, 8600cGy, 100; 0%, 9100cGy(106%), 100
PTV80 100%, 8000cGy, 100; 0%, 9100cGy(106%), 100
	_control_80_0.5cm 0%, 8500cGy, 100
	_control_80_0.2cm 0%, 8650cGy, 200 (added by Lu)
CTV80 100%, 8000cGy, 100; 0%, 9100cGy(106%), 130
PTV56_PLN  100%, 5600cGy, 100; 0%, 8200cGy(106%), 100, due to overlap w PTV80
	_control_56 0%, 6100cGy (109%), 80
PTV56_Dis  100%, 5600cGy, 100; 0%, 8700cGy(106%), 100, due to overlap w PTV80

## Case Study misc
1350 cGy * 1 fx case is sent to MD to review, he thinks the 50% ISL is not safe, so he change it to 2500 cGy in 5 fx.
3D plan is too hot (128%), Karen changed the prescription from 95% - 100 % to 95% to 95 %, and mentioned it in the review email to MD.
#### Large MU duty cycle:
	MU duty cycle is 9, way more larger than 5. Total MU / Daily Dose should be less than 5.
	1. Add one more Arc
	2. MU Objective, set maximum MU as Daily dose * 5 (2500 = 500cGy * 5), strength is from 0 to 100, which is the priority for MU Objective. Check MU number while optimizing! 
	... If MU total is required less than 4000, you can put 5000 priority 50 because you can go a little larger than 5 and don't want to hurt the plan
	3. Try to use 10x instead of 10xFFF, Try to use 10x instead of 6x
	4. Set min MU
	5. LinacA should be < 5 strictly!!! Other machines prefer < 5 but could be around 6
	6. Re-optimization from ML level 1 (instead of from ML level 3) could be helpful to reduce the MU
	7. Change SRS Arc Therapy to Arc Therapy if not SBRT cases
#### DIBH
	DIBH was written in Prescription and in physician's order; However, in some reason she was only scanned in free breath. I planned in the free breath CT and sent it to MD approval but I forgot to change Gating:DIBH to Gating:None.
Field X size for large volumes
	Set 4 full arcs - change collimator angles - Arc Geometry Tool - Fit Collimator to Target - change Field X, X1, and X2.
	Field ID 	Gantry Rtn	Field X		X1	X2 	Field Y
	Arc_1		30		15		7.5	7.5	22		cover lateral
	Arc_2		330		15		7.5	7.5	22		cover lateral
	Arc_3		90		15		-15	0	22		cover superial
	Arc_4		90		15		0	15	22		cover inferior

#### 3D for large volumes on Edge
	AP and PA
	click I in front of PA in the Group column - create a new group
	change SSD of AP to 100 - MLC - Fit to structure - check whether PTV fit inside of FOV
	same to PA
	Calculate
	Norm to 100%-95%
	Adjust field weighting, look at the volume with dose >110% and the max dose. We finally adjusted AP 48% and PA 52%
	Add a FIF, if D0.03cc>115%, that's not acceptable, add more FIF. We finally got 108%
		when move MLC, an error prompted saying distance limitation; so I move the X2 jaw close to isocenter, then try again
		when done, merge subfields
	Since the plan have two isocenters, we need to split them into two plans
		change the norm from 100%-95% to 'Plan Normalization Value:69.45%'
		copy the plan into three plans: DNU_SUM, Iliac_R_AP (delete PA fields), Iliac_R_PA (delete AP fields)
		in Iliac_R_AP plan:
			new structure with 50%IDL, and new structure named opti_PTV2000_ANT ( = PTV2000 & 50%IDL) -- Don't why this step????
			new reference point named PTV2000_ANT (no location, check Target, fill the dose, set as the primary reference point)
			new reference point named RC_ANT (put it inside the opti_PTV2000_ANT)
		in Iliac_R_PA plan:
			same
		insert a plan sum and ask MD to approve it.


## PLANNING TIPS
#### 与PET blend看enhancement
Pt - View - View Parameter - hot iron - Save
File - open - plan - click CTSim - click Registered Images - rc PET images - Blend with CTSim
usually check volumes for SBRT lung and conventional HN cases before you plan.
#### SBRT
Calculation Models: 0.125
PTV High Resolution, GTV as well if GTV is used to be optimized too
Every field uses SRS Arc Therapy technique
Ring 2cm, 50% IDL should not touch outside of 2cm.
If PTV is next to spinal cord, then SBRT max dose is 120%; otherwise 140%. Make it as hot as you can, especially for whose tx intent is ablasive
Hotspot is in GTV, not at the border of PTV.
#### --misc--
2 cases are good, 3 on top in progress
I am responsible for: primary on west, secondary on main, no on proton, doral, lennar, and DFB.
7:30 am - 4:00 pm, 8:30 am - 5:00 pm with 1 hour break during 12 pm to 1 pm.
MRI: dark means domestic lesion
Pacemaker only 6x, 6xFFF
SBRT only FFF
OAR max<=2500cGy is not met, change it to V2500cGy<=0.03cc.
PTV max<=110% is not met, change it to D0.01<=3300cGy??
800cGy * 1 fx spine: max 115%, 100%-95%

-----exception planning---
a course with two plans: MRN 20244772
add setup fields for each plan, make rename with different names, such as AP SETUP_I for the first plan; AP SETUP_II for the second plan

---SIM plans---
Target Structure: GTV3000_Rectum
Primary Reference Point: ID: GTV3000_Rectum
Normalization to GTV3000_Rectum
Arc Geometry Tool - Target: PTV2500_Rectum
Reference Point: GTV3000_Rectum w/o location, PTV2500_Rectum w/o location, RC_GTV3000_Rectum w location

-----AP/PA----
If MD draws PTV, then use 100%-95%, Rx: Prescribe To: Volume, PTV3000_L_Hip 3000 500.
If MD doesn't draw PTV, then use 90% ISL, Rx: Prescribe To: IsodoseLine 90%
If MD doesn't put any on Prescription Coverage Constraints, then only put BODY on Clearcheck, add Plan Structurer and Plan Check as well.

---field x size ---
keep it less than 14.5 for IMRT; 3D don't care about the field x size, the field will be split into multiple carriage groups
@@@@@@@@@@@@@@@ If the machine have jaw tracking feature (eg. all Truebeam machines have it), then field X could be larger than 20 cm. However, considering replan in a different machine, we prefer to keep less than 14.5 even in Truebeam.

---normalization--
100% of dose covers 95% of target = Dxx > 100% (D95% > 100% ) = Vxx > 95% (V100% > 95%) = At least: 95% of PTV2500 at 100% of 2500cGy

---GPU---
When optimizing Hyper Arc plans, please avoid using GPU as it doesn’t support optimization with high resolution (1.25mm) and it switches it to standard 2.5mm resolution for optimization. 
Since hyper arc optimization defaults to 1.25mm optimization, if GPU is checked it will change to standard without prompt. As always, the final dose calculation should be performed using 1.25mm resolution.
I spoke to Varian yesterday and this will be changed in version 18, albeit potentially leading to memory issues. In the meantime, turn off GPU for Hyper Arc plans, and this will probably give you better plans especially when there are very small targets.

@@@@DO NOT check GPU for SRS and SBRT cases.

---Selection--
split two 3D images in the same frame
	Selection - click that series - Image - Change Patient Position - check 'Assign a new frame of reference'

------duplicate CT slices----
Drag all images to the right upper corner, select the superior image - click Image - click Duplicate - input Position z number, such as -23.5 cm (the current slice is -26.5cm), then you got a new superior image 266 
... - drage the new image 266 to the right upper corner too - select all images including the new image - rc - new 3D Image.

------varian support---
Call 888-VARIAN5 - Press 2 clinical support - Press 4 treatment planning
Explain to the varian custom service: I have a CT short at top. I'd like to duplicate slices but I don't know how. Please help me out.
https://rs.varian.com/, input the session key that the custom service provides

------misc-----
if override HU, rename the structure as HU_3888_SurgicalClips, HU_-993_BBs, etc
At least: 95% of PTV2000 at 100% of 2000cGy ==> CC: V100% >= 95%
can not meet minimum dose
	min>= 90% can change to Min Dose Volume: MinD0.03cc >= 90%, OR even change to MinD1% >= 90%
	new structure, contour three slices, one of which is the superior or inferior of the PTV
	
Workflow:
	101724...Need Volume...Edge
	103024 WILLIAM Ready to plan Edge
	000000 SBRT case: after PTV is done, plan is within 3 days, tx starts within 5 days. eg, volumn is done at 10152024, 101824 OK to plan, start tx 102224 or after
	Schedule SBRT Tx's note: ready to schedule, start 102224 or after.	
	OK To Plan -> XUEYAN LU Ready to Plan -> XUEYAN LU Review

b1_Arc: b for bolus
Email to MD to review the case, cc the chief therapist

Avoid radiating through arms because arms are easy to move then the dose will not be accurate

-----contour----
Strip_skin: 1 cm thick of skin
CW: 3 cm thick
Bowel_Bag: barely use Bowel in this hospital, almost all Bowel_Bag. If it overlaps with PTV, then crop it from CTV only, not from expension.
LiverEff = Liver - CTV_liver

-----Dose limits----
SBRT Liver: Liverr-GTV (for non-cirrhotic liver) mean dose < 15 - 17 Gy
V3200cGy < 30cc
V3000cGy < 70cc

------MIM------
Dr. Mahal has a case ready to plan, so open MIM
	Input patient ID and search
	Select CT (CTSim, not PETCT), and RTst (final for planning)
	Send To Eclipse
Eclipse - Import from MIM
change to new or old GUI
	click gear button at the upper right corner - click 'Patient List Options' - check/uncheck 'Use Classic Patient List'

_BH: breath hold
In UM, pt come, do CBCT, which is used as a reference during Tx. In other hospitals, the FB in simulation not the CBCT during Tx is used as a reference.
UM uses brass bolus.

### change to BID Ethos
1. Aria: 
	Plan Parameter - Create Revision - in the new plan: double the daily dose of the reference point
2. Ethos: 
	Create Revision - click the down arrow of Phase 1 - Edit 'One session per treatment day' - select 'Minimum time between sessions: 6 hours' - Authorize - re-import plan's RP file because revision will clear the RP file.
3. Add a journal: Change to BID per MD. -- Lu
4. Email or call physicists to approve the plan in Aria since they don't have a task in carepath.

### 3D
1. 3D T Spine
10X, gantry: 180, 140, 220. Spare kidney. 95%-97%, hotspot 108%
2. 3D Acetabulume
15X, AP/PA, AP:PA=1:2 to avoid the bowel at anterior, 
3. 3D R iliac
6X, RAO=320, RPO=220.

4. 3D whole brain
May need to edit fluence to reduce lens dose, to keep it max < 7 Gy. Using Decrease Transmission Factor (brush size 0.4 cm, Transmission Factor 0.3)

# import images
Import all patients if the Treatment Center (not simulate center) is in SCCC West
	West - Import/Fuse/Volume - Available, then import it
	West machines - CT Simulator - green checked patient, then import it
	West - 4DCT-Generate ITV - Available
Dr. Azzam, Dr. Melon, Dr. Mahal: MIM only
Dr. Kubercek: eclipse only
@@@@@@@@@@@@@@@@@@@@@@4D or SRS or deformable fusion: MIM. Physicists are responsible for these fusions.
Carepath - mouse hovering on the Import/Fuse activity - got the Department information, it should be SCCC West
Carepath - mouse hovering on the new Tx activity - got the machine information, such as Ethos


Open MD Tx Plan Note, got information: 3D, T4-T2. This document is for insurance.
Open Physician's Order, got information: BH, freebreath, MRI (10/16/2024, T2 Axial)
	**If scans are in JMH PACS, ask Physicists to import the scan (email or add an activity??)
Open care path, check which facility the pt will have tx

UMPACS
	MRN is pt ID, find images (PET images: PET WB CTAC and CT WB (not AC CT WB)) - double click - export to DICOM - click V - UMHC RT Eclipse 15 
	**If can't find the pt through MRN, then use pt names instead.
MIM is used for contouring, plansum, fusing, breathhold, 4D (create ITV).
Eclipse
	import images from either CTSim, PACS, or MIM
	rename PTCT_101224, CTPT_101224 (both series, images ID and image description), RibsTsp_101524 (CTSim's series, images, CT set structure). ThrxFB_101524 (free breath w/o contrast), ThrxBHwC_101524 (breath hold w contrast)
	rc CT set - Properties - Physical Material Table: AcurosXB-13.5
	rc CTSim Series - Properties - Imaging Device - XXXX 5674 (5674_pHN is only for proton H&N cases, CT49408 is for main)
	User origin
	Proton
		no couch
		if verification, then 1. fuse with the previous plan CT, no other fusion needed; 2. autocontour
		no Note for any proton cases in the care path

Fuse Diagnostic CT from UMPACS to CTSim in MIM
	UMPACS - Select the scan with the most slices - rc - Export to UMHC RT MIM, wait several minutes
	MIM - Select two Patients on the left - rc - merge - info
	Select two scans - open - click the two circle icon (fuse two series) - click 'Select this series' of CTSim - click the gear icon (Fusion Settings) 
	... - Run Box-Based Assisted Alignment - rotate? move? Align the carina rather than spine for chest cases - click Save - Save DICOM Image Data - cick the bottom fused scan (may with the name of CT/CT Fusion #1)
	... - click the DICOM... icon at the upper right corner - select Registration - after it done, a new modality is seen under the CTSim scan.

BH
Fuse BH scan w PETCT

SRS
make sure CTSim existing in MIM???
If Fusion is not completed, wait physicists to Fusion at first
Elseif Fusion is completed, then:
	If Dr. Kubecik, import from MIM to eclipse, mark Import/Fusion as completed
	If other MDs, mark Import/Fusion as completed
	Add notes:
		Import/Fusion: 110624 Need Volumes SRS
		Ready to plan: 110624 Need Volumes SRS
		Print Isodose plan: 110624 Need Volumes SRS

4D
CTSim should be in MIM already
4DCT Integrity Check: phycisits will do it
4DCT-Draw Target on S..: MD draw volumes
Add notes:
	Ready to plan: 0000 START TBD SBRT Needs VOLUMES
	Print Isodose plan: 0000 START TBD SBRT Needs VOLUMES
4DCT-Generate ITV: Dsmt takes when it becomes available
	Open both 0-90% series and Average series - Click 0-90% series -  click 4D - Select All (- Setting icon - ITV Creation Options - select Deformable Propagation) - highligh GTV - Create ITV - waiting propagating
	... (two new structures generated: GTV, which is GTV in all Phase, and ITV) - rename the GTV in all Phase as GTV_All - Contours - Transfer All Contours (means you transfer contours in 0-90% to Average, you can see structures with ghost icon after you transfer)
	... - 1. Save ITV in Average: 
				Select GTV_MD (don't select GTV_ALL) - select Average CT on the upper left corner - click the save icon at the top - click Save DICOM RTstruct - select Average CT - Q: Transfer Ghost Contours? - Select No (because 0-90% has those contours already and you don't care of them )
				... - Q: Continue saving w/o including the 4 ghost contours? - Select Yes - input Series Description: ITV. Done. (Don't need to save ITV on 0-90% series)
	... - 2. Save ITV and GTV_All in 0-90%
				XXX
	
	... physicists will evaluate the ITV motion and export ITV.
	*ITV is a single structure, while GTV has one structure for each phase (there are 10 phases in 4D)
	----Export from MIM----
	Documents - Motion Assessment file - it says choose Free Breathe - go to MIM - Export - select:
		1. CT	4DCT AverageCT iMAR KD/JL
		2. 	RTst	ITV on Avg	jxc2508 (Jonathan)	
	Eclipse - import from MIM - autocontour etc.

Fusion tips:
	MRI prostate only focuses the prostate area and rectum, all softtissue matters, don't care about pelvic bone.
	PET/CT in UM always has two sets, one set of arms up, the other set of arms down. Only import the arms down (not the one with the most slices or the one with marks), which arms' position is the same as that during tx.
	PET/CT: look at the PETCT MIP black and white series. Those dark spots are enhancement spots. If the dark spots only exist on the small area, then focus on that area to fuse; 
	... elseif the dark spots expand on different areas, such as oral cavity and lower neck, then fuse on the large area and need a deformable fusion.

PETCT fuse to 4DCT
(in UMPACS) export PETCT to MIM
(in MIM) select PTCT, CTPT, and CTSim (4DCT 0 - 90 %)- click Open Series - select 'Fusion two series' - Select Primary Series: click CTSim - Select Secondary Series: click PTCT 
	...- a new fusion named 'CT/CT Fusion #2' (CT2 Primary and BH_2 iMAR series) is created - click the axial view of this fusion - click 4D, select one phase whose lung volume matches the PTCT most 
	...- Run box-based Assisted Alignment - click the plus/square icon to run - check - rc - Save DICOM Image data - choose registration - name: PET to 4D registration - close all sessions
	...- click Export - choose PTCT, CTPT, CTSim (4DCT 0 - 90 %), and 'PET to 4D registration' - click Eclipse - send it
	**if delete a registration: click Data Management - click the registration - click Delete
	@@@@@@@@@@@@@@ Need to fuse twice!!! ( PTCT to CTSim and CTPT to CTSim)
PETCT fuse to CT from Rod
	@@@@@@@@@@@Workflow - Organ - PET - Single PETCT to CT R - TG1-32 - Import
	@@@@@@@@@@@Workflow ... - 4DCT-ITV Creation

PETCT deform fusion
Dsmts do fusion in eclipse and add a task for physicists to check. Drop the template 'SCCC West - Special physics' (It should say ‘Physics’ not ‘Physicist’ under staff), and add a line to 'Review/Draw Target Volumes'

Troubleshooting:
1. import 3 MRI series, it only shows one series on Contouring, but all three exists in files:
	Selection - drag one series that does not show - Ctrl + A to select all images - rc - new 3D Image - click OK to all prompting warning - input the ID name such as MRI_T2_Csp_Inf
	select images from the one image that is not selected to the end - rc - new 3D Image - click OK to all prompting warning - input the ID name such as MRI_T2_Csp_Sup

--fusion---
Use aorta and carina to align the chest area

Care path
(Have already sent PET from PACS to MIM)
Items - Activities - Search - fusion - drag to today - note: Fusion with PETCT (already in MIM). Dr. Mahal is OK w only PETCT (no MRI).
Add a line bw fusion with Need Volume
mark Import/Fusion as completed

proton
no couch
Imaging device:
Care path - Add note for 'Drop Proton Care Path': TBD Need Volumes

SRS, 4D, SBRT, ADC early late MRI prostate's fusion always go to Physicists @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@

--proton
pLiver means proton case
Proton cases only have CTV, GTV, not PTV at all. Plan on CTV.


## import images tips
MRI: Dr. Rich: Notice that the full name of the sequence is "T1 MPRAGE POST". The "post" means after contrast administration. If they did the sequence before IV contrast administration it would be "T1 MPRAGE". For my cases, please grab the "T1 MPRAGE POST" 
Bladder cancer: use the empty bladder scan, autocontour on it and fuse images to it, rather than the full bladder scan

# Review
## Before Review
Change Course name to C1_Prostate, prefer that Rx, Course name and plan name are the same
PTV's type is PTV
Change the structure's name CT structure, Clearcheck, Prescribe, Plan Check
Reference points and Calc points
	Ex Planning - rc GTV7720_Prostate - new location for - new reference point - delete - Delete location from image 'XXX', rc the reference point - Type: Target
		Primary Referenc Point select GTV_high, not PTV
	Ex Planning - rc PTV7020_Prostate - new location for - new reference point - delete - Delete location from image 'XXX', rc the reference point - Type: Target
	Ex Planning - rc GTV7720_Prostate - new location for - new reference point - rename it as RC
	Reference Points - Fill in all dose limits in the table (for the secondary reference point and RC_point, but not for the verification plan)
	Reference Points - check Without Dose - click the down arrow of PTV7020_Prostate - input the dose number for each arc (= daily dose / arc_number, ie, 270/2=135)
	*Ex Planning - Reference Points - make sure there are numbers for each column; if not, go back to Reference Points.
	*Ex Planning - Reference Points - make sure the RC dose is close to or larger than the primary reference point. If not, move the RC point; or make two points for two arcs.

Change IDL to IDL-review
Add Setup fields: AP SETUP, LT SETUP, CBCT. Make sure Field X and Field Y are 10*10, change gantry plan. Use 6 MV only.
ADD DRR: Bone for all setup fields. Select bone for Tx fields if VMAT; select others such as breast for Tx fields if static IMRT or 3D.
Prescribe Treatment
	Energy: 6X
	Gated
	make sure all PTV names are the same as ones in CT sets (OAR names could be different)
	if need to change: V2000cGy < 50%; V2500cGy < 0.03cc if change the max dose
rc any field - Properties - Tolerance: T1
	Double check Dose rate (6xFFF: 1200, 10xFFF:2400)
rc the plan - General - check Use Gated if DIBH (*Ethos* Don't need to check Gated)
Mark previous course as COMPLETED
ClearCheck
	Constraints -  口口s, ie. Create Structure Template from Constraint Template - click Structure Checks - Select Left or Right under Laterality for Lung L, Kidney R, etc.
	Plan Checks - Photon/Electron Plan Checks for regular; Stereotactic Plan Checks for SBRT or SRS - + - check it only - OK
	make sure everything is green under Prescription Checks
F4 check approval error
Mark Ready to Plan as completed
Email MD: Title: SHNADER, SONIA 8486310, Body: Hi, the patient is ready to review. Please noted .... Let me know if you have any questions.
-----SIM-----
Clearcheck: PTV_low select PTV_low, not OPTV_low, if the max dose is over the limit, then just delete it, and delete it in the Prescription as well.

**At least: 95% of PTV4005 at 100% of 4005cGy --> Eclipse: normalized at 100%-95% --> CC: V100%>95%

## After MD Review / wrap up
\\Client\W$\ECLIPSE PLANS\XL

Delta Couch Shift Editor
ClearCheck
	Report- uncheck everthing except PTV3000_Lt Hip (two checks)  - Thickness 3 on 100%ISL 
	Isodose (cGy) change to 1500 (which is 50% ISL), change Y Spacing [cm] to 1. It could be 0.5 cm for a small PTV, or 3 cm for a big PTV, as long as 6-9 slices.
	PDF to ARIA
	Supervised by MD
Treatment Preparation
	Setup Note: Copy from Therapist Worksheet + CBCT only or CBCT / IDENTIFY (Prescribe Treatment: CBCT pre tx, every tx; KV pre tx)
	Setup Notes / Photos: Edit - Add Photos - 
\\Client\W$\PUBLIC\PT_Setup_pictures_ West\2024\10-18-24
\\Client\W$\PUBLIC\PT_Setup_pictures_ West\2024\11-13-24
\\Client\W$\PUBLIC\PT_Setup_pictures\2024 MAIN pictures\2024-10-07
\\Client\W$\PUBLIC\PT_Setup_pictures_Lennar\2024\2024-10-28

Reference Points: Fill in the blank. Do not fill in the C1_PD
	Delete all locations for all primary reference points, make sure 'Planned Total Dose' is 4005cGy, not something like 4002.8.
QA for IMRT only:
	Planning - Creating Verification Plan - New Course - C1 PD (C1, not C2, the course number is the same to the tx plan)- SID: 100 cm - Tolenrenc: T1 - rc the plan - Planning Approved
	*Ethos* Ethos don't need above step
	*3D* 3D don't need above step
Plan Scheduling
	Course: C5 Lt Hip
		AP SETUP and LT SETUP: Add Imaging - kV Imaging
		CBCT: Add Imaging - CBCT
	Course: C5 PD
		Arc_1 and Arc_2: Add Imaging - Portal Dosimetry
	*Ethos* Ethos schedules automatically
BH:
	All west cases with BH needs to export to Identify
	*Ethos* Don't need to check Gated
Plan Parameter
	Validate for Treatment, make sure no error
Reradiate
	If PTV overlap w previous Tx, then fuse w old CT, copy old PTVs to the new CT and named as _PriorXXXX; insert a plan sum, and generate a plan sum report. May need to change OAR dose limits according to QUANTEC or ask physicists.

----- RadCalc ------
Eclipse: rc the plan - export - RadCalc West - Export and OK
RadCalc: 
	Select site (Coral Gables for Lennar)
	Import - Select the patient - Import Selected - Double click the plan with Checked By --- --/--/---- 
	change name: Prescription: Lt Hip ???
	Compute All Beams (F11)
	Photon Beams - Beam ID: Arc_1 - Select Calc Pt: RC_Lt Hip
	Select Points to Print: only select rad calc 1 ???
	make sure %Diff < 5%, if not, try:
		Select "For all beams, set Inhomogeneity Correction: EQUIV PATH"
		MLC Data - Volume Average Dose - Enter Sampling Radius for Volume (cm): 0.10, change 0.10 to 0.15 or 0.2 - Check the smallest %Diff on the list
		Click Regions of Interest (an icon at the right upper corner): 
			change the PTV-Lt Hip from 1.000 to 1.3, or change the lung from 1.000 to 0.3, check 'CT Override'
			change BODY from 1.000 to 0.9-1.15, check 'CT Override'
			If the beam goes through a lung or bone (skull or humeral head) which is not contoured, then go back to eclipse and contour them, then come back to RadCalc to change the density.
		*Hayden doesn't agree with this, he thinks never clear this* BODY - click down arrow near 'Set External ROI' - Clear the selected external ROI, put 0.9 or 1.1 instead 1.0
		Eclipse - File - Print - report - Adobe PDF - Layout: Full.html - Preview, find the page including Depth and 'Eq. Path Length'
		... - RadCalc - Photon Beams - Avg. Depth of Treat.(cm): put the Depth number; Avg. Equivalent Path Length: put the 'Eq. Path Length' number
		uncheck 'Print Point Doses' if the number at the upper right corner is different from ...
	Points & Off Axis Assistance: change the Name to RC_Lt Hip.
	Save - Print
		Select Beams to Print, uncheck the useless one like isocenter, only leave Arc_1 and Arc_2.
		If more than one calculation points are used, uncheck Print Point Doses
		Set Path as \\Client\W$\ECLIPSE PLANS\XL
	**Exception**
		If the plan is outdated and Compute All Beams is done, calculation need to be deleted at first (rc the plan in the RadCalc and delete the calculation)
		If you can't pass %Diff < 5%, and need to create a new RC, then:
			cp & paste a new plan named as T8_10_MU
			Add a new RC
	if RC needs to be changed or is missing
		Copy the MD approved plan as ENT_MU
		Create a correct RC
		Export the ENT_MU plan to RadCalc
		In RadCalc, add comment: RC generated from a copied plan. Report is attached below. 
		In Eclipse, drag the ENT_MU plan, File - report - MS Print to pdf - Full.html - Save to \\Client\W$\ECLIPSE PLANS\XL too.
		In W:\ECLIPSE PLANS\XL: click both pdf files - rc - combine files in Acrobat, import this combined files to Documents as a RadCalc report.

Import RadCalc
\\Client\W$\ECLIPSE PLANS\XL
	Supervised by MD; Document Type: Phy.-MU Check; Template Name: Lt Hip

------ Encounter -----
Create Physics Billing Appointment (both for 3D and IMRT) - Check-in Physics - Select anyone on the list - change time as the MD approval day - wait for one minute - Mark as completed
Add Hypofractionation Document if SBRT (fx <= 5 or session dose >= 500cGy)- + 
	Documents - New - Template - select Hypofraction Co-Signature Note
		Region Treated: Lt Hip; Dose: 3000 cGy (total dose); Fractions: 5. 
		If need to change the content of the note: Review - Restrict Editing - Stop Protection
	Delete the C5_PD line under Treatment Plan
	Authored By / Supervised By co-sign MD (if there are two co-sign MD, then put the primary MD name instead)
	Make sure Date of Service is the same with the MD approval day
	Email co-sign MD: Title: Hypo note needed for SHNADER, SONIA 8486310; Body: Hi, Hypo template is ready on Document. Please sign it when you are available???. OR Please let me know who will co-sign it.
	Email cc both primary and secondary physicists that day
N/A the last four items since SRS


------ CarePath -------
**make sure these documents have the MD approval day. It doesn't matter for other items**
	'Date of Service' of the 77300/77301/77338, 
	'Date of Service' of the Aria report
	'Date of Service' of the RC report
	Physics UChart Encounter
Review Treatment Plan: mark as completed
Print Isodose Plan: mark as completed, change time to 9 am today if the physics review is needed today
	Billing
		IMRT: 77300 #field, 77301, 77338;
			@@@@@@77301 IMRT Plan is for CTSim scan.
			IMRT boost with one arc: 1 77300, 1 77338
		3D/electron: 77295, 77300 #field, 77334 #field (as long as MLC shape changes for each field) 
		...Eg: a LAO field at 300, a RPO opposing field at 120, a LAO_2 field at 340. Then 1 77295, 3 77300, 2 77334 (bc LAO_300 and RPO_120 share the same MLC shape so you only charge once)
		If Motion Assessment for Photon Treat... (Document Type: Phy.-Note) exists in Documents, then charge 77293 ET for ethos, 77293 for other machines
		Change Course to C5 Lt Hip
		Mark it completed - make sure 'Date of Service' of the 77300/77301/... is the same MD approval day (the Start date is OK to be different)	
	Account Number: Click PHYSICS with the same day with the MD approval day
Ethos Prep & Import Plan:
	an error prompt with checklist - Open the activity - click Checklist - check everything - mark it completed (don't need to change the time)
Ethos Print Isodose Plan:
	the time is MD approval day!
Drag SCCC West - New Start VMAT/IMRT and drop it on the Print Isodose Plan
	double click Run IMRT QA - add machine name to Resource/Staff (check the 'New Start' item to get the machine info)
		3D Plan doesn't have IMRT QA, so skip this step
	**OnPatient Dosimetry if pacemaker, just drag it on the Patient Review line, don't drop it on any item. Add note: mosfet reading on pacemaker. Eg: MRN 0001639
	**Drag 'SCCC West - Special physics' (It should say ‘Physics’ not ‘Physicist’ under staff) on the Print Isodose Plan if there is.
	rc any item - schedule - select the bottom one, schedule for all



## wrap up Ethos
Print patient like normal in Eclipse. Print report/MU check. Add Tx Prep/Scheduling/Carepath/etc.
 
1. Create patient folder in 
W:\ECLIPSE PLANS\ETHOS
ECLIPSE PLANS\ETHOS\NIEVES, MARIA
\\Client\W$\ECLIPSE PLANS\ETHOS\
2. Send plan to W:\
	rc the plan - Export - DICOM Media File Export Filter (From CT SIM) - Change destination to patient folder created in W drive
	... - Uncheck everything and select only the desired course/plan
3. Log in to Ethos workspace (https://10.64.117.136/Citrix/StoreWeb/)
	Ethos Tx Management - Search for patient by MRN - + - Add diagnosis/Region of interest/No planning directive. Next
	Add targets (refer to Rx) - Add # of phases/Rx - Add OAR (refer to Rx)
		V95%>=95%
		V105.0%<=10.0%
		Dmax<=107%
4. Contours
	Drag in planning CT and click Accept
	Unlock and rt click - clear all contours ???
	Click ^ on SS. Click expand button
	Match Ethos structures to Eclipse structures
	Authorize
5. Dose preview: Only needed for adaptive cases
6. Tech structures
	Edit - set ISO (drag the isocenter to the user origin (3BBs)) - Confirm
	Edit - set Couch - Confirm
7. Plan Review
	Click 3 dots on side and Import plan. 
	***CANNOT INPUT THE LINK, HAVE TO SELECT THE FOLDERS ONE BY ONE
	Select RP file from W drive folder you created earlier
	Add setup instructions/photos (2 photos max) (Yes, you need to add these info in Treatment Preparation as well)@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
	Select the imported plan
	Plan Report: make sure MUs match Eclipse plan
	Plan QA
		a) SBRT plans: QA in Eclipse like normal bc Ethos dose grid is not accurate enough
			@@@@@@@@@@@@@@@@@@ refer to the document 'ETHOS SBRT ARCCHECK'
		b) VMAT: Create patient folder
			W:\PUBLIC\ArcCheck QA\2024 Patients QA\NIEVES, MARIA_QA
			Select template (FF means feet first)
			DICOM export to receiver
			Calculate (can take 10-40 minutes)(will say zip folder created when complete)
			Export Calc Results to patient folder created in PUBLIC\ArcCheck folder
			Unzip results. Cut and paste RD and RP file. Can delete the rest of the files.
		c) 3D plans: Just click DICOM Export to Receiver (SCP)



## Hypo note
•	External beam cases delivering high dose radiation in 1 fraction greater than (but NOT equal to) 8Gy and that are defined as stereotactic radiosurgery (SRS) require a hypofractionation note.
•	External beam cases delivering 2-5 treatments that are defined as stereotactic body radiation therapy (SBRT) or treatments with doses greater than (but NOT equal to) 5 Gy per fraction regardless of the technique, require a hypofractionation note.
•	External beam cases delivering 5 Gy per fraction only require a hypofractionation note when delivered as SBRT.  Thus 25 Gy in 5 fractions delivered with standard radiation for pelvic, GI, spine and brain tumors do not require hypofractionation notes.
•	This policy excludes standard palliative or prophylactic radiation treatments delivered with convention 3D conformal radiotherapy or IMRT/VMAT that are not considered SBRT or SRS. Thus, excluded from this policy are “quad shots” of 14.8 Gy in 4 fractions delivered BID over 2 days, and 7 or 8 Gy in 1 fraction.
•	Any treatment that delivers more 5 Gy or more per day to a previously irradiated area requires a hypofractionation note, including “Quad shots”, 25 Gy in 5 fractions, or 7 or 8 GY in 1 fraction.
•	The attending radiation oncologist must review the case with a co-signing attending physician. This review should take place after volumes and prescriptions are approved but prior to treatment planning.  The hypofractionation note must be signed prior to the first treatment.
•	Final treatment plans will be reviewed at the weekly new patient conference.  Please note that because large fraction sizes are routine in the setting of brachytherapy, this policy will not apply to brachytherapy cases.
•	Intracranial SRS performed using gammaknife or linear accelerator that has a neurosurgeon involved in the case is exempt from this policy as long as the neurosurgeon is involved in the target delineation and treatment planning.  The neurosurgeon will document his/her involvement in a note in UCHART.
**SBRT 5Gy/fx need hypo note; IMRT 5Gy/fx doesn't need it.

## Protocol
Protocol page will be selected on the physician’s order. Upon CT imported we need to add the comment on dosimetry task “protocol submission needed or so” and start collecting the protocol (email MD to ask for it) and add it to documents. Also contact MD/physics before planning if any questions arrive. The plan needs to be done on time so that they can sent protocol and get everything ready. 
Once plan is ready you can review with physics also so that both goes over structures name, etc. 
### Physcis Protocol Assignment list
Site		Primary			Secondary
GU			Siamak			Kyle
GI			Levent			Siamak
Gantry		Joseph both		Matt Studenski
Breast		Garret			ROBERT
Brain/Spine	Irene			Beth Bossart
HN			Svetlana Denissova	Fei Yang
Lung/Thorax	Rod				Chet ford
JMH			Alberto Zerda	Levent
Proton		Michael			ROBERT

# replan
----move to another machine---- pt ID: 23894074
Copy ENT and paste as ENT_22TXD (means treated), change the fx as 22
Copy ENT and paste as ENT_13New, change the fx as 13, rc any field - Change Treatment Units - click No??? - Select Machine; if not allowed, delete all MLCs, and then change the machine
	Change the correct couch @@@@@@@@@@@@@@@@@
	Choose ENT_22TXD as base plan, and re-optimize
Insert a Plan Sum, run ClearCheck (don't need to change anything)
Plan Parameters:
	Window - check 'Context Window'
	rc ENT_Oral - Plan Approval - Completed Early
PTV_low_reference_point is empty in Ex Plan:
	either Plan Parameters - enter the dose number if blank, eg. 'Dose to PTV_5950_ENT: 170.0cGy' have four arcs and it is empty, then input 42.5 for each arc.
	... or Reference Points - down arrow of PTV_low_reference_point - Edit - input 42.5 for each arc.
Reference Point: don't need to change anything
Add a journal: The patient became inpatient in West and the plan was re-optimized using the Edge machine for the remaining 13 fractions. - Xueyan Lu
F4
run Aria report w/o errors


Create a new verification plan under the same old C1_PD
RadCalc for the ENT_13New plan
Carepath
	FYI - Owner: Dosimetrist - 120524 XUEYAN LU replan
	Review Treatment Plan - Owner: Dr. Kubicek
	Print Isodose Plan - Owner: Dosimetrist - 120524 XUEYAN LU Print new plan
	// Add - Add Task... - Resource/Staff choose Dosimetrist, Activity choose 'Treat Approve Replan'??? - OK - mark it completed after MD approval ??
	// ... - Drag 'SCCC West - New Start VMAT/IMRT' (make sure it is West, not Miami; if not: Summary - click 'SCCC Miami' in Primary Hospital - change to 'SCCC West') - ...

----difference for the resim situation----
Check OAR contouring, may need to delete all of them and use autocontour from scratch
Aria report
	ENT_11New: scale PTV from 7000 to 2200 in CC, scale all OAR constraints too. Print it.
	Plan_Sum: delete PTV constraints and leave OARs only. Uncheck all sub-plans. Print it.

---replan due to removing GTV----
MRN 22000013
1. change Rx to 2 Rx:
	Rx (PTV7020 and GTV7720): 17 fractions; note: 17 fractions treated using PTV7020 (dose of 4590cGy) as well as GTV7720 (dose of 5047.7 cGy). Keep all OAR constraints. Keep the PTV name, such as PTV7020_ProstateSV.
	Rx (PTV7020): 9 fractions; note: Remaining 9 fractions using only PTV7020 due to increasing urinary issues. Keep all OAR constraints. Keep the PTV name, such as PTV7020_ProstateSV.
2. Copy the old prostate as 17 TXD; New a prostate_new plan with 9 fractions, use the PTV7020 reference point only (remove the GTV7720 ref point).
3. Plan Sum
4. Complete the old prostate completed early, ...., just as other replan cases do.

----billing--
If not change, check 00002-Isodose Plan - NO CHARGE




# Records Release Rotation
Request Patient DICOM from other hospitals
	Physician's Order says Specical physics consult needed, Prior history of RT as MSKCC satellite in New Jersey. EQD2 calc.
	Ask UM MD whether DICOM has been requested yet, he said no. His physician assistant gave the dsmt MSKCC MD's name and location. Dsmt googled and called the office.
	Dsmt filled in a Provider to Provider Release of Information for Treatment Purposes form:
		DICOM records (preferred)of radiation treatment plan including: CT planning Images, DVH, setup and treatment fields, daily and total dose, number of fractions.  PDF of End of treatment summary note. 
		... We can provide a safe records sharing link. Please email at contact: Katherine Gomez krg110@miami.edu.  305-243-4525.
	MSKCC office needs a patient record release, so email UM MD to request if from patient's authorization:
		Title: Patient record release needed (MRN 22466980) Body: Hi Dr. Mahal, We need the patient record signed by the patient to obtain DICOMS. I spoke with an office coordinator from MSK, 
			... and she said the patient can also give a verbal authorization. The patient can call the number 646-608-2450 and speak with Vianna only. Please advice as soon as possible. Thank you, XXX. 
			... A screenshot of the Physician's Order with 'the Special physics consult needed' highlighted is attached.
Amber or Box or fax
	Hayden uses Amber

Send Patient DICOM to other hospitals
Click the course or plan ??? - File - Export - ... - W:\PHYSICS\TEMP IMAGE STORAGE, new a folder MARIA_XXX_01021965 - Override Options - check 'Planning images' and 'Planning structure set' - OK
Document - 'End of Treatment Chart Closeout' - save as pdf - to the save folder above (W:\PHYSICS\TEMP IMAGE STORAGE\MARIA_XXX_01021965)
W:\PHYSICS\TEMP IMAGE STORAGE - zip MARIA_XXX_01021965
Log in UM Box - Create a New Folder - upload the zip file - add the receiver's email address - add a message: Please find zipped files. Let us know if you have any questions or any issues downloading both files - Send

Good morning William, 
My name is Jacqueline Canut and I am an intake coordinator for Radiation Oncology at the Miami Cancer Institute. I am reaching out to you in efforts of obtaining some radiation records for a mutual patient. 
... My colleague Ericka Guido has shared your email with me in hopes for assistance with these records. Above I have attached the request form with what we are looking for along with the ROI from the patient. 
... Please let me know if you are able to assist or have any questions or concerns. Thank you so much and I look forward to hearing back from you. This patient is scheduled to come in early next week so it is 
... a STAT request. Wishing you a very happy holiday season! 
Best, 
Jackie 

Upon requests from other hospitals
	Email: Hope all is well. I will be helping with the records request. Can you plz send us an Ambra link to upload the requested DICOMS?
	Open 'RT Summary', check different courses, empty means no treatment
	Eclipse - rc plan - export - override: check 'Planning images' and 'Planning Structure Set', Dose: choose 'plan'.
	Documents - export 'Phy.EOT summary'.
	Upload these two to the Amber link

Import DICOM from other hospitals
Learn from Beth: Eclipse, new an initial plan without any field (cancel the field window), import the initial dose (not the plan), calculate??; new a boost plan w/o any field, import the boost dose, calculate??
Learn from Irene:
	MIM
		import: (check Use Classic Patient List) - click 'Import from CD or other source' at the lower left corner - click Browse - click W drive path, only select the folder - Import All - (check all images) - Import - click 'Newly Received' to see whether imported
		change patient ID: rc all images - rc - correct ... - input the correct Patient ID value.
		open the Dose file - click Dose - got the dose number 27.42 Gy(Max)
		export all images to Eclipse
	Eclipse
		import CT firstly
		File - Import - Dose Distribution... - select RD file in W drive - a window showing 'Set 100% Relative Dose to 2741.9cGy', check the number is the same as the one in MIM - rename the plan as PrevTx_2022.

-------------------------------------------------------
import images:
Mondays- Rene
Tuesdays-Jon
Wednesdays- John B.
Thursdays- Boris
Fridays- Emma



# Ethos Adaptive
MRN 10365810
24042953
23941778 IM109 is good but low dose 50% IDL not conformal.
Eclipse
	crop CTSim, only leave PTV with 5 - 12 cm sup/inf area
		In Selection, highligh image Series ID - Change Patient Position - check 'Assign a new frame of reference' (keep original patient position) - OK
		... - Drag the new series - Delete superior images and inferior images - rc on any of the images in gallery and select New 3D image named Pelvis_122624_Cr
		... - Fuse the images of the old one to the new one (check the option 'register based on DICOM origin') and copy the structures over (if a window prompted with asking about Body, click skip)
	check MRI fusion and PET fusion, decide both of them are helpful and will drag them later in ethos (Do not need to register MRI or PET to the new one)
	check how many margin of PTV from CTV: 3mm
Ethos
	Page 31. select correct tx region according to OARs in Rx, very important due to enfluences.
	check 'Adaptive Treatment'
	Delete useless OAR but not Bones due to high density, and not delete Body as well
	Add OARs CaudaEquina and PenileBulb since they are in eclipse's OAR structures. DO NOT use 'General ?? Tissue' but use the correct structures such as CaudaEquina
	Contours
		rc the down arrow button of PTV3000_LN - 'Change Auto Margin/Combination...' - click Combination - check CTV3500_LN, fill 0.3cm at margin - click the sigma botton
		Fix all alarms, such as:
			1. bladder overlapps with rectum (click Bladder - click eraser icon - fix the overlapping area slice by slice)
			2. bladder misses some slices (click Bladder - clike brush icon - rc - select Static Brush - contour missing bladder)
		Attach PTV and OARs
		DO NOT attach Body, because we use the one generated by Ethos not by Aria.
	Dose Preview
		click Dose Preview - click Refine Dose
		Organ		Rx			Goal in Ethos	Variation in Ethos
		opti_GTV4000_LN
		Bowel		V1950cGy < 5cc		V1950cGy < 4cc	V1950cGy < 5cc
		Bowel		V3000cGy < 0.1cc	D0.1cc<2900cGy	D0.1cc<3000cGy (if <= 1cc, then use Dxx < xxcGy instead of Vxx < xxcc)
		Bladder
		GTV4000_LN	V100% > 95%		V86% > 98%	V86% > 95%
		CTV3500_LN	V3500cGy > 95%		V100% > 98%	V100% > 95%
		GTV4000_LN	Dmax<115%		Dmax<114%	Dmax<115%
		PTV3500_LN	V3000cGy > 95%		V86% > 98%	V86% > 95%
		!! PTV5000_Pancress goal is V5000cGy > 98% but the variation should be 80% as in Rx.
		
		Rectum
		Femur L
		Femur R
	During optimization
		Bowel is too good, so Olga changed it to: 						V1950cGy < 5cc	V1950cGy < 5.1cc
		New a GTV named opti_GTV4000_LN, it = GTV4000 - (Bladder + 0.6cm) -(Bowel + 0.6cm): 	V100% >= 98%	V100% > 95% Priority: R-Report Value Only
			!!! default automated margin is 0.3 cm, so always use >= 0.4 cm margin if you need to add a margin manually
		PTV3500_LN:										V86% > 99%	V86% > 95%
		PTV3500_LN										Dmax0.03cm3<=140%
Pick plan
	MU: if BH, prefer 7 fields rather than 9 or 12, also prefer low MU, all due to quick delivery. 800 MU/min, 4000 MU means 5 min, it is quick.
	isocenter replacement: less sensitive, more robust and better
	conformality, esp 50%IDL.
After MD approval in Ethos
Ethos
	Plan Report - check and let physics know if any warning or error - if not, click Export Report - Save to W:\ECLIPSE PLANS\Ethos Adaptive\Rubin, Israel_IM109 @@@@@@@@@@@@@@@@@@@@@@@@@@
	... - name as Plan Report IM109 this is equivelant to the Treatment Plan report
	click DICOM Export to File - save in to W:\ECLIPSE PLANS\Ethos Adaptive\Rubin, Israel_IM109.zip @@@@@@@@@@@@@@@@@@@@
	click DICOM Export to Receiver (SCP) - ... - Calculate - save the zip in W:\Public\ArcCheck\2025 Patient QA\Reynoso, Omar IM109_QA, unzip and leave RD and RP files.
Mobius3D (equivelant to RadCalc)  @@@@@@@@@@@@@@@@@@@@@@
	10.64.80.211
	save the report in W:\ECLIPSE PLANS\Ethos Adaptive\Mobius
Eclipse
	File - Import - select W:\ECLIPSE PLANS\Ethos Adaptive\Rubin, Israel_IM109 ?? - import all CT, RTDose, RTPlan, and RTStruct
	select Physical Material Table as AcurosXB-13.5
	delete Couch and insert a correct ethos couch
	Calculation model: 
		Volume Dose: 			AcurosXB_1610, 
		DVH Estimation: 		DVH Estimation Algo [16.1.0], 
		Optimization: 			PO_1610, 
		Irregular Surface Compensator: 	PO_1610, 
		Portal Dose: AAA_1610
	Calc
	insert setup fields or imaging setup fields, DRR, and Reference points ( no need for RC point since all tx will be in Ethos, everything in Eclipse is only for tracking)
	Approve the plan in Eclipse
Documents
	import Mobius report, Document Type: Phy-MU Check, Template Name: M3D IM109
	import 'Plan Report IM109', Document Type: Treatment plan
	new a Document 'MD Ethos Adaptive SBRT Procedure Note'(or the IMRT one) - do not need to change anything - OK - change supervised by primary MD
	new a Document 'Hypofractionation Co-Signature Note' if SBRT
Carepath: new Ethos Adaptive Dosimetry???
Ethos: setup phots
Aria: Treatment Preparation: schedule???
if BH:
	send structures from Eclipse to Identify
Rx
	note: 
"SBRT
Ethos adaptive
Isotoxic planning
PTV = CTV + 0.3cm

Priorities:
Bowel
Bladder
GTV
CTV
PTV
Rectum
Femur"

Bowel_loop: very tight
Bowel_bag: loose, big bowel bag
GTV and CTV: MD draws them for every fx
PTV: draw it from CTV by extending

## Technical Plan Report
If the mean dose of PTV is 125% of the PTV Rx dose, then it gives a warning;
Other if 150%, then the plan is interlocked and won't treat, you need to play with the number, such as V86%>95% instead of V100%>95%.




# code
install git in Windows command
	winget install --id Git.Git -e --source winget