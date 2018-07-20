# Self-contained ASP.NET Core with Docker sample

## Usage

Build the container:

```
docker build -t aspnetcoresample .
```

Then run it interactively:

```
docker run -it -p 5000:5000 aspnetcoresample
```

And you can test it from another terminal with:

```
curl http://localhost:5000
```