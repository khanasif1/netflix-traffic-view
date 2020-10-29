# Netflix Traffic View
<img src="https://github.com/khanasif1/netflix-traffic-view/blob/main/images/Regional.PNG" />
<img src="https://github.com/khanasif1/netflix-traffic-view/blob/main/images/services.PNG" />
# Setup
1. Get source, install deps, and run demo server.

   ```sh
   git clone https://github.com/khanasif1/netflix-traffic-view.git
   cd netflix-traffic-view
   npm install
   npm run dev
   ```

2. Open `localhost:8080` in your browser.

##### Using Docker
If you don't have a node environment setup or would like to run this example on a platform, there is a Dockerfile for experimental usage.

```
$ docker build -t <name>/netflix-traffic-view .
```
```
$ docker run -p 41911:8080 -d <name>/netflix-traffic-view
```

Then you should be able to navigate to http://localhost:41911
