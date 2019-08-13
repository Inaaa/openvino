# openvino
install openvino

run mask_rcnn_inception_v2
1.at first you should compile the openvino_demo, you can find the method here https://www.youtube.com/watch?v=6Ww_zLDGfII&list=PLDKCjIU5YH6jMzcTV5_cxX9aPHsborbXQ&index=5. Of course ,you can find it too at the webside of openvino.
2. Then you should download this model. 
3.You should go into the compile fiel from step 1 and go into ./intel64/Release, here you can find the compiled fiel mask_rcnn_demo.
4.run ./mask_rcnn_demo -i <path>/*.bmp -m ./<path>/mask_rcnn_inception_v2/frozen_inference_graph.xml.
