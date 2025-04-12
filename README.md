## Qr-detection

This project is developed to detect the qr codes on packages that are moving on a conveyer belt in the receiving inventory section of the warehose
The Qr code inclues the prduct id of the package and we have to store it in the database for further usage of it in the warehouse.
# Basic Workflow

* A camera is interated with the computer and captures the qr on the product then sends it to the computer.
* The computer uses image processing on the captured qr code to enhace it.
* Then the qr code gets scanned giving the product id as output.

# Corner cases

* Packages on the conveyer belt moves fast so that the capturing and detection of the qr codes should be fast.
* Packages are of different sizes(big package - easy to scan, small package - hard to scan) as the camera position is fixed.
* Placement and position of the qr code on the package is different.

# Solutions for the corner cases

* Still working on it
* We enhance the qr code quality for perfect scanning
* We trained Yolo model on 2d matrix detection so that it would be easy to locate and isolate qr.

# Manual Process of Scanning

![Sample Output](demo_result.png)

# Automated process of Scanning

![Sample Output](demo_result.png)
