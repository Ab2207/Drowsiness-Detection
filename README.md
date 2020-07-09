cam = cv2.VideoCapture("/Users/AB/Desktop/0.mp4") -- In this line of code, give the path to your video.

  if not os.path.exists('drowsiness_data'): 
        os.makedirs('drowsiness_data') -- This piece of code will check for folder with name 'drowsiness_data' in your local machine, if not available a folder will be created
                                          and all images will be saved there. 
