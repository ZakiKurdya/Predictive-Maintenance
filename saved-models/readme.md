To load and use the pickle files, you will first need to import the pickle module. Then, you can use the `pickle.load()` function to open the pickle file and load the model stored in the file.

Here is an example of how to do this:

```
import pickle

# Open the pickle file and load the model
loaded_model = pickle.load(open('path/to/pickle/model_name.pkl', 'rb'))

# Use the model
loaded_model.predict(input_data)
```
