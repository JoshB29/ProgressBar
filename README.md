# ProgressBar
Progress Bar for Loops in Python

This code allows for easy creation of progress bars in loops in python. For example
    
    progress = ProgressBar(len(range(0,10000)), fmt=ProgressBar.FULL)
    for i in range(0,10000):
      #do stuff in the loop
	   progress.displayProgress()


 Note this code is mostly not my own; I took it from  https://stackoverflow.com/a/36985003/3923510, and created the method `displayProgress`.
