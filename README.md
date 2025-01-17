# 출석체크 프로젝트

## 팀원
- 변상원
- 조송하
- 배우석

## 기능
1. 출석 체크, 수정
2. 출력 (*.csv)
3. DB: 주별, 월별, 학기별, 연별 (부가기능)
4. 등록
    1. 학생등록, 수정, 삭제
    2. 강의등록, 수정, 삭제 (부가기능)

## 요구사항
1. face-api를 활용해 학생들의 얼굴을 등록하여, 출석체크를 진행한다.
2. 학생 얼굴로 출석을 했을 때, 유사도(%)가 낮으면 관리자(교수님)가 선택하도록 한다.
3. 해당 과목에 등록되지 않은 학생이 출석했을 때 처리한다.
4. CSV를 이용하여 주, 월, 학기별로 출력할 수 있도록 한다.
5. 데이터베이스를 활용하여 이전 기록도 열람 가능해야 한다.

## 페이지
[메인화면(index.html)](index.html)<br>
[출석 페이지(attendance.html)](attendance.html)<br>
[출석관리 페이지(attendance_management.html)](attendance_management.html)<br>
[학생관리 페이지(student_management.html)](student_management.html)<br>
[학생 정보 페이지(student_info.html)](student_info.html)<br>
