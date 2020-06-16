# Tweet-Generator

Uses Twint and a GPT-2 Model to generate its own tweets based on the tweets of any Twitter user.

To generate a model that outputs tweets:

First, run the Data_Collecting_Cleaning.ipynb file and customize the parameters on the first cell. This will generate a text
file containing the tweets of the selected user from the specified date range.

Next, run the Train_GPT2_Model.ipynb file (preferably on Google Colab, if not you will have to delete certain lines)
and customize the parameters in the first cell. This will train a model and then output text containing generated tweets.

If you want to generate text without creating a new model, just run the last cell in the Train_GPT2_Model.ipynb file
