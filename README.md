# Repo usage
1. [__TextTest.exe__](/TextTest_exe/): out-of-box test app, there're several versions online, but this version is surely able to get correct format .CSV data analysis files.
2. [__TextTest source code__](http://depts.washington.edu/madlab/proj/texttest/TextTest.zip): if you want to adapt the test app to your own use case (like derandomize example sentence order, customize app GUI to create realistic scenario like conversation).
3. (optional) [__Interactive data analysis GUI__](/InteractiveDataAnalysis/): [install Jupyter Notebook](http://jupyter.readthedocs.io/en/latest/install.html), then follow the instructions on [README.md](/InteractiveDataAnalysis/README.md)

# Test process & results interpretation
![](TextTest_sampleScreenshot.png?raw=true)
1. Make TextTest app up and running, either out-of-box app or adapted version.
2. Have test participant transcribe sentences in the app
3. From resulting .xaml files, use app menu 'Analyze' --> 'Logs' -> choose your .xaml files --> 'Main measures for each trial (*.CSV)', export analysis files
4. Now you may do you own analysis, or use interactive data analysis 


#### Reference
Wobbrock, J.O. and Myers, B.A. (2006). [Analyzing the input stream for character-level errors in unconstrained text entry evaluations](http://faculty.washington.edu/wobbrock/pubs/tochi-06.pdf). ACM Transactions on Computer-Human Interaction 13 (4), December 2006, pp. 458-489.