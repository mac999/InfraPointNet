# Infra Point Net
Infra point net supports the train and prediction related to LiDAR point cloud dataset developed by Taewook Kang (laputa99999@gmail.com).

# algorithm
fileList = readPointsList('list.txt')
for file in fileList:
    class, pcd = convertPCDtoTrainData(file) # convert octree
    train(net, class, pcd)

class net:
    def model():
        return
