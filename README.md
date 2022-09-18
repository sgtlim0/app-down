# app-down
app download html

ffmpeg -r 6 -i ./jpg/%03d.jpeg -vcodec libx264 out.mp4

사진폴더에 있는 사진들을 (img000.jpg ~ img999.jpg, 연속된 이름만 가능) 15프레임, H264 코덱으로 output.mp4로 출력하겠다.

ffmpeg -r 15 -i "C:\경로\사진폴더\img%03d.jpg" -vcodec libx264 "C:\출력\경로\output.mp4"
-r : 초당 프레임 수
-i : 입력 파일 경로
-vcodec : 비디오 코덱 설정
