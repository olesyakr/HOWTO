## HOWTO create Python virtual environment venv
using Windows command prompt

open cmd
enter desired directory 
create python virtual environment:
```
python -m venv brass_counter_env
```
after environment is created, enter folder
```
cd brass_counter_env
```
start virtual environment
```
Scripts\activate
```
to close environment run:
```
Scripts\deactivate.bat
```

***************************
While in active environment (Scripts\activate), one can install needed packages using pip install
such as
```
pip install jupyterlab
```
or if there is a requirements.txt file
one can install specific versions from the file
make sure to include -r
```
pip install -r requirements.txt
```



