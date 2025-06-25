## Free Course

https://github.com/markshust/docker-magento/blob/release/next/README.md#custom-cli-commands 

Trong quá trình làm việc nếu có vấn đề thì có thể 

- bin/restart 
- bin/fixowns: This will fix filesystem ownerships within the container.
- bin/fixperms: This will fix filesystem permissions within the container. 
- bin/bash: Drop into the bash prompt of your Docker container. The phpfpm container should be mainly used to access the filesystem within Docker.
- docker compose build 
- bin/copyfromcontainer: Copy folders or files from container to host. Ex. bin/copyfromcontainer vendor
- bin/copytocontainer: Copy folders or files from host to container. Ex. bin/copytocontainer --all
