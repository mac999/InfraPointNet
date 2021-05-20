# Infra Point Net
Infra point net supports the train and prediction related to LiDAR point cloud dataset developed by Taewook Kang (laputa99999@gmail.com).

# algorithm  
fileList = readPointsList('list.txt') <br/>
for file in fileList: <br/>
    class, pcd = convertPCDtoTrainData(file) # convert octree <br/>
    train(net, class, pcd) <br/>

class net: <br/>
    def model(): <br/>
        return
