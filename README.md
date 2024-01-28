# docker-antdv-pro
docker-antdv-pro


# 克隆 antdv-pro
git clone https://gitee.com/antdv-pro/antdv-pro.git app

# 运行 docker-compose
docker-compose up -d

# 等待 容器内 pnpm 编译

# 访问页面
IP:63102
http://localhost:63102

# 从上游更新源码
cd app
<br/>
git pull

# 容器内 从上游更新源码
docker exec -it docker-antdv-pro /bin/sh -c "pwd && ls -alh &&git pull"
<br/>
<br/>
<br/>
容器内更新源码
<br/>
docker exec -it docker-antdv-pro /bin/sh -c "git pull"