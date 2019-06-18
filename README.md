"Speech To Text android " 
First we need to create a RecognizerIntent by setting necessary flags such as
ACTION_RECOGNIZE_SPEECH – Simply takes user’s speech input and returns it to same activity
LANGUAGE_MODEL_FREE_FORM – Considers input in free form English
EXTRA_PROMPT – Text prompt to show to the user when asking them to speak
hence the speech input is done we have to catch the response in onActivityResult and take appropriate action needed.
