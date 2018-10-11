# WebRTC
 1、git config --global http.proxy "localhost:1087"
 2、git clone https://chromium.googlesource.com/chromium/tools/depot_tools.git
 3、open -e .bash_profile 
     set mac env:
     #WebRTC
     export PATH=$PATH:/Users/samir/WebRTC/depot_tools
     source .bash_profile
4、 run cmd below download source
    fetch --nohooks webrtc_android
    gclient sync
    
5、 https://webrtc.org/native-code/android/

