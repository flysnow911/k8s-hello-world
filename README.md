# SpringBoot k8s Hello-World
这是个最简单的springboot k8s helloworld项目，主要用途是：   
1. 拿来直接在上面写demo，学习新技术。
2. 写好了现成的DockerFile,k8s的相关yaml文件。   
      可以直接利用这些文件打包docker镜像,实现在k8s中部署app pod的一整套流程。
	
		dockerfile     --制作docker镜像
		namespace_create.yaml  --k8s ns创建文件
		service.yaml 		   --k8s svc创建文件
		ingress.yaml           --k8s ingress route创建文件
		deployment.yaml        --pod部署文件



