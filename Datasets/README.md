Download links for the datasets used in the paper:

      Baidu Netdisk address:


We provide the RS-AOD dataset in COCO format and in YOLO format for training with the Ultralytics object detection framework. We also provide the ShipRSImageNet dataset in YOLO format for training with the Ultralytics object detection framework.

Some modifications have been made to the ShipRSImageNet dataset, specifically:

      Only the "Ship" category is retained.
      All images have been resized to 640×640.


These modifications were made to facilitate the extraction of APSM's generic amplitude spectrum and to ensure that the image input size required during APSM training and validation matches or closely approximates the size of the extracted generic amplitude spectrum, thereby avoiding significant discrepancies.

