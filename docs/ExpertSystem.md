# Expert System

# Requirment
 - [python 2.7](https://www.python.org/)
  - [flask](http://flask.pocoo.org/)
    
     install
     ```
      pip install Flask
     ```
     
     run
     ```
      python flask.py
     ```
  - [pyswip](https://pypi.python.org/pypi/pyswip)
    
    install
     ```
      pip install pyswip
     ```
    
  - [flask-cors](https://flask-cors.readthedocs.io/en/latest/)
  
     install
     ```
      pip install -U flask-cors
     ```
 - [prolog](http://www.swi-prolog.org/)
   PS: if you see this error
```
 libpl (shared) not found. Possible reasons:
 1) SWI-Prolog not installed as a shared library. Install SWI-Prolog (5.6.34 works just fine)

```
  - windows
    copy a file and rename it 
   ```
    // copy a file
    C:\Program Files\swipl\bin\libwsipl.dll
    // rename to
    C:\Program Files\swipl\bin\libpl.dll 
   ```
  - unbuntu
    copy a file and rename it 
   ```
    // copy a file
    /usr/lib/libswipl.so
    // rename to
    /usr/lib/libpl.so
   ```
# Get started
  import jess into project directory
```
  src/
  |- Server.java
  |- kb.clp
  |- jess.jar
```
