# How does a program read the cvMat object, in particular, what is the order of the pixel structure?
The object is stored in a matrix. The structure may be different due to different type. When a program read the cvMat object, it first read the number of row, col and also which type is the object. Then it can get the data of each pixel from the certain positions. For example, for gray scale image, the data of one pixel is only saved in one position in the matrix. But for RGB, the data of R, G, B part are saved in three channels, so there will be three poisitions.