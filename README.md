# KHU_Lecture

경희대학교 학부생 재학 중 "인공지능론" 강의를 수강하면서 수행한 프로젝트입니다.
프로젝트의 주제는 "음식 메뉴 분류를 통한 메뉴벌 후기 정리 서비스"입니다.

주제 선정 배경은 
1) '배달의 민족', '요기요'와 같은 배달 어플리케이션에 이미지 분류 기술 적용 가능성을 고찰하고,
2) 어플리케이션 이용 고객의 메뉴 선택 폭 확대를 통한 고객의 편의성 증진
입니다.

기존 서비스 방식은
1) 메뉴 입력 시 검색결과로는 매장별로만 나옵니다. Ex) "치킨" 검색 시 패스트푸드점(맘스터치 등)의 치킨에 대한 정보 부재 ( 2019년 11월 기준 )
2) 원하는 메뉴의 후기만 검색하는 것에 어려움이 있습니다.

제안하고자 하는 서비스 방식은 
1) 올라와 있는 후기(리뷰) 사진을 어떤 음식(메뉴)인지 분류해 해당 음식(메뉴)에 대한 후기를 모아서 제공하는 서비스
2) 원하는 메뉴에 대한 선택의 폭을 넓혀 보다 다양한 음식을 즐길 수 있게 해주는 서비스
3) 즉, 검색 결과에 표시되는 매장을 기존 서비스보다 증가시켜서 고객의 검색 편의성을 향상시키는 것
입니다.

사용된 데이터셋: Aihub에서 제공받은 배달 음식 이미지 데이터 중 5개 카테고리(떡볶이, 짜장면, 족발, 피자, 후라이드 치킨)별 300장 씩 1,500개의 image 파일
=> Image Augmentation을 통해 각 Label(음식)별로 3000장으로 증가시켜서 총 15,000개의 iamge 사용


