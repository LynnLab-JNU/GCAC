
Table 2: Tools Task Description
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

+------+---------------------------+------------------------------------------------------------+
| S.N. |    Tool Name              |            Description                                     |
+======+===========================+============================================================+
| 1.   | PaDEL-Descriptor          | tool calculates descriptors for active and                 |
|      |                           | inactive datasets.                                         |
+------+---------------------------+------------------------------------------------------------+
| 2.   | Merge-Activity-Files      | tool assigns response values and merges                    |
|      |                           | positive and negative datasets.                            |  
+------+---------------------------+------------------------------------------------------------+
| 3.   | Remove-Redundant-Entries  | tool removes redundant entries of moleclues.               |  
+------+---------------------------+------------------------------------------------------------+
| 4.   | CSV-2-RData               | tool converts csv_files to RData format.                   |
+------+---------------------------+------------------------------------------------------------+
| 5.   | Build-Classification-Model| tool build classification model using 'caret' R package.   |
+------+---------------------------+------------------------------------------------------------+
| 6.   | Predict-Activity          | tool predicts activity of molecules using their descriptor |
|      |                           | file (prediction set) and supplied model.                  |       
+------+---------------------------+------------------------------------------------------------+
| 7.   | Select-Candidate-Molecules| tool selects compound name or ids  of interesting          | 
|      |                           | molecules based on certain cutoff range.                   |
+------+---------------------------+------------------------------------------------------------+
| 8.   | Extract-Compound-IDs      | tool extracts compound IDs to be used in downstream        |
|      |                           | compound extraction from sdf files.                        |
+------+---------------------------+------------------------------------------------------------+
| 9.   | Extract-From-SDF-Files    | tool provides sdf file of extracted compounds from         |
|      |                           | the prediction set.                                        |
+------+---------------------------+------------------------------------------------------------+
