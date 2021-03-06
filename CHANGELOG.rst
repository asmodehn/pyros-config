Changelog
=========


0.2.1 (2018-04-15)
------------------------
- Removing MANIFEST. cleaning up README. [AlexV]
- Attempting to configure pyup with pipfile. [AlexV]
- Specifying xenial distro for travis, to get recent python versions.
  Now using the various python3 versions via tox. [AlexV]
- Now using travis version of python, independently of linux distro.
  [AlexV]
- Relying on six for portable string instance detection. [AlexV]
- Replacing requirements files with pipfile. [AlexV]
- First attempt to restructure the README for pipenv usage. [AlexV]
- Adding recent python version for testing. [AlexV]
- Adding direnv using pipenv layout. [AlexV]
- Adding Pipfile to support pipenv for ease of use. [AlexV]
- Update pytest from 3.2.0 to 3.5.0. [pyup-bot]
- Fixing README repo link after move. [AlexV]

  asmodehn -> pyros-dev
- Update pytest from 3.0.7 to 3.2.0. [pyup-bot]
- Update gitchangelog from 2.5.0 to 3.0.3. [pyup-bot]
- Now also detecting debian layout 'dist-packages' installs. [AlexV]
- Adding repr for confighandler. [AlexV]
- Adding __version__ to __init__ module. [alexv]
- Update pytest from 3.0.4 to 3.0.7. [pyup-bot]
- Setup.py publish command description change. [AlexV]


0.2.0 (2017-02-21)
------------------
- V0.2.0. [AlexV]
- Getting rid of config import to avoid deep complex behavior. Lets not
  care about imports here... [AlexV]
- Update gitchangelog from 2.4.1 to 2.5.1. [pyup-bot]
- Pin pytest to latest version 3.0.4. [pyup-bot]
- Pin gitchangelog to latest version 2.4.1. [pyup-bot]


0.1.5 (2016-08-31)
------------------
- V0.1.5. [alexv]
- Generated changelog. improved comments for release flow. [alexv]
- Fixed regression about accepting dict and object when configuring.
  [alexv]
- Improved logging. cosmetics. [alexv]


0.1.4 (2016-08-30)
------------------
- V0.1.4. [alexv]
- Generated changelog. [alexv]
- Improved setup.py publish and tag commands. [alexv]
- Fix creating directory for generated default config file if it doesnt
  exists yet. [alexv]
- Adding IOError handling by creating default configuration file from
  provided string. [alexv]
- Changed version number to patch .99 to denote devel version. [alexv]
- Removing useless cmakelists. [alexv]
- Fixed configimport for python3. [alexv]
- Added setup.cfg. added badge for ros release builds. [alexv]


0.1.3 (2016-08-10)
------------------
- More cleanup of ros stuff. preparing 0.1.3. [alexv]
- Improved setup to do releases. removed ros files from master branch.
  [alexv]
- Improve self test. [AlexV]
- Reviewing tox and tests. [AlexV]
- Refining tox test command, importing more from __future__. [AlexV]
- Making check for string work with python3. [AlexV]
- Adding .idea folder to gitignore. [AlexV]
- Removing ROS and not using site-package, this is a pure python
  package. [alexv]
- Revert "improving travis files to test catkin_pip build with
  rosdistros." [alexv]

  This reverts commit 3c3bdd1d65f28f24bf3891ff1567e084b0dfb6bf.
- Improving travis files to test catkin_pip build with rosdistros.
  [alexv]


0.1.2 (2016-06-03)
------------------
- Preparing version 0.1.2. [alexv]
- Adding one fake test to succeed tox. [alexv]
- Changing tox command to call py.test directly. [alexv]
- Now using pytest form catkin-pip. [alexv]
- Now using pytest from __main__ [alexv]
- Now using setup.py test command from tox. [alexv]
- First version, adding tox and py.test. removing dependency on
  importlib, not needed since py2.7 ? [alexv]


0.1.1 (2016-06-02)
------------------
- Preparing v0.1.1. [alexv]
- Fixing repo links in package.xml. [alexv]
- Using renamed dependency catkin_pip. [alexv]
- Small cleanup. removing mention of ros. now printing sys.path in case
  import fails. added gitignore. [alexv]


0.1.0 (2016-06-01)
------------------
- Generated changelog. [alexv]
- Cleaned up README. added .travis.yml. [alexv]
- Copying files from pyros-setup. [alexv]


