---
# 페이지 제목
title: My page
# 페이지 유형 - 랜딩 페이지
type: landing

# 랜딩 페이지 섹션 - 다양한 콘텐츠 블록 추가 가능
sections:
  # 블로그 게시물을 표시하는 섹션
  - block: collection
    id: section-1
    content:
      title: Section 1
      subtitle: A subtitle
      text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
      # `content/post/` 폴더의 콘텐츠 표시
      filters:
        folders:
          - contact
    design:
      # 섹션의 열 수 선택. 유효 값: '1' 또는 '2'.
      columns: '1'
      # 콘텐츠 나열 뷰 선택 - 여기서는 `showcase` 뷰 사용
      view: community/card
      # Showcase 뷰에서 대체 행 뒤집기 여부
      flip_alt_rows: true
---
