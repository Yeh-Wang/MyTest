# MyTest

## Basical Git CMD

* `git init`  
  Create a new respository locally.
* `git clone [remoteurl]`  
Clone a remote repository to local.
* `ssh-keygen -t [rsa/ecdsa/ed25519] -C    "youremail@example.com"`  
  `eval "$(ssh-agent -s)"`  
  `ssh-add ~/.ssh/id_[rsa/ecdsa/ed25519]`  
Config local and remote ssh connections: Generate a key and add it to the agent.Then you should add the key to your remote respository deploy keys.
