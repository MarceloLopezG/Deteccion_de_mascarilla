# Deteccion_de_mascarilla

<< Creamos una carpeta llamada mascarilla >>

mkdir mascarilla
cd mascarilla

python pip install -m -upgrade pip  OR  python -m pip install -U pip
pip install tensorflow==2.0.0
pip install Keras
pip install imutils
pip install numpy
pip install opencv-python
pip install matplotlib
pip install argparse
pip install scipy

pip freeze > requirements.txt
pip install -r requirements.txt
----------------------------------------------------------------
<< Una vez instalados crearemos el entorno Virtual >>
----------------------------------------------------------------
<< Dentro de la carpeta mascarilla creamos el entorno virtual >>

python -m venv mascarilla

<< Una vez creado el entorno lo vamos a activar >>

source ./mascarilla/Scripts/activate   -> Salta este paso funciona sin activarlo.
python -m   pip install django
pip install sklearn
pip install Pillow
pip freeze > requirements.txt
pip install -r requirements.txt

--------------------------------------------------------------
python -m pip install –-upgrade pip setuptools   (opcional -> Te aconsejo que no lo hagas si no te pide)
--------------------------------------------------------------

python train_mask_detector.py --dataset dataset
python detect_mask_video.py


