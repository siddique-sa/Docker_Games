## To play this amazing game
### Directly from Docker 
- Run the below command in terminal
```
docker run -it --rm --init -p 30:3000 siddiquesa/dockergames:games2048
```
then browse to  _**`http://localhost:30`**_
<hr>

### Using source codes

- clone this repo 
- change the directory into **2048**
- `docker build -t game2048 .`
- `docker run -it --rm --init -p 30:3000 game2048`
- then browse to _**`http://localhost:30`**_
