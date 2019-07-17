# Electoral-Fraud-Detection

This project contains set of trained weights which can detect Human and an Election Booth. It can also be used as a Person Identifier along side only election booth identifier. Project contains a Weights file which is compatible with Darknet Framework and its been trained on YOLOv3 for 2000 iterations. Training set consisted of CCTV footage of actual Indian Election Voting Room. It has been labelled manually using labelImg which can be found at https://github.com/tzutalin/labelImg.

Due to the constraints of GitHub, I cannot upload weights file in the repo. So, I decided to upload them on Google Drive instead, you can go through this link : https://drive.google.com/open?id=1GtZ3yb-SDUOxAx7lWGpHo7LYE8xQMw2I to view and download those weights for your purposes.

There is a test.png which is a snapshot from a tested video, Unfortunately I cannot share the whole video, but I can share a snapshot from that tested video. As it can be seen that if the Booth is in direct LOS of the camera, detection works pretty fine, same goes for the person detection. Sorry for the low-res video but all the videos that I had for test and train were indeed low-res, image is also a bit blown out but you got the point anyhow.


