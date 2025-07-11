# <p align="center"><b>HackRF GNU Radio FM Transmitter</b></p>
## <p align="center"><b>Simple GNU Radio blocks for TX</b></p>
- Start in your LINUX Terminal
## ! FOR EDUCATION PUSPOSES ONLY !
### !ONLY YOU ARE RESPONSIBLE FOR ANY DAMAGES or ILLEGAL ACTIVITY !
- I recommend to use Dragon OS
## ensure you have gnuradio version 3.10.4.0
# Setup
## For Transmit saved file (song) on FM
- For check your GNU radio version
```
gnuradio-config-info --version
```
- Start GNU radio
```
gnuradio-companion HackRFOne-FM-Transmitter.grc
```
- OR just by python
```
python3 default.py
```
## For transmit Audio (Your Voice) on FM
- Enable your USB or 3.5MM jack Microphone then start
```
gnuradio-companion hackRFOneMicTransmitFM.grc
```
- then press play button
- now say: Hello Hello, this is test 123 ...
