pwa dev detail
==============

Step - pwa-checkpoint-01_
--------------------------------

Just getting things setup for baseline pwa ReactJS project with documentation on 2cld-pwa-readthedocs_

#. Create new React-App Web Application::

    catmini:2cld cat$ npx create-react-app pwa

#. Pull in docs structure::

    macci:pwa cat$ cd ~/2cld/pwa
    macci:pwa cat$ (copy in base docs from 2cld-readthedocs-demo_ setup)
    macci:pwa cat$ vi docs/conf.py
    macci:pwa cat$ vi docs/index.rst (and various others)
    macci:pwa cat$ cd docs
    macci:docs cat$ make html (fix errors)
    macci:docs cat$ open build/html/index.html

#. Verify docs build here 2cld-pwa-localdocs_ on local system

#. Adjust .gitignore (add docs/build/)::

    # See https://help.github.com/ignore-files/ for more about ignoring files.
    
    # dependencies
    /node_modules

    # testing
    /coverage

    # production
    /build

    # misc
    .DS_Store
    .env.local
    .env.development.local
    .env.test.local
    .env.production.local

    npm-debug.log*
    yarn-debug.log*
    yarn-error.log*

    #######################
    # readthedocs gitignore

    # sphinx build folder
    docs/build/



Step Template
=============

Step-NN - pwa-checkpoint-NN_
-----------------------------------

The NAME_OF_GOAL Step-NN intent is to blahblahblah.

#. Create NAME_OF_GOAL for pwa-checkpoint-NN_

    #. tbd  
    #. tbd 

#. Produce pwa-checkpoint-NN_ NAME_OF_GOAL

    macci:pwa cat$ cd ~/2cld/pwa/docs
    macci:docs cat$ vi source/pwa-dev-detail.rst (update doc)
    macci:docs cat$ make html 
    macci:docs cat$ open build/html/index.html (verify docs)
    macci:pwa cat$ cd ~/2cld/pwa
    macci:pwa cat$ git add *
    macci:pwa cat$ git commit -m "commit for pwa-checkpoint-NN - NAME_OF_GOAL"
    macci:pwa cat$ git tag pwa-checkpoint-NN
    macci:pwa cat$ git push
    macci:pwa cat$ git push origin pwa-checkpoint-NN
    
#. Verify checkpoint pwa-checkpoint-NN_

Resources
---------

#. Github Project Repo: 2cld-pwa-github_
#. Read the Docs: 2cld-pwa-readthedocs_
#. ReadTheDocs demo files: 2cld-readthedocs-demo_


.. _readthedocs: https://readthedocs.org/
.. _2cld-readthedocs-demo: https://github.com/2cld/readthedocsdemo
.. _2cld-pwa-readthedocs: http://2cld-pwa.readthedocs.io/en/latest/
.. _2cld-pwa-localdocs: http://~/2cld/pwa/docs/build/html/index.html
.. _2cld-pwa-github: https://github.com/2cld/pwa


.. _firebase-console: https://console.firebase.google.com/

.. _pwa-checkpoint-NN: https://github.com/2cld/pwa
.. _pwa-checkpoint-01: https://github.com/2cld/pwa/tree/pwa-checkpoint-01
.. _pwa-checkpoint-02: https://github.com/2cld/pwa/tree/pwa-checkpoint-02
.. _pwa-checkpoint-03: https://github.com/2cld/pwa/tree/pwa-checkpoint-03
.. _pwa-checkpoint-04: https://github.com/2cld/pwa/tree/pwa-checkpoint-04
.. _pwa-checkpoint-05: https://github.com/2cld/pwa/tree/pwa-checkpoint-05
.. _pwa-checkpoint-06: https://github.com/2cld/pwa/tree/pwa-checkpoint-06
.. _pwa-checkpoint-07: https://github.com/2cld/pwa/tree/pwa-checkpoint-07
.. _pwa-checkpoint-08: https://github.com/2cld/pwa/tree/pwa-checkpoint-08
.. _pwa-checkpoint-09: https://github.com/2cld/pwa/tree/pwa-checkpoint-09
.. _pwa-checkpoint-10: https://github.com/2cld/pwa/tree/pwa-checkpoint-10
.. _pwa-checkpoint-11: https://github.com/2cld/pwa/tree/pwa-checkpoint-11
.. _pwa-checkpoint-12: https://github.com/2cld/pwa/tree/pwa-checkpoint-12

.. _youtube-FlutterWireUpFirebaseAuthiOS: https://www.youtube.com/watch?v=3nFIMej3Tvw
.. _youtube-ios-tutorial-testflight-1: https://www.youtube.com/watch?v=1CcCKQHjDpw
.. _youtube-ios-tutorial-testflight-2: https://www.youtube.com/watch?v=1DVLaMmGxR8

.. _github-projects-configure-projects: https://help.github.com/articles/configuring-automation-for-project-boards/
