import speech_recognition

r = sr.Recognizer()
mic = sr.Microphone()

sr.LANGUAGE = 'ru-Ru'

with mic as source:
    r.adjust_for_ambient_noise(source)
    print('Говорите')
    Pyaudio = r.listen(source)

text = r.recognize_google(Pyaudio, language='ru-RU')
print(f"сказали: {text}")
