# WEDA-FALL
WEDA-FALL - Wrist Elderly Daily Activity and Fall Dataset. A fall-related Dataset captured at 50Hz using a smartwatch on the wrist, containing Elderly People Data.

The device used to compile this dataset is the [Fitbit Sense](https://www.fitbit.com/global/be/products/smartwatches/sense). This dataset was compiled using the [Fitbit Gather Data Mechanism](https://github.com/joaojtmarques/FitbitGatherDataMechanism). One can use this tool to gather more data and expand this dataset.

## Description of the Datasets’ movements

This dataset has compiled with two types of movements. Falls and ADLs (Activities of Daily Life).
A fall usually happens given a context and a cause. Having that in mind, the types of falls compiled in this dataset are detailed in Table 1.

### Table 1: Types of Falls selected for this work
| Code      |Activity   |
| :-----:   | :---:     |
| F01       | Fall forward while walking caused by a slip   |
| F02       | Lateral fall while walking caused by a slip   |
| F03       | Fall backward while walking caused by a slip  |
| F04       | Fall forward while walking caused by a trip   |
| F05       | Fall backward when trying to sit down         |
| F06       |  Fall forward while sitting, caused by fainting or falling asleep   |
| F07       | Fall backward while sitting, caused by fainting or falling asleep   |
| F08       | Lateral fall while sitting, caused by fainting or falling asleep    |


ADL selection was based on the frequency of real-life activities and similarity to fall movements that could generate False Positives. ADL choice had the position of the device in mind - the wrist - and its selection is detailed in Table 2.

### Table 2: Types of ADLs selected for this work

| Code      |Activity   |
| :-----:   | :---:     |
| D01       | Walking                      |
| D02       | Jogging                      |
| D03       | Walking up and downstairs    |
| D04       | Sitting on a chair, wait a moment, and get up   |
| D05       |  Sitting a moment, atempt to get up and collapse into a chair         |
| D06       | Crouching (bending at the knees), tye shoes, and get up               |
| D07       | Stumble while walking        |
| D08       | Gently jump without falling (trying to reach high object)         |
| D09       | Hit table with hand          |
| D10       | Clapping Hands               |
| D11       | Opening and closing door     |


## Participants Description

Falling is an issue that mainly affects elderly people. No previous wrist-based dataset provided Elderly People Data. This dataset does.
The groups of participants are, therefore, divided in two: Young Participants and Elder Participants. The statistics of each group can be found in Table 3 and 4, respectively. The combined statistics of this dataset is detailed in Table 5.


### Table 3: Statistics of Young Participants

| User_id   |Age    | Height (m)    |Weight (Kg)    |Gender     |
| :-----:   | :---: | :---:         | :---:         |:---:      |
| 1         | 22    | 1.76          | 56.3          | Male      |
| 2         | 22    | 1.78          | 56.0          | Male      |
| 3         | 20    | 1.73          | 69.5          | Male      |
| 4         | 21    | 1.70          | 57.1          | Female    |
| 5         | 23    | 1.67          | 59.6          | Male      |
| 6         | 22    | 1.67          | 69.0          | Male      |
| 7         | 21    | 1.78          | 68.1          | Male      |
| 8         | 23    | 1.62          | 61.0          | Female    |
| 9         | 22    | 1.70          | 52.0          | Female    |
| 10        | 23    | 1.83          | 77.0          | Male      |
| 11        | 23    | 1.69          | 61.8          | Female    |
| 12        | 23    | 1.78          | 64.5          | Female    |
| 13        | 22    | 1.79          | 66.0          | Male      |
| 14        | 46    | 1.84          | 83.0          | Male      |


### Table 3: Statistics of Elder Participants

| User_id   |Age    | Height (m)    |Weight (Kg)    |Gender     |
| :-----:   | :---: | :---:         | :---:         |:---:      |
| 21        | 95    | 1.70          | 71.0          | Male      |
| 22        | 85    | 1.53          | 62.0          | Female    |
| 23        | 82    | 1.60          | 60.0          | Female    |
| 24        | 81    | 1.52          | 63.0          | Female    |
| 25        | 81    | 1.73          | 72.0          | Female    |
| 26        | 83    | 1.75          | 85.0          | Male      |
| 27        | 89    | 1.71          | 71.5          | Male      |
| 28        | 88    | 1.57          | 52.5          | Female    |
| 29        | 77    | 1.60          | 65.9          | Female    |
| 30        | 80    | 1.79          | 72.0          | Male      |
| 31        | 88    | 1.63          | 53.0          | Female    |

### Table 4: Overall statistics of Participants

| Number of Males | Number of Females | Max - Min Age | Average Age | Max - Min Height (m) | Average Height (m) | Max - Min Weight (Kg) | Average Weight (Kg) | 
| :-----:   | :---: | :---:         | :---:         |:---:      | :---:      | :---:      | :---:      | 
| 13 | 12 | 20 - 95 |  50.48 |  1.84 - 1.52 |  1,699 |  85 - 52 |  66.3 |

The activities each Elder individual performed is detailed in Table 5. Note that Elder Participants were not asked to perform any Fall nor activities that could harm the individual, since it is impossible to assure their safety in these type of movements.


### Table 5: Activities Elder Participants performeds
| User id   |Activities performed |
| :-----:   | :---:     |
| 21 | D01; D04; D09; D10; D11;|
| 22 | D01; D04; D09; D10; D11;      |
| 23 | D01; D03; D04; D09; D10; D11; |
| 24 | D01; D03; D04; D09; D10; D11; |
| 25 | D01; D04; D09; D10; D11;      |
| 26 | D01; D03; D04; D09; D10; D11; |
| 27 | D01; D03; D04; D09; D10; D11; |
| 28 | D01; D03; D04; D09; D10; D11; |
| 29 | D01; D03; D04; D09; D10; D11; |
| 30 | D01; D03; D04; D09; D10; D11; |
| 31 | D01; D03; D04; D09; D10; D11; |



## Dataset Acquisition Conditions


First and foremost, it is important to denote that every fall movement was performed in a mattress to avoid the risk of injury. This work’s dataset is accompanied with [Videos](https://drive.google.com/drive/folders/1jB3W_sd4-aXkVRsRIdlSLDNdfaXizZ4a?usp=sharing) detailing the exact conditions of each movement.

Younger Participants were asked to repeat each activity three times. Fall F08 was asked to be repeated 4 times, where the first two the volunteer would fall towards the side of the watch, while in the last two he would fall to the opposite side. From YP alone, this dataset totals 350 (14 × 7 × 3 + 14 × 4) fall signals, and 462 (14 × 11 × 3) ADL signals. The number of epetitions each elder was asked to performed varied a lot, based on each volunteer’s mobility, comfort and fatigue. The total EP signals is 157, having on total 619 ADL Signals.

This dataset, that was acquired at 50Hz, also provides 4 more frequencies: 40Hz, 25Hz, 10Hz and 5Hz. These frequencies of data were obtained from the 50Hz frequency data. Both accelerometer, gyroscope and orientation sensor data were gathered in this dataset.

For the frequency of 50Hz, it is also provided de vertical acceleration.  Acceleration was projected on an inertial referential, where the previous z-axis value of acceleration now corresponds to the acceleration projected in the direction of the vertically upward vector, usually aligned with and opposite to the gravity vector.

Every filename in the dataset follows the following format: **_<user_id>_R<trial_counter>_<sensor_type>.csv_**, and is stored in a directory that identifies the movement, whose name is the code of each movement (see Table 1 and 2). The **_<user_id>_** distinguishes each volunteer, even though it does not identify them, since it is an abstract integer. The **_<trial counter>_** is the identifier of the trial of the movement since each movement was usually repeated more than once. For instance, the file **_dataset/50Hz/F07/U02_R03_accel.csv_** identifies the accelerometer readings with 50Hz for the third trial of fall number 7 (code F07) of the user with **_<user_id>_** = 2.






