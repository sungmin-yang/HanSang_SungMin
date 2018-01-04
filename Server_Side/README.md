# Server side

### Using AWS
### Languages : C++, Java, Python

### Funtions
1. Get Signal
2. Convert Signal_to_Voice(sig2vce)
3. 


### Caution
- There will be no function to call "real phone number".  e.g., Voip <-> Real-Phone (Not our target) <br>
- else

### Possible libraries
  #### *libSRTP : RFC3711(Secure Real Time Transport Protocol) <- RTP+security+Compression <- Cisco
    - used for VoIP, Audio and Video streaming.
    - https://github.com/cisco/libsrtp
    - Licencse : publish copyright, BSD-based License (Cisco Systems)
  #### *Speex software : audio compression format
    - www.speex.org
    - Licencse : Revised BSD License
  #### *GSM Codec 06.10 software, Speech Compression, www.quut.com/gsm/
  #### *iLBC Codec software, Speech codec for VoIP, www.webrtc.org/ilbc-freeware
  #### *WebRTC software, Real-Time Communications(RTC), Javascript API, www.webrtc.org
  #### *Opus-codec software, codec, www.opus-codec.org
  
### Reference
References are ordred by priority.

- Library Collection in KaKao : https://m.blog.naver.com/PostView.nhn?blogId=dunamislife&logNo=140205513731&proxyReferer=https%3A%2F%2Fwww.google.se%2F
- General info about KaKao Voice : https://www.bpak.org/blog/2012/08/kakaotalk-%EB%B3%B4%EC%9D%B4%EC%8A%A4%ED%86%A1-voice-talk%EC%97%90-%EA%B4%80%ED%95%9C-%EC%9D%B4%EC%95%BC%EA%B8%B0/
