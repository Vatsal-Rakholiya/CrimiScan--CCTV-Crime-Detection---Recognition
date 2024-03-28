#CrimiScan: CCTV Crime Detection & Recognition
In numerous instances, surveillance recordings capture criminals, yet due to technological limitations and manpower shortages, authorities remain unaware of these sightings, allowing wanted individuals to evade justice.

Our solution addresses this critical issue with the following features:

1. Identification of criminals in video recordings based on uploaded images.
2. Detection of criminals in video clips for investigation.
3. Matching individuals against a database of known criminals, aiding in identifying affiliations such as gang memberships or terrorist groups.

Technologies employed include Python, Deepface, and OpenCV. Future enhancements will include partial facial recognition and the use of LSTM for crime prediction.

Project Objectives:
1. Precise Identification:
   - Matching individuals to images and video clips.
   - Identifying known criminals and their affiliations.
2. Live Recognition.
3. Automation for routine identification tasks.

Dataset Utilization:
Our current dataset, created in-house, serves as a testing ground. We aim to acquire real-world footage from cyber-cell databases for practical implementation, focusing on footage from society-installed cameras, albeit pixelated due to lower resolutions.

Results:
Through rigorous experimentation, models such as FaceNet, VGG-Face, ArcFace, and Dlib have demonstrated exceptional performance, leveraging transfer learning from datasets like Labeled Faces in the Wild (LFW) and YouTube Faces in the Wild (YTF) to achieve high accuracies.
