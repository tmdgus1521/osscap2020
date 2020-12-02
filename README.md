오픈소스 팀 프로젝트_나_3팀
___
사용한 오픈소스 링크

1. [손동작] :  https://github.com/DarshNaik/Hand-Detection-Finger-Counting

2. [리듬 게임] : https://github.com/PrintedLove/Python-pygame-Game-4-Beats
___     


## 라이브러리 설치

1. Pygame 설치
___
    python3 -m pip install -U pygame --user

2. OpenCv 설치
___
   [OpenCv] : http://www.3demp.com/community/boardDetails.php?cbID=235
  
3. numpy 설치
___
    sudo apt-get install python3-numpy
    
## 실행 방법

    git clone https://github.com/tmdgus1521/osscap2020
1. 리듬 게임 실행
___
    cd osscap2020/Python-pygame-Game
    python3 game.py
   
   game.py 오류 관련
   ALSA error: snd_pcm_open failed: No such file or directory 및 audio 관련.
        
    sudo raspi-config
    system option에서 Audio를 HDMI로 변경하기
        
2. 모션 인식 실행
___
    cd osscap2020/Hand-Detection-Finger-Counting
    python3 main.py
    
   위 명령어로 켜진 화면에 나와있는 사각형 영역 안에 손가락을 넣어 손가락 개수를 인식시킴
    
## 시연영상
    [유튜브 링크] : https://youtu.be/KmkHHHh79z8
