# Scam-call-detector

Input voice data is recorded using the 'Speech Recognition' library and converted to English using 'gTTS' (Google Text-to-Speech) if the input language is other than English. The model uses TF-IDF to study word patterns and predicts whether the text is phishing or not using Logistic regression. If the message is phishing, an authoritative answer aimed at thwarting the phishing attempt is generated using GPT-4. The warning message is translated into the language of the input speech using gTTS and played.
