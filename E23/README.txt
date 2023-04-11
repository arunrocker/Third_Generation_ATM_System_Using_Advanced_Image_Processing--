STEP 1 : Install Python version 7 or later

STEP 2 : After installing python install the following libraries in python
	# pip install -r requirements.txt

	# base ----------------------------------------
	Cython
	matplotlib>=3.2.2
	numpy>=1.18.5
	opencv-python>=4.1.2
	Pillow
	PyYAML>=5.3.1
	scipy>=1.4.1
	tensorboard>=2.2
	torch>=1.7.0
	torchvision>=0.8.1
	tqdm>=4.41.0

	# logging -------------------------------------
	# wandb

	# plotting ------------------------------------
	seaborn>=0.11.0
	pandas

	# export --------------------------------------
	#coremltools==4.0
	#onnx>=1.8.0
	scikit-learn==0.19.2  # for coreml quantization

	# extras --------------------------------------
	#thop  # FLOPS computation
	#pycocotools>=2.0  # COCO mAP

	# ui------------------------------------------
	pyqt5 # ui

STEP 3 : Download anaconda 3 and configure it to your system
	https://repo.anaconda.com/archive/

STEP 4 : Copy the source code to a new folder(eg: atm-code)

STEP 5 : Create a new folder inside the atm-code folder and name it as users and one more datasets

STEP 6 : Open Anaconda Prompt and change the directory to the users folder(eg: cd C/Users/Desktop/atm-code)

STEP 7 : Create another folder inside atm-code and name it as create users to store user data

STEP 8 : Inside data store the image that you want to  and it should be in jpg format(eg: 1.jpg)

STEP 9 : Running the project:
		-> Open Anaconda prompt and change the directory to the Human-Rescue folder
			# cd C/Users/Desktop/atm-code
		-> Then type the run command with the input you want detect
			Run python create_data.py for registrating the user's data
				NOTE : *data/1.jpg refers to the input video which has been converted to jpg
		->To use face detection run command python face_recognize.py to detect the user whether he is authenthicated or not.