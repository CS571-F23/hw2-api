build
```bash
docker build . -t ctnelson1997/cs571-f23-hw2-api
docker push ctnelson1997/cs571-f23-hw2-api
```

run
```bash
docker pull ctnelson1997/cs571-f23-hw2-api
docker run --name=cs571_f23_hw2_api -d --restart=always -p 38102:38102 -v /cs571/f23/hw2:/cs571 ctnelson1997/cs571-f23-hw2-api
```