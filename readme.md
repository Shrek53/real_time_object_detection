**Create virtual env**
```bash
virtualenv venv -p python3
```
**Activate virtual env**
```bash
source ./venv/bin/activate
```
**Install requirements**
```bash
pip install -r requirements.txt
```
**Run object detection program**
```bash
python real_time_object_detection.py -p MobileNetSSD_deploy.prototxt.txt -m MobileNetSSD_deploy.caffemodel
```
