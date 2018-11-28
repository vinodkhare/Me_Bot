# Me_Bot
A simple tool to make a bot that speaks like you, simply learning from your WhatsApp Chats.

## Requirements

* **TensorFlow**: to install TensorFlow, [conda-forge](https://conda-forge.org/) needs to be added to Anaconda as a channel. Start Anaconda prompt and add the channel using

```cmd
> conda config --add channels conda-forge
> conda install tensorflow tensorflow-hub
```

* **[`sentencepiece`](https://github.com/google/sentencepiece)**: needs to be installed using `pip`.

```cmd
> pip install sentencepiece
```

Instructions:-

1. From WhatsApp on your phone, go to any chat and export it by going into the settings. Move the txt file that you receive inside the Me_Bot folder.

2. Run the clean_whatsapp_chats.py script using the command. Before running, change the names of the people by changing YOUR_NAME and OTHER_NAME in the scripts according to the txt file you have for your chats.

`python clean_whatsapp_chats.py whatsapp_chat.txt`

3. Run the prepare_files.ipynb ipython notebook.

4. Run the Me_Bot.ipynb file and you can play with the bot at the bottom!
