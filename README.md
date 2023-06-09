# Real_Time Speech Transcription

'app.py' in this repository is a python source code to trnscribe the audio from the microphone for 5 sces since the button is clicked. This code utilizes Streamlit and SpeechRecognition libraries and Hugging Face API to transcribe the speech.

# Instructions To Setup:

i. Clone the reository and install the required python packages mentioned in 'requirements.txt'

ii.Get API token from Hugging Face and assifn to the api_token variable in the code.

iii.Run the file using the command:
streamlit run app.py

iv. This opens the app in browser. Click 'Start Recording' and speak into microphone.

v. As soon as you click the button 'Recording.....' is displayed. The recording is stopped automatically after 5 seconds and 'recording stopped.' is displayed.

vi. You can change the recording time by changing the value of duration in line 60 of code to the required value.

# Note:

-->Accuracy of the transcription depends on HuggingFace API
-->Cannot stop recording by clicking the button. Recording automatically stops after specified duration. You can always change it to the desired value by changing the value of duaration in line 60.
-->Showing some error while deplying in streamlit cloud.
