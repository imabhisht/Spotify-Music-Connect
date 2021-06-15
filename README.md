
# Music Connect Web  App

House Party Music Controlling Application for Spoitfy.


## Features

- Host can create Room
- Guest can join the Room [Room Code Required]
- Guest can Pause/Play [Permission Required]
- Guest can Skip/Forward [Permission Required]



  
## Setup Instructions

### Install Required Python Modules

```bash
  pip install -r requirements.txt
```

### Start Web Server

```bash
  python manage.py runserver
```

### For Developing and Testing Purpose



#### [Install Node.js](https://nodejs.org/en/)

#### Install Node Modules

First go into the ```frontend``` folder.
```bash
cd frontend
```
Next install all dependicies.
```bash
npm i
```

#### Compile the Front-End

Run the production compile script
```bash
npm run build
```
or for development:
```bash
npm run dev
```

  