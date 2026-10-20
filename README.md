# vf-factcheck

비전파인더 홈페이지(visionfinder.co.kr) 「편입 카더라 팩트체크」 글 저장소.

- 대표가 VF 다음 카페 「최신 입시 팩트체크」 게시판에 **등록한 글만** 이곳에 올라온다 (예약 작업이 자동으로 옮김).
- 홈페이지는 `posts/index.json`과 `posts/<slug>.md`를 읽어 보여준다 (1시간마다 갱신).
- 홈페이지 소스 코드는 이 저장소에 두지 않는다.

## 형식
- `posts/index.json`: `[{ "slug", "title", "claim", "order", "publishedAt", "updatedAt", "cafeUrl" }]`
- `posts/<slug>.md`: 프론트매터(title, claim, status: "published", publishedAt, reviewedAt, author, order, sources, cafeUrl) + 카페 본문(줄바꿈 그대로)
