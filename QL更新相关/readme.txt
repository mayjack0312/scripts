
# 什么都没有：docker+QL+QL端口更改（可选）+CK提交版Ninja（可选）
wget -q URL/ql.sh -O ql.sh && bash ql.sh

# 已有QL2.11+：一键拉库 没反应就是网不行
docker exec -it qinglong bash -c "$(curl -fsSL URL/1customCDN.sh)"

