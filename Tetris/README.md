## To play this amazing game

### Directly from Docker 
- Run the below command in terminal
```
docker run -it --rm --init -p 31:3000 siddiquesa/dockergames:gamestetris
```
then browse to  _**`http://localhost:31`**_
<hr>

### Using source codes
- clone this repo 
- change the directory into **Tetris**
- `docker build -t gametetris .`
- `docker run -it --rm --init -p 31:3000 gametetris`
- then browse to _**`http://localhost:31`**_
