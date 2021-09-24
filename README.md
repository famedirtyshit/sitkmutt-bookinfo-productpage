# Bookinfo Productpage Service

Productpage service has been developed on python

## How to run

```bash
pip install -r requirements.txt
python productpage.py 9080
```

## How to run with Docker

```bash
# Build Docker Image for productpage service
docker build -t productpage .

# Run productpages service on port 8083
docker run -d --name productpage -p 8083:9080 productpage
```

## Website

[Opsta (Thailand) Co., Ltd.](https://www.opsta.co.th)
