<img src="https://raw.githubusercontent.com/ADGVLOGS/ADG-ML-AI-Website/main/static/chessicon.svg" height="85px">  

# ADG-CHESS-AI ENGINE

#### Motivation
<p>After learning and looking at how George Hotz built his Chess Application on Twitch Slam. I wanted to build my own AI and have computer play me in chess and this is my <br> engine built by motivation of this paper <br> https://www.researchgate.net/profile/T-Anthony-Marsland-2/publication/2404258_Computer_Chess_Methods/links/0deec53c0d09e4e57e000000/Computer-Chess-Methods.pdf</p>

#### To Do
<p>1. Redesign whole system to a Keras Neural Network - Self Learning Model</p>
<p>2. Fix failed Ajax Responses when nodes exceed 7+ </p>

<img src="https://upload.wikimedia.org/wikipedia/commons/4/4e/Docker_%28container_engine%29_logo.svg" height="85px">  

#### Docker

````
docker pull adgrules/adg-aichess-engine
docker run --publish 8000:8000 adg-aichess-engine
````


#### Usage
<p>Compile the notebook to start a Flask Server</p>
<p>Send a URL to 'localhost/move/depth/path' </p>

````
Where depth {int} - Number of Nodes - More Nodes = More AI = More Processing Time = More Harder AI
Constrains dept can only be MAX_NODES = 60

Path is your chessboard

Example Usage

Request:   https://adgai.co.za/move/5/r1bqkbnr/pppppppp/2n5/8/4P3/3P4/PPP2PPP/RNBQKBNR%20b%20KQkq%20-%200%202
Response : e7e6
````

#### Interactive Implementation
Visit Here
https://adgai.co.za/adgchessai



#### Copyright (c) ADGSTUDIOS 2021 

------------------------------
| Date        | Changes      |
|-------------|--------------|
| 2021/08/25  | First Commit |
|             |              | 

