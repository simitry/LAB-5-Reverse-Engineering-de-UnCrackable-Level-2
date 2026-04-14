# LAB-5-Reverse-Engineering-de-UnCrackable-Level-2


# Étape 1 — Installer et lancer l’APK

premierement, une fois l'apk installé on peut pas l'ouvrir, donc on execute un code javascript "bypass.js" pour intercepter apk et l'ouvrir
<img width="696" height="316" alt="image" src="https://github.com/user-attachments/assets/500aa348-0285-4849-a876-e6a11c33cdcd" />
<img width="493" height="890" alt="image" src="https://github.com/user-attachments/assets/a6ba6220-9453-435a-b6c6-6fd246eed60c" />

# Étape 2 — Décompiler l’APK avec JADX Gui

<img width="1335" height="753" alt="image" src="https://github.com/user-attachments/assets/1296aa02-5ed8-4b59-b26f-21f0620cf49d" />

# Étape 3 — Repérer l’appel de validation dans MainActivity

<img width="1043" height="380" alt="image" src="https://github.com/user-attachments/assets/7cf0bb34-7fa0-4098-adca-4185e6a95898" />

# Étape 4 — Identifier la classe qui effectue la vérification

<img width="388" height="133" alt="image" src="https://github.com/user-attachments/assets/8ba84b84-8ac1-4bc8-ab47-36d5313988bc" />

# Étape 5 — Extraire le contenu de l’APK

<img width="696" height="256" alt="image" src="https://github.com/user-attachments/assets/18156c95-9b4e-4026-b28d-64e66d3aa325" />
<img width="705" height="510" alt="image" src="https://github.com/user-attachments/assets/630e9568-89e8-4c83-8725-d8793163564d" />
<img width="94" height="53" alt="image" src="https://github.com/user-attachments/assets/2cddd881-cd12-4c95-bce8-e01cf365d175" />

la bibliothèque libfoo.so est localisée.

# Étape 6 — Importer libfoo.so dans Ghidra

<img width="1461" height="921" alt="image" src="https://github.com/user-attachments/assets/166fa902-159d-457e-b9e1-e8d5b00417df" />
<img width="1620" height="919" alt="image" src="https://github.com/user-attachments/assets/3c6f0044-46ad-4a23-b438-688622e47ea9" />

<img width="495" height="115" alt="image" src="https://github.com/user-attachments/assets/7bc66cd6-b7f6-48e3-912c-e567e4e5ce80" />
dans l'image ci-dessus on a trouvé la chaîne cachée.


<img width="402" height="870" alt="image" src="https://github.com/user-attachments/assets/1603b4a0-f4b9-4f36-9b19-619ec011dec7" />






