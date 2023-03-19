# The Galatic Poets

## SmartTagger

Inside the lib/navigate/navigate_bloc.dart folder, there is a variable called API_ENDPOINT. This is the API that communicates with the AI deployed by Uvicorn. Please fill in the value of the API for the application to work.

### Flutter app

* Step 1: `flutter package get`
* Step 2: `flutter run`

### Model AI
* Step 1: `pip install -r requirements.txt`
* Step 2: `uvicorn app.main:app --reload`
