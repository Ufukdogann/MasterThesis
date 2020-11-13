# MasterThesis

# in order to install git-lfs in the server!


```bash
sudo apt-get install git-lfs 
git lsf install
git lfs fetch
git lfs checkout
```

# for landingpage

```bash
python manage.py runserver
```

# for activating the chatbot

after downloading the chatbot, 
```bash
cd ~/ParlAI; python setup.py develop
```

```bash
python folder_name/Parlai/parlai/chat_service/services/browser_chat/run.py --config-path folder_name/Parlai/parlai/chat_service/tasks/chatbot/config.yml --port 8000
python folder_name/Parlai/parlai/chat_service/services/browser_chat/client.py --port 8000
```
