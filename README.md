Library on Flask
====================

An site with articles and books, created for VD. Works on Flask framework & hosted by OpenShift cloud.


Running on OpenShift
----------------------------

Create an account at https://www.openshift.com

Create a python application

    rhc app create library postgresql-9.2 python-2.7 --from-code=https://github.com/AlexMakII/rhc.library

That's it, you can now checkout your application at:

    http://library-$yournamespace.rhcloud.com
