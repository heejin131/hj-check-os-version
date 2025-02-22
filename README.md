# hj-check-os-version

## USE
```python
$ pip install hj-check-os-version
$ python
>>> from hj_check_os_version .hi import hi
>>> hi()
```

### Devlelopment environment Setting
```bash
$ install pdm
$ git clone
$ source .vnev/bin/activate
# $ vi ...

# TEST
$ pdm install
$ pdm test
$ pip install

$ git add <file-name>
$ git commit -a
$ git push
$ pdm publish --username __token__ --password $PYPI_TOKEN
Building sdist...
Built sdist at /home/tom/code/hj-check-os-version/dist/hj_check_os_version-0.3.0.tar.gz
Building wheel from sdist...
Built wheel at /home/tom/code/hj-check-os-version/dist/hj_check_os_version-0.3.0-py3-none-any.whl
Uploading hj_check_os_version-0.3.0-py3-none-any.whl
 100% ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 18.1/18.1 kB • 00:00 • 83.2 MB/s
Uploading hj_check_os_version-0.3.0.tar.gz
 100% ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 16.0/16.0 kB • 00:00 • 80.8 MB/s

View at:
https://pypi.org/project/hj-check-os-version/0.3.6/

# PR - Merge
# Tag - Releases 
```

### TEST
- http://docs.pytest.org/en/stable/
```bash
# $ pdm add -dG test pytest pytest-cov
$ pytest
$ pytest -s
$ pytest --cov
```

### ART
```
==========----------------:::::::::::::::::::::::::::::::::::::-----------=++++++++++=-------------=
=============---------------:::::::::::-+*+-:-=+++*++==--#%%*-:-----------=++++++++++=--------------
=================------------::::::::-*@@@@@@@@@@@@@@@@@@@@@@@%+----------=++++++++++=--------------
=====================----------:::::+%@@@@@@@@@@@@@@@@@@@@@@@@@@%---------=++++++++++=--------------
=========================--------=%@@@@@@@%%@@@@%----*@@@@+--+@@@@=-------=++++++++++=--------------
=========================-==---+%@@@@@@%=---=#@@#-----+%#------*%*=-------=++++++++++=--------------
============================-=%@@@##%%#=----------------------------------=+++++**+++=--------------
============================+@@@%=----------------------------------------=++**++++++=--------------
===========================*@@@@+-----------------------=-----------------=++++++++++=--------------
==========================+@@@@#---=------*%%%#+---------+%%###+-----------=+++++++++---------------
==========================%@@@@*--=----=%@+:..=%@+-----=%@+...-@@=------------+++++++---------------
-------------------------*@@@@%-------=%@+....-%@@-----*@@#:.-#@@#-------------=+++++-:-------------
---------===+===-------==+*%@@%-------+@@@%%%@*+@%-----=%@@##@@@@=---------------++++-::------------
----------=====------==------%*--------*%@@@#%@@#--------=#%%%#+-----------------++++-----------====
--------===---------=---------=-----------=++==----------------------------------=++++++++**********
---------------------------------------------------------------------------------=+++*************++
-------------------=---------------------------------------====------------------=++++++++=======+++
-------------------=-----------------------------------=**######**+----------------:::--===========+
-------------------=----------------------------------*############*=-----------=::::::::::-=+======
--------------------=--------------------------------+###############=---------=-=-::::::::::::-====
---------------------=-------+*++==------------------*###############*-------=------=---::::::::::::
------------------------=**************++===---------=*##############+-----=------------=---::::::::
------------------------=**********************++++===+*############*==+++------------------=---::::
------------------------=************************************************+---------------------==---
------------------------=************************************************+-------------------------=
-------------------------+***********************************************+-----------------==-------
-------------------------=***********************************************+-------------====---------
-------------------------=***********************************************+--------------==----------
-------------------------+***********************************************+--------------------------
-------------------------=***********************************************+--------------------------
```

## REF
```bash
- https://pdm-project.org/en/latest/
- https://packaging.python.org/en/latest/tutorials/packaging-projects/
- console_scripts
```


