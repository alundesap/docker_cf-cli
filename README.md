# docker_opensuse

```
cd /Users/i830671/git/docker_headless

docker build -t alunde/headless:latest .

docker run -ti -p 2222:22 alunde/headless:latest

```
Connect with:
```
ssh -p 2222 root@localhost
```
