# STIX suite

This repository contains all related tools for using STIX. It includes:

1. STIX  (main program)
2. Giggle (tool for indexing)
3. excord (SV singals extraction for short-read)
4. excordlr (SV singals extraction for long-read)

The bundled toolset will be published as docker images with version numbers. Please note that the version is NOT the stix version, it is the stix-suite version. 


## Versions


### 1.0.0

- stix[de50db8]

- giggle[4071cb7]

- excord[v0.2.4]

- excord-lr[v0.1.17]

<details>

```
docker build -t stix-suite:1.0.0 -f Dockerfile  versions/1.0.0/
docker tag 784ea063777c zhengxc1993/stix-suite:1.0.0
docker push zhengxc1993/stix-suite:1.0.0
```

</details>
