# easyswoole3_dockerfile
# 构建镜像
  docker build -t easyswoole3 .
# 运行容器
  docker run -d -p 9501:9501 easyswoole3
# 访问
  http://localhost:9501
