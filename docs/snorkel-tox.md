```shell
(.venv) cwm@flxsa02:~/git/git.c-w-m/nlp_dev/src/snorkel-tutorials$ tox -e snorkel37
snorkel37 create: /home/cwm/git/git.c-w-m/nlp_dev/src/snorkel-tutorials/.tox/snorkel37
snorkel37 installdeps: 
    -rrequirements.txt, 
    -rgetting_started/requirements.txt, 
    -rspouse/requirements.txt, 
    -rspam/requirements.txt, 
    -rmultitask/requirements.txt, 
    -rvisual_relation/requirements.txt, 
    -rcrowdsourcing/requirements.txt, 
    -rrecsys/requirements.txt, 
    -rdrybell/requirements.txt, 
    jupyterlab
snorkel37 installed: absl-py==0.12.0,anyio==2.2.0,appdirs==1.4.4,argon2-cffi==20.1.0,astor==0.8.1,async-generator==1.10,attrs==20.3.0,Babel==2.9.0,backcall==0.2.0,black==19.3b0,bleach==3.3.0,blis==0.2.4,bokeh==2.3.1,boto3==1.17.49,botocore==1.20.49,cached-property==1.5.2,certifi==2020.12.5,cffi==1.14.5,chardet==4.0.0,click==7.1.2,cloudpickle==1.6.0,contextvars==2.4,cycler==0.10.0,cymem==2.0.5,dask==2.30.0,dataclasses==0.8,decorator==5.0.6,defusedxml==0.7.1,distributed==2.30.1,entrypoints==0.3,filelock==3.0.12,flake8==3.7.8,fsspec==0.9.0,future==0.18.2,gast==0.4.0,gdown==3.8.1,google-pasta==0.2.0,grpcio==1.37.0,h5py==3.1.0,HeapDict==1.0.1,idna==2.10,immutables==0.15,importlib-metadata==3.10.0,ipykernel==5.5.3,ipython==7.16.1,ipython-genutils==0.2.0,ipywidgets==7.6.3,jedi==0.18.0,Jinja2==2.11.3,jmespath==0.10.0,joblib==1.0.1,json5==0.9.5,jsonschema==3.2.0,jupyter==1.0.0,jupyter-client==6.1.12,jupyter-console==6.4.0,jupyter-core==4.7.1,jupyter-packaging==0.7.12,jupyter-server==1.6.0,jupyterlab==3.0.13,jupyterlab-server==2.4.0,jupyterlab-widgets==1.0.0,jupytext==1.2.0,Keras-Applications==1.0.8,Keras-Preprocessing==1.1.2,kiwisolver==1.3.1,locket==0.2.1,Markdown==3.3.4,MarkupSafe==1.1.1,matplotlib==3.1.1,mccabe==0.6.1,mistune==0.8.4,msgpack==1.0.2,munkres==1.1.4,murmurhash==1.0.5,names==0.3.0,nbclassic==0.2.7,nbconvert==5.5.0,nbformat==5.1.3,networkx==2.3,nltk==3.4.5,nose==1.3.7,notebook==6.3.0,numpy==1.16.4,packaging==20.9,pandas==0.25.3,pandocfilters==1.4.3,parso==0.8.2,partd==1.2.0,pexpect==4.8.0,pickleshare==0.7.5,Pillow==8.1.1,plac==0.9.6,preshed==2.0.1,prometheus-client==0.10.1,prompt-toolkit==3.0.18,protobuf==3.15.8,psutil==5.8.0,ptyprocess==0.7.0,py4j==0.10.7,pyarrow==0.14.1,pycodestyle==2.5.0,pycparser==2.20,pyflakes==2.1.1,Pygments==2.8.1,pyparsing==2.4.7,pyrsistent==0.17.3,pyspark==2.4.3,python-dateutil==2.8.1,pytorch-transformers==1.0.0,pytz==2021.1,PyYAML==5.4.1,pyzmq==22.0.3,qtconsole==5.0.3,QtPy==1.9.0,regex==2021.4.4,requests==2.25.1,s3transfer==0.3.6,scikit-learn==0.21.3,scipy==1.5.4,Send2Trash==1.5.0,sentencepiece==0.1.95,six==1.15.0,sniffio==1.2.0,snorkel==0.9.5,sortedcontainers==2.3.0,spacy==2.1.9,srsly==1.0.5,svn==1.0.1,tblib==1.7.0,tensorboard==1.14.0,tensorboardX==1.8,tensorflow==1.14.0,tensorflow-estimator==1.14.0,termcolor==1.1.0,terminado==0.9.4,testpath==0.4.4,textblob==0.15.3,thinc==7.0.8,toml==0.10.2,toolz==0.11.1,torch==1.5.0,torchvision==0.6.0,tornado==6.1,tqdm==4.60.0,traitlets==4.3.3,typing-extensions==3.7.4.3,urllib3==1.26.4,wasabi==0.8.2,wcwidth==0.2.5,webencodings==0.5.1,Werkzeug==1.0.1,widgetsnbextension==3.5.1,wrapt==1.12.1,zict==2.0.0,zipp==3.4.1
snorkel37 run-test-pre: PYTHONHASHSEED='1264958296'
snorkel37 run-test: commands[0] | python -c 'print((80*"~")+"\ntestenv: commands\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
testenv: commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
snorkel37 run-test: commands[1] | python -c 'print((80*"~")+"\n"+"pip list\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
pip list
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
snorkel37 run-test: commands[2] | python -m pip list --format=columns
Package              Version
-------------------- ---------
absl-py              0.12.0
anyio                2.2.0
appdirs              1.4.4
argon2-cffi          20.1.0
astor                0.8.1
async-generator      1.10
attrs                20.3.0
Babel                2.9.0
backcall             0.2.0
black                19.3b0
bleach               3.3.0
blis                 0.2.4
bokeh                2.3.1
boto3                1.17.49
botocore             1.20.49
cached-property      1.5.2
certifi              2020.12.5
cffi                 1.14.5
chardet              4.0.0
click                7.1.2
cloudpickle          1.6.0
contextvars          2.4
cycler               0.10.0
cymem                2.0.5
dask                 2.30.0
dataclasses          0.8
decorator            5.0.6
defusedxml           0.7.1
distributed          2.30.1
entrypoints          0.3
filelock             3.0.12
flake8               3.7.8
fsspec               0.9.0
future               0.18.2
gast                 0.4.0
gdown                3.8.1
google-pasta         0.2.0
grpcio               1.37.0
h5py                 3.1.0
HeapDict             1.0.1
idna                 2.10
immutables           0.15
importlib-metadata   3.10.0
ipykernel            5.5.3
ipython              7.16.1
ipython-genutils     0.2.0
ipywidgets           7.6.3
jedi                 0.18.0
Jinja2               2.11.3
jmespath             0.10.0
joblib               1.0.1
json5                0.9.5
jsonschema           3.2.0
jupyter              1.0.0
jupyter-client       6.1.12
jupyter-console      6.4.0
jupyter-core         4.7.1
jupyter-packaging    0.7.12
jupyter-server       1.6.0
jupyterlab           3.0.13
jupyterlab-server    2.4.0
jupyterlab-widgets   1.0.0
jupytext             1.2.0
Keras-Applications   1.0.8
Keras-Preprocessing  1.1.2
kiwisolver           1.3.1
locket               0.2.1
Markdown             3.3.4
MarkupSafe           1.1.1
matplotlib           3.1.1
mccabe               0.6.1
mistune              0.8.4
msgpack              1.0.2
munkres              1.1.4
murmurhash           1.0.5
names                0.3.0
nbclassic            0.2.7
nbconvert            5.5.0
nbformat             5.1.3
networkx             2.3
nltk                 3.4.5
nose                 1.3.7
notebook             6.3.0
numpy                1.16.4
packaging            20.9
pandas               0.25.3
pandocfilters        1.4.3
parso                0.8.2
partd                1.2.0
pexpect              4.8.0
pickleshare          0.7.5
Pillow               8.1.1
pip                  21.0.1
plac                 0.9.6
preshed              2.0.1
prometheus-client    0.10.1
prompt-toolkit       3.0.18
protobuf             3.15.8
psutil               5.8.0
ptyprocess           0.7.0
py4j                 0.10.7
pyarrow              0.14.1
pycodestyle          2.5.0
pycparser            2.20
pyflakes             2.1.1
Pygments             2.8.1
pyparsing            2.4.7
pyrsistent           0.17.3
pyspark              2.4.3
python-dateutil      2.8.1
pytorch-transformers 1.0.0
pytz                 2021.1
PyYAML               5.4.1
pyzmq                22.0.3
qtconsole            5.0.3
QtPy                 1.9.0
regex                2021.4.4
requests             2.25.1
s3transfer           0.3.6
scikit-learn         0.21.3
scipy                1.5.4
Send2Trash           1.5.0
sentencepiece        0.1.95
setuptools           51.3.3
six                  1.15.0
sniffio              1.2.0
snorkel              0.9.5
sortedcontainers     2.3.0
spacy                2.1.9
srsly                1.0.5
svn                  1.0.1
tblib                1.7.0
tensorboard          1.14.0
tensorboardX         1.8
tensorflow           1.14.0
tensorflow-estimator 1.14.0
termcolor            1.1.0
terminado            0.9.4
testpath             0.4.4
textblob             0.15.3
thinc                7.0.8
toml                 0.10.2
toolz                0.11.1
torch                1.5.0
torchvision          0.6.0
tornado              6.1
tqdm                 4.60.0
traitlets            4.3.3
typing-extensions    3.7.4.3
urllib3              1.26.4
wasabi               0.8.2
wcwidth              0.2.5
webencodings         0.5.1
Werkzeug             1.0.1
wheel                0.36.2
widgetsnbextension   3.5.1
wrapt                1.12.1
zict                 2.0.0
zipp                 3.4.1
snorkel37 run-test: commands[3] | python -c 'print((80*"~")+"\n"+"pip freeze\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
pip freeze
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
snorkel37 run-test: commands[4] | pip freeze
absl-py==0.12.0
anyio==2.2.0
appdirs==1.4.4
argon2-cffi==20.1.0
astor==0.8.1
async-generator==1.10
attrs==20.3.0
Babel==2.9.0
backcall==0.2.0
black==19.3b0
bleach==3.3.0
blis==0.2.4
bokeh==2.3.1
boto3==1.17.49
botocore==1.20.49
cached-property==1.5.2
certifi==2020.12.5
cffi==1.14.5
chardet==4.0.0
click==7.1.2
cloudpickle==1.6.0
contextvars==2.4
cycler==0.10.0
cymem==2.0.5
dask==2.30.0
dataclasses==0.8
decorator==5.0.6
defusedxml==0.7.1
distributed==2.30.1
entrypoints==0.3
filelock==3.0.12
flake8==3.7.8
fsspec==0.9.0
future==0.18.2
gast==0.4.0
gdown==3.8.1
google-pasta==0.2.0
grpcio==1.37.0
h5py==3.1.0
HeapDict==1.0.1
idna==2.10
immutables==0.15
importlib-metadata==3.10.0
ipykernel==5.5.3
ipython==7.16.1
ipython-genutils==0.2.0
ipywidgets==7.6.3
jedi==0.18.0
Jinja2==2.11.3
jmespath==0.10.0
joblib==1.0.1
json5==0.9.5
jsonschema==3.2.0
jupyter==1.0.0
jupyter-client==6.1.12
jupyter-console==6.4.0
jupyter-core==4.7.1
jupyter-packaging==0.7.12
jupyter-server==1.6.0
jupyterlab==3.0.13
jupyterlab-server==2.4.0
jupyterlab-widgets==1.0.0
jupytext==1.2.0
Keras-Applications==1.0.8
Keras-Preprocessing==1.1.2
kiwisolver==1.3.1
locket==0.2.1
Markdown==3.3.4
MarkupSafe==1.1.1
matplotlib==3.1.1
mccabe==0.6.1
mistune==0.8.4
msgpack==1.0.2
munkres==1.1.4
murmurhash==1.0.5
names==0.3.0
nbclassic==0.2.7
nbconvert==5.5.0
nbformat==5.1.3
networkx==2.3
nltk==3.4.5
nose==1.3.7
notebook==6.3.0
numpy==1.16.4
packaging==20.9
pandas==0.25.3
pandocfilters==1.4.3
parso==0.8.2
partd==1.2.0
pexpect==4.8.0
pickleshare==0.7.5
Pillow==8.1.1
plac==0.9.6
preshed==2.0.1
prometheus-client==0.10.1
prompt-toolkit==3.0.18
protobuf==3.15.8
psutil==5.8.0
ptyprocess==0.7.0
py4j==0.10.7
pyarrow==0.14.1
pycodestyle==2.5.0
pycparser==2.20
pyflakes==2.1.1
Pygments==2.8.1
pyparsing==2.4.7
pyrsistent==0.17.3
pyspark==2.4.3
python-dateutil==2.8.1
pytorch-transformers==1.0.0
pytz==2021.1
PyYAML==5.4.1
pyzmq==22.0.3
qtconsole==5.0.3
QtPy==1.9.0
regex==2021.4.4
requests==2.25.1
s3transfer==0.3.6
scikit-learn==0.21.3
scipy==1.5.4
Send2Trash==1.5.0
sentencepiece==0.1.95
six==1.15.0
sniffio==1.2.0
snorkel==0.9.5
sortedcontainers==2.3.0
spacy==2.1.9
srsly==1.0.5
svn==1.0.1
tblib==1.7.0
tensorboard==1.14.0
tensorboardX==1.8
tensorflow==1.14.0
tensorflow-estimator==1.14.0
termcolor==1.1.0
terminado==0.9.4
testpath==0.4.4
textblob==0.15.3
thinc==7.0.8
toml==0.10.2
toolz==0.11.1
torch==1.5.0
torchvision==0.6.0
tornado==6.1
tqdm==4.60.0
traitlets==4.3.3
typing-extensions==3.7.4.3
urllib3==1.26.4
wasabi==0.8.2
wcwidth==0.2.5
webencodings==0.5.1
Werkzeug==1.0.1
widgetsnbextension==3.5.1
wrapt==1.12.1
zict==2.0.0
zipp==3.4.1
snorkel37 run-test: commands[5] | python -c 'print((80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
________________________________________________________________________________________________________________________________ summary ________________________________________________________________________________________________________________________________
  snorkel37: commands succeeded
  congratulations :)
(.venv) cwm@flxsa02:~/git/git.c-w-m/nlp_dev/src/snorkel-tutorials$ tox -e markdown


```