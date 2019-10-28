# marker_localization
A collection of tools to perform localization in an unknown environment with defined markers

## ml_detector
This node will detect and output pose estimates for defined ARUCO markers/boards

## ml_landmarks
This node will accept found marker positions, extract pose estimates, then manage and pusblish static transforms for each of the known markers

## Usage
To be used with the packages on [aruco_client]() and [knowledge_server]() 
* Images added are required for the boards
* Changed board dictionary
