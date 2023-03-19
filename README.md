# TW_Finch_for_general_video
Applying the classic TW-Finch hierarchial clustering to any general video 

## How to segment any video
1. Download the video you want to segment and place it in the same directory as the python scripts
2. Install the dependencies via the command : pip install -r requirements.txt 
3. Run the **extract_frames_features** notebook after following the instruction mentioned in the columns
4. If ground truth is known and you want to evaluate the performance of the segmenting run the **test_with_groundtruth** notebook after follwing the instructions mentioned in the comments
5. If ground truth is not known run the **test_without_groundtruth** notebook to get the appropriate number of clusters and then use any of those values to get the appropriate transition frames

## Evaluation of a sample file
1. Download the video : "https://www.youtube.com/watch?v=tA42nHmmEKw&list=PLh2mXjKcTPSACrQxPM2_1Ojus5HX88ht7&ab_channel=NPTEL-NOCIITM"
2. Rename it to "Video_1" and place it in the same directory as the python notebooks
3. Run the extract_frames_features and then the test notebooks without changing anything to get the results
