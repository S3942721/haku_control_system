# haku_control_system
Complete control system and integration of all 4 repos and associated infrastructure

## Structure
### Handler
- This is the code that runs on the robot
- It 'handles' and processes commands from the web-server

### LLM
- This is the repo with the ollama container and prompt/model files
- This is only needed for the 'AI chat' functionality

### STT
- This contains the code responsible for taking audio from either a USB microphone, or from the robot and converting into text for the LLM to process
- This is only needed for the 'AI chat' functionality

### Web Controller
- This is one of the main components of the system
- This is responsible for commanding the robot(s) directly, and their handler will process these requests
- This will provide the web-page for devices to control the robot

## Clone the repo
```bash
git clone --recursive git@github.com:S3942721/haku_control_system.git

cd haku_control_system # Move into the repo folder
```

## 

