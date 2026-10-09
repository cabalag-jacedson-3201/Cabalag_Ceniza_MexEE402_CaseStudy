# MexEE 402: Data Preprocessing Case Study

MexEE Elective 2: Data Science and Machine Learning
Batangas State University, Alangilan Campus
1st Semester, AY 2026-2027

## Members

| Name | Student Number | Section |
|---|---|---|
| Cabalag, Jacedson | 23-00967 | MEXE-4101 |
| Ceniza, Janzen | 23-06972 | MEXE-4101 |

## Notebook links

| Chapter | Link |
|---|---|
| Ch1_2_3 | [[link]()](https://colab.research.google.com/drive/15IVEx_MofeanXX0Vd3QmqI_i2WoSE4Mz?usp=drive_link) | 
| Ch4 | [[link]()](https://colab.research.google.com/drive/1AafrTMlYitcWsELasJggrhna3d_dRh4b?usp=drive_link) | 
| Ch5 | [[link]()](https://colab.research.google.com/drive/1xqifnmPTmXgWoCgeRiJdzHRYHLNOba6d?usp=drive_link) | 
| Ch6 | [[link]()](https://colab.research.google.com/drive/1sggC3YY-clOb_GgvhsLTEp70K487N7wm?usp=drive_link) | 
| Ch7 | [[link]()](https://colab.research.google.com/drive/1HCfMkEx-rXrRG-ceW4nPuOtHiCv21B_1?usp=drive_link) | 
| Ch8 | [[link]()](https://colab.research.google.com/drive/1rKXW88rDxsfEFZGlW2IEzZeXWx3EouSf?usp=drive_link) | 
| Ch9 | [[link]()](https://colab.research.google.com/drive/1ikeO9F0X2se_fuGhfWl5iVehr9eV5JfY?usp=drive_link) |

## What We Learned

<table align="center" width="100%">
  <thead>
    <tr>
      <th align="center" width="25%">CHAPTERS</th>
      <th align="center" width="75%">LEARNING</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><strong>CHAPTER 1</strong></td>
      <td><p align="justify">I discovered that preprocessing largely involves cleaning up unrefined, disorganized data to ensure the remainder of your work operates effectively. I was surprised to learn that a significant portion of a data project is dedicated to correcting errors and addressing missing values instead of developing intricate models.</p></td>
    </tr>
    <tr>
      <td align="center"><strong>CHAPTER 2</strong></td>
      <td><p align="justify">I discovered that in order to determine the formats and values you are working with, you must first examine the structure of your dataset. The ease with which minor details, such as a year stored as a decimal, can result in errors in your code if you overlook them early on surprised me.</p></td>
    </tr>
    <tr>
      <td align="center"><strong>CHAPTER 3: CLEANING DATA</strong></td>
      <td><p align="justify">I gained knowledge about handling missing data, including how to eliminate incomplete rows and use averages to fill in blanks. I was shocked to learn that eliminating extreme outliers actually improves the accuracy of your analysis as a whole.</p></td>
    </tr>
    <tr>
      <td align="center"><strong>CHAPTER 4: TRANSFORMATION OF DATA</strong></td>
      <td><p align="justify">I realized that in order for algorithms to perform fair comparisons, they require numerical data on consistent scales. The ability to combine current features to create completely new columns that provide the model with better context surprised me.</p></td>
    </tr>
    <tr>
      <td align="center"><strong>CHAPTER 5: CHOOSING FEATURES</strong></td>
      <td><p align="justify">I discovered that retaining every bit of data can slow down your process and add pointless noise. The number of unnecessary columns that can be eliminated without compromising the main point surprised me.</p></td>
    </tr>
    <tr>
      <td align="center"><strong>CHAPTER 6: UNBALANCED INFORMATION</strong></td>
      <td><p align="justify">I observed how a model is tricked into favoring the majority response when a dataset is dominated by one outcome. It surprised me that a model with high accuracy could still be worthless if it consistently guesses the same outcome.</p></td>
    </tr>
    <tr>
      <td align="center"><strong>CHAPTER 7: SPLITTING DATA</strong></td>
      <td><p align="justify">I discovered that in order to assess actual performance, training and testing data must be kept apart. The speed at which a model can commit particular data points to memory rather than discovering the underlying patterns shocked me.</p></td>
    </tr>
    <tr>
      <td align="center"><strong>CHAPTER 8: PIPELINES</strong></td>
      <td><p align="justify">I discovered that pipelines combine all of your preparation and cleaning procedures into a single, efficient workflow. The ease with which testing data can infiltrate your training set if those procedures are done by hand surprised me.</p></td>
    </tr>
    <tr>
      <td align="center"><strong>CHAPTER 9: MODEL EVALUATION</strong></td>
      <td><p align="justify">I found that a model's high accuracy does not guarantee proper operation. How easy it is to declare a project successful when it is actually making significant errors on the most crucial metrics surprised me.</p></td>
    </tr>
  </tbody>
</table>

## Errors We Found

### Chapter 6 – Outlier Detection
- The outlier detection result does not display the value `100` as expected.

### Chapter 7 – Feature Selection Using RFECV
- The feature selection process produces repeated `UndefinedMetricWarning` messages because the R² score is not well-defined with fewer than two samples.
- The output selects `assignments completed` as the feature.

### Chapter 9 – Discretization
- There appears to be a reversal or inconsistency in the discretization results.


## Note on AI Tools

- **Grammarly** was used in some cases to improve sentence structure and grammar.
- **Gemini** was used to help us better understand how scalers and filters work.
- **ChatGPT** was used to help us understand the overall program, including its code, functions, and the purpose of each step.

## References

McKinney, W. (2021). Python for Data Analysis, 3rd ed. O'Reilly.
VanderPlas, J. Python Data Science Handbook.
Any other page or article you used.
