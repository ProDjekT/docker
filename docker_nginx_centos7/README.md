# dockerfiles for nginx on centos7


To build:

Copy the sources down -
```python
docker build -rm -t <username>/nginx:centos7 .
```
To run:
```python
docker run -d -p 80:80 <username>/nginx:centos7
``````

To test:
```python
curl http://localhost

``````
Please, see my Unix/Linux blog:
[Unix and Linux in examples](http://linux-notes.org)

It's russ version, but soon i'll have multi site on many languages
