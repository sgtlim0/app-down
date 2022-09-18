# app-down
app download html

ffmpeg -r 6 -i ./jpg/%03d.jpeg -vcodec libx264 out.mp4

사진폴더에 있는 사진들을 (img000.jpg ~ img999.jpg, 연속된 이름만 가능) 15프레임, H264 코덱으로 output.mp4로 출력하겠다.

ffmpeg -r 15 -i "C:\경로\사진폴더\img%03d.jpg" -vcodec libx264 "C:\출력\경로\output.mp4"
-r : 초당 프레임 수
-i : 입력 파일 경로
-vcodec : 비디오 코덱 설정





ffmpeg -f image2 -r 30 -i <이미지 있는 폴더\%04d.jpg> -vcodec libx264 <동영상 저장될 폴더>

 

eg.) ffmpeg -f image2 -r 30 -i C:\image\%04d.jpg -vcodec libx264 C:\temp\output.mp4

 

-f : 입력 파일의 포맷 의미, image2는 jpg 파일 의미

-r : 출력 동영상 fps 지정

-i : 입력 파일 위치 및 형식 %04d.jpg는 4자리 숫자로 구성된 jpg 파일을 의미한다. (ex. 0000.jpg, 0001.jpg, ..., 9999.jpg)

-vcodec : 출력 동영상의 압축 코덱을 의미, H.264가 가장 무난하다고 함

 
 
