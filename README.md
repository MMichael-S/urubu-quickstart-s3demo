# urubu-quickstart-s3demo
A simple demo website build by urubu-quickstart for "Static Website Hosting on Amazon S3"

#About urubu installation & build:
http://urubu-quickstart.jandecaluwe.com/start.html

Steps:

Clone the repository

cd urubu-quickstart-s3demo/_build

aws s3 sync . s3://s3.mm2dela.xyz/

s3.mm2dela.xyz is bucket hosting website and match the Domain name.

