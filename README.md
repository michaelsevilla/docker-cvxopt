Installs dependencies for [CVXOPT](http://cvxopt.org/index.html) and builds it. 

===================================================
Quickstart
===================================================

To drop into a container that has CVXOPT:

```bash
msevilla@dexter:~/$ docker run -it --name cvxopt-container michaelsevilla/cvxopt
```

Once inside the container, run the example:

```bash
root@ea319b33e82b: cd /cvxopt-1.1.8/examples/doc/chap8/
root@ea319b33e82b: python lp.py
root@ea319b33e82b: exit
```
