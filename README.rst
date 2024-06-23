This project documents the Participatory Processes Backend

The full documentation is hosted at `Read the Docs <https://participatory-tool.readthedocs.io/>`_.

- cd into the project folder

.. code-block:: bash
    
    cd {PROJECT_FOLDER}

- Create and activate the virtual environment and install dependencies

.. code-block:: bash
    
    virtualenv env
    source env/bin/activate
    pip install -r requirements.txt

- Run the below command to build Docs 

.. code-block:: bash
    
    sphinx-build docs docs/_build/

- Navigate to docs/_build/index.html and open the file