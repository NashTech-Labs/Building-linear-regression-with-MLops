Linear Regression Using MLops. This is a basic demo project on how use Mlops for making good Machine Learning projects.
We are using a wine quality csv dataset for this project.

The requirements for this project can be installed using:
"pip install -r requirements.txt"

Add the dataset to DVC using:
"dvc init"
"dvc add data_given/winequality.csv"

The parameters for the model are set in params.yaml file. Feel free to play around with it.

Use "dvc repro" to which will run all the stages in dvc. If there is any chage it will show. It will also create a dvc.lock file which will track any changes if made.

Then finally use the following dvc command to chack your result:
"dvc metrics show"
"dvc metrics diff"
