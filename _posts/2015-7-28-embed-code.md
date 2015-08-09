title: Testing Code Embed
date: 2015-07-29 12:00:00

Testing embedding code

<h3>Python</h3>
<pre><code>
def myfunction(name)
    print "Hello %s" %(name)
</code></pre>
 
<h3>Matlab</h3>
<pre><code>
fprintf('%s\n','Eww')
</code></pre>


<h3>CSS</h3>
<pre><code>
    .list-group-item {
        border: none;
        border-radius: 0px;
        background-color:black;
        color: white;
    }
    .list-group-item:hover{
        background-color: #666;
    }
    .nav-item:hover {
        background-color: #666;
    }
</code></pre>

<h3>Harrr Docker!</h3>
<pre><code>
FROM python:2.7
ENV PYTHONUNBUFFERED 1
RUN apt-get update && apt-get install -y \
    libopenblas-dev \
    gfortran \
    libhdf5-dev \
	  default-jre

RUN pip install numpy \
    cython
RUN pip install -v scipy
RUN pip install scikit-learn pandas h5py matplotlib
</code></pre>

<h3>R</h3>
<code><pre>
cat("one","two","three","four",sep="|")
</code></pre>
