# PBFMM-HW

### QUERY CONTAINERS
```cmd
docker ps
```

### START CONTAINER:
```cmd
docker run -it --rm --name nauticle_container -v ${pwd}:/user_dir ubuntu_nauticle_intel
```

### START CONTAINER TERMINAL:
```cmd
docker start -i nauticle_container
```

### NAVIGATE:
```cmd
cd user_dir
cd lab5
```

### DOWNLOAD:
```cmd
wget -O config.yaml https://simba.ara.bme.hu/~havasitoth/PBMF/
```