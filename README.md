## Google-Text-to-Speech
### Text to Speech in 5 lines of python code using google text to speech API :

 ''' !pip install gTTS '''
from gtts import gTTS
import os
say = 'Hello Prashant Shekhar'
language = 'en'
speech = gTTS(text = say)
speech.save('/content/drive/My Drive/CSE Projects/first.mp3')
