Main Translator: SQuAD_trans.py
Utility: SQuAD_trans_utils.py

Open the Main translator if you wanna translate your SQuAD Dataset JSON file

Handle Error:

if NotValidPayload occured
change the error shown on your console on validate.py into this:

if not isinstance(text, str) or text.isdigit():
        return text