Installs dependencies for [CVXOPT](http://cvxopt.org/index.html) and builds it. 

===================================================
Quickstart
===================================================

To drop into a container that has CVXOPT:

```bash
docker run -it --name cvxopt-container michaelsevilla/cvxopt
```

Once inside the container (you'll know because your prompt will look like this: ```root@ea319b33e82b: #```), run the example:

```bash
cd /cvxopt-1.1.8/examples/doc/chap8/
python lp.py
exit
```
