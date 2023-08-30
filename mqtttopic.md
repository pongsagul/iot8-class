## How do you design MQTT topics and payloads for smart washing machine

1. สถานะเครื่องซักผ้า
    - topic:v1cdti/app/get/1212312121/model-01/sn-001/
    - payload
        - {"STATUS": "POWER ON|START|STOP|FINISHED|POWERED OFF"}
1. เซนเซอร์ภายในเครื่องซักผ้า
    - topic:v1cdti/app/get/1212312121/model-01/sn-001
    - payload
        - {"temperature": "25.2"}
        - {"Energy efficiency": "2000 W"}
        - {"saving water": "5"}
        - {"clean detergent": "100%"}
        - {"GPS": "Bankok"}
        - {"Water level": "5"}
        - {"UVC": "100%"}
        - {"Motor count ": "10"}
        - {"Humdity": "30%"}
        - {"Hall": "close"}
        - {"low acustic noise": "100 dB"}
        - {"3D position": "x,y,z"}
        

 1. เซนเซอร์ภายนอกเครื่องซักผ้า
    - topic:v1cdti/app/get/1212312121/model-01/sn-001
    - payload
        - {"Rader": "1"}
        - {"Touch water level sensing ": "3"}
        - {"low acustic noise": "60 dB"}
        - {"temperature": "25.6"}
        - {"Humdity": "50%"}
        - {"name": "value"}
        - {"": "value"}



