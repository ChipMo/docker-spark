env vars needed to start jupyter in pyspark

* export PYSPARK_DRIVER_PYTHON="jupyter" 

* export PYSPARK_DRIVER_PYTHON_OPTS="notebook --no-browser --port=8889 --ip=0.0.0.0" 
