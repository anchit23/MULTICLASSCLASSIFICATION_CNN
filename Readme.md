# MULTI TASK MULTI CLASS CLASSIFICATION
## DATASET
	20,000+ face images with annotations of age, race and gender. Provided in cropped or uncropped format.
	Images cover large variation in pose, facial expression, illumination, occlusion, age(0-116 yrs), resolution, etc.

### LABELS
	[age] is an integer from 0 to 116, indicating the age
	[gender] is either 0 (male) or 1 (female)
	[race] is an integer from 0 to 4, denoting White, Black, Asian, Indian, and Others (like Hispanic, Latino, Middle Eastern). [date&time] is in the format of yyyymmddHHMMSSFFF, showing the date and time an image was collected to UTKFace	

## FEATURE ENGINEERING
	Utilized openCV library to read images and convert them into a matrix (23708x64x64) with 3 RGB channels
	I decided to bin the values within the Age variable into children(1-14), youth(14-25), adults(25-40), middle-age(40- 60) and old(60+)

## 	MODELS
## 		1. NEURAL NET MODEL
##		2.CNN MODEL
##		3. TRANSFER LEARNING
 