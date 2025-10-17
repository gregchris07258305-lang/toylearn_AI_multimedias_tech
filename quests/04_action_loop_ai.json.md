# 프롬포트

기사 내용을 일부 간략화해줘
- content 필드 값을 10자로 간략하게 줄여줘
- 나머지 필드 값은 그대로 유지

### 기사 내용
```json
{
  "title": {{ $json.title }},
  "link": {{ $json.link }},
  "content": {{ $json.content }},
  "pubDate": {{ $json.pubDate }}
}
```
### 출력 예시 
- 타이틀 : 
- 링크 : 
- 기사 내용 : 
- 발행 날짜 :

### 제외사항 
- 구어체