http://sdformat.org/tutorials?tut=convert_sdf_to_usd&ver=12&cat=developers&
dockerized sdf2usd environment
sdf2usdの環境構築をdockerizeしました。

docker-compose build
docker-compose up -d
docker exec -it kokhayas_container bash

sdf2usd directory/input.sdf directory/output.usda

git clone hsr
