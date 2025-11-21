# BLNK PETROPIX

1. Retrieve an authentication token and authenticate your Docker client to your registry. Use the AWS CLI:

```bash
aws ecr get-login-password --region us-east-1 | docker login --username AWS --password-stdin 481255523699.dkr.ecr.us-east-1.amazonaws.com
```

2. Build your Docker image using the following command. For information on building a Docker file from scratch see the instructions here . You can skip this step if your image is already built:

```bash
docker build -t blnk-petropix .
```

3. After the build completes, tag your image so you can push the image to this repository:

```bash
docker tag blnk-petropix:latest 481255523699.dkr.ecr.us-east-1.amazonaws.com/blnk-petropix:latest
```

4. Run the following command to push this image to your newly created AWS repository:

```bash
docker push 481255523699.dkr.ecr.us-east-1.amazonaws.com/blnk-petropix:latest
```
