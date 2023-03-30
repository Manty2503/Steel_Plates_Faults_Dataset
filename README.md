# Steel_Plates_Faults_Dataset

Given the Steel Plates Faults Data Set as a csv file (SteelPlateFaults2class.csv). This dataset comes from research by Semeion, Research Center of Sciences of
Communication. The original aim of the research was to correctly classify the type of surface
defects in stainless steel plates, with six types of possible defects (plus "other"). The Input vector is
made up of 27 indicators that approximately describe the geometric shape of the defect and its
outline. As Semeion was commissioned by the Centro Sviluppo Materiali (Italy) for this task and
therefore the details of the nature of the 27 indicators used as input vectors or the types of the 6
classes of defects are confidential.

The dataset used for this assignment contains features extracted from the steel plates of types A300
and A400 to predict whether the image of the surface of steel plate contains two types of faults such
as Z_Scratch and K-Scratch. It consists 1119 tuples each having 27 attributes which are indicators
representing the geometric shape of the fault. The last attribute (28th attribute) for every tuple
signifies the class label (0 for K_Scratch fault and 1 for Z_Scratch fault). It is a two-class problem.

Attribute Information:

The fault description is constituted by 27 indicators representing the geometric shape of the fault
and its contour.
*  X_Minimum
*  X_Maximum
*  Y_Minimum
*  Y_Maximum
*  Pixels_Areas
*  X_Perimeter
*  Y_Perimeter
*  Sum_of_Luminosity
*  Minimum_of_Luminosity
*  Maximum_of_Luminosity
*  Length_of_Conveyer
*  TypeOfSteel_A300
*  TypeOfSteel_A400
*  Steel_Plate_Thickness
*  Edges_Index
*  Empty_Index
*  Square_Index
*  Outside_X_Index
*  Edges_X_Index
*  Edges_Y_Index
*  Outside_Global_Index
*  LogOfAreas
*  Log_X_Index
*  Log_Y_Index
*  Orientation_Index
*  Luminosity_Index
*  SigmoidOfAreas

