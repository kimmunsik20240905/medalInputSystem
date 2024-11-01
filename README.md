# 파리올림픽 국가별 랭킹 입력 사이트 구축 프로젝트

## 프로젝트 개요
리액트를 이용하여 파리올림픽 참가국별 메달 획득 상황을 입력, 읽기, 수정, 삭제 하여 국가별 랭킹을 리스트화 할 수 있게 구현한 프로젝트

- **제작 기간:** 2024.10.30 ~ 2024.11.1

## 기술 스택
- ![Yarn](https://img.shields.io/badge/Yarn-2C8EBB?style=flat&logo=yarn&logoColor=white)
- ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
- ![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white)
- ![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat&logo=css3&logoColor=white)
- ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
- ![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)

## 페이지 구성 및 기능
- 레이아웃(App.jsx), 인풋 영역(MedalSubmit.jsx), 리스트 영역(MedalList.jsx)으로 컴포넌트를 분리
- 중복 체크를 통한 국가별 메달 집계 현황 입력 기능 (국가명 중복 시 입력 불가)
- 중복 체크를 통한 국가별 메달 집계 현황 수정 기능 (입력된 국가가 존재하지 않을 시 수정 불가)
- 로컬 스토리지를 이용한 CRUD 기능
- 금메달 순 정렬 및 총 메달 순 정렬 형태로 내림차순 정렬 기능
