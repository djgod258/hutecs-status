# hutecs-status

휴텍스제약 영업관리 앱의 "매출현황" 화면에서 쓰는 상태 데이터 전용 저장소입니다.

- `special/latest.json` — 매출팀이 뱃파일로 올리는 품절금액·특이사항. 이 저장소에는 이 파일만 존재합니다.
- 이 저장소는 앱이 `raw.githubusercontent.com`으로 인증 없이 읽기 때문에 공개(Public)로 유지됩니다.
- 쓰기는 매출팀 담당자 PC의 GitHub PAT(Contents 권한만)로만 이루어집니다.
