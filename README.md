text-segmentation-server
========================

an http server wrapped around norvig's text segmentation implemenation

`pip install tornado`

`python server`

```
curl "localhost:8888?q=whorepresents"
who represents
```

```
curl "localhost:8888?q=117MARGARETSTREETPLANTCITYFL"
117 margaret street plant city fl
```
