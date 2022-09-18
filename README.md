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

 
 curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/1.jpg 	--output 081.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/2.jpg	--output 082.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/3.jpg	--output 083.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/4.jpg	--output 084.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/5.jpg	--output 085.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/6.jpg	--output 086.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/7.jpg	--output 087.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/8.jpg	--output 088.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/9.jpg	--output 089.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/10.jpg	--output 090.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/11.jpg	--output 091.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/12.jpg	--output 092.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/13.jpg	--output 093.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/14.jpg	--output 094.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/15.jpg	--output 095.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/16.jpg	--output 096.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/17.jpg	--output 097.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/18.jpg	--output 098.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/19.jpg	--output 099.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/20.jpg	--output 100.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/21.jpg	--output 101.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/22.jpg	--output 102.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/23.jpg	--output 103.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/24.jpg	--output 104.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/25.jpg	--output 105.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/26.jpg	--output 106.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/27.jpg	--output 107.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/28.jpg	--output 108.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/29.jpg	--output 109.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/30.jpg	--output 110.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/31.jpg	--output 111.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/32.jpg	--output 112.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/33.jpg	--output 113.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/34.jpg	--output 114.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/35.jpg	--output 115.jpg
curl https://hmgics-ne1s-stg.tridive.io/rendered/1920x1080/A22A_8IW5YCZ7ZHH002_NB9_NNB/03/0000/36.jpg	--output 116.jpg![image](https://user-images.githubusercontent.com/30682869/190933182-db0ced5d-77ba-449b-b4cf-edd907d4185b.png)

 
