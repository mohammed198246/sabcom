# SABCoM repository lay-out	
	
    .
    ├── /docs                 # Documentation files, also used to host documentation site
    ├── /src                  # Model source files
    ├──	/.github/workflows    # used for continuous integration  
    ├── /input_data           # data files that serve as input for the model
    ├── /output_data          # data files that are model output_data and scripts to generate graphs
    ├── /raw_data 	      # data & scripts that are used to generate the input data
    ├── /initialisations      # pickle files of initialised model version with 100k agents
    ├── calibration.ipynb     # notebook used to set the parameters of the model
    ├── de_model.ipynb        # notebook that contains the differential equation model 
    ├── initialisation.py     # script used to initialise the pickle files in the initialisation folder
    ├── simulations.py 	      # main script used to simulate the model 
    ├── sensitivity.py 	      # script used to do the sensitivity analysis 
    ├── test_SABCoModel.py    # test script to make sure the application runs
    ├── requirements.txt      # text file containing python package dependencies
    ├── LICENSE		      # MIT licence information	
    ├── README.md	      # model description
    └── .gitignore            # list of files to ignore for Github 
	