# Anaconda-Installation-Setup
## How to set Customs Path/Folder in Anaconda for Jupyter Lab/Jupyter Notebook
Youtube Tutorial : https://www.youtube.com/watch?v=U4p5hlN1H78


## 				---------------**Jupyter Lab** ---------------------
![image](https://user-images.githubusercontent.com/87929992/187691948-b4d7832a-3498-4f89-aa96-1601082dd508.png)

1. Open Conda(Promt) or cmd
2. $ jupyter lab --generate-config
3. . jupyter_lab_config.py should be created in dir /home/$USER/.jupyter directory.

	
	![image](https://user-images.githubusercontent.com/87929992/187690550-0554bb3e-6ea2-44e5-b0df-6abafd2653c1.png)


4. Open  **jupyter_lab_config.py** in any Editor
5. 	Search for	-	notebook_dir

	
	![JupyterLab](https://user-images.githubusercontent.com/87929992/187690657-d48f4013-c515-434e-bb5f-36bff7c2f936.PNG)


6. Copy your path 	
	add your desired path and uncomments it 
F:\New Path	to 	F:/New Path/
change \ to /

ie.	c.ServerApp.notebook_dir = 'F:/New Path/'

7. Save it
Open Again Jupyter Lab from Anaconda or Refresh
	![image](https://user-images.githubusercontent.com/87929992/187694735-76180e79-8009-4ea5-9521-ccf6fb0c0836.png)


## 					-------**Jupyter Notebook**--------
![image](https://user-images.githubusercontent.com/87929992/187692091-1c9253c3-659d-4e37-97b8-6f2164bc43ad.png)

1. Open Conda(Promt) or cmd
2.  	$ jupyter notebook --generate-config
3. . jupyter_notebook_config.py should be created in dir /home/$USER/.jupyter directory.
	![image](https://user-images.githubusercontent.com/87929992/187691031-7318a92e-fa1b-410f-9650-df4fd5683f11.png)
	

2. Open **jupyter_notebook_config.py**	in any Editor
3. 	Search for	-	notebook_dir
	![JupyterNotebook](https://user-images.githubusercontent.com/87929992/187691129-b4782b71-3da6-45c8-af87-953c36507846.PNG)

4. Copy your path

	add your desired path and uncomments it 
F:\New Path	to 	F:/New Path/
change \ to /

ie. -	c.NotebookApp.notebook_dir = 'F:/New Path/'
	![image](https://user-images.githubusercontent.com/87929992/187694571-b059abba-5efd-4efc-a6a3-26c43638986e.png)
	
