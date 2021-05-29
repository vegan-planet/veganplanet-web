# 下载并运行前端UI
git clone https://github.com/vegan-planet/veganplanet-web.git

cd veganplanet-web && npm install -g cnpm --registry=https://registry.npm.taobao.org

npm run build:docker && docker-compose up -d

