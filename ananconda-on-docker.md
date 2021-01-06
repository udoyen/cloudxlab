```

docker run -i -t -p 8888:8888 --name anaconda -v /home/george/Documents/cloudxlab-docs/projects/jupyter/opt/notebooks:/opt/notebooks continuumio/anaconda3 /bin/bash -c "/opt/conda/bin/conda install jupyter -y --quiet &&  /opt/conda/bin/jupyter notebook --allow-root --notebook-dir=/opt/notebooks --ip='*' --port=8888 --no-browser"


```