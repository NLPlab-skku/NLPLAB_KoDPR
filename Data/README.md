# 한국어 정보검색 데이터셋

NLPLAB에서 [한국어 지식검색 대화](https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=&topMenu=&aihubDataSe=data&dataSetSn=71304) 데이터셋을 기반으로 구축한 한국어 정보검색 데이터셋입니다.
본 데이터셋은 NC soft와의 산학 연구를 통해 구축된 데이터셋으로 비공개 대상입니다.



## 구축내용
1) 원본 데이터의 질문을 기반으로 쿼리 구축
2) 구축된 쿼리를 이용해 엘라스틱 서치로 문서 검색
3) 검색된 상위 5개의 문서에 대해 관련성 여부 태깅

* 검색 대상 한국어 문서 집합은 NC soft로부터 제공받았습니다.



## 데이터 통계
<table class="tg">
<thead>
  <tr>
    <td class="tg-c3ow">쿼리</td>
    <td class="tg-c3ow">검색 대상 문서집합</td>
    <td class="tg-c3ow">태깅된 관련 문서</td>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-c3ow">10,266</td>
    <td class="tg-c3ow">1,355,594</td>
    <td class="tg-c3ow">17,606</td>
  </tr>
</tbody>
</table>

* 관련 문서는 검색 가능한 쿼리 9,261개에 대한 검색 결과를 기반으로 쿼리와 관련 있는 문서를 태깅한 개수
