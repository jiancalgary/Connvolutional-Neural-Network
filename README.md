![](https://raw.githubusercontent.com/NELSONZHAO/zhihu/master/cifar_cnn/example_pic.png)


# Statements
It includes two parts：

- CIFAR_KNN.ipynb
- CIFAR_CNN.ipynb

# Version
```Python3`` and```TensorFlow 1.0```

```CIFAR_CNN.ipynb```

	import tarfile
	cifar10_path = 'cifar-10-batches-py'
	tar_gz_path = '/input/cifar-10/python.tar.gz' 
	with tarfile.open(tar_gz_path) as tar:
	    tar.extractall()
	    tar.close()
	    


	floyd run --gpu --env tensorflow-1.0 --mode jupyter --data diSgciLH4WA7HpcHNasP9j
