# 정보보안 종목 주가

국내 정보보안 상장사 36개 종목의 주가, 시가총액, 전일·전주·전월·전분기 등락률을 보여 주는 시세판입니다. 로그인 없이 누구나 볼 수 있습니다.

- 시세: [kr-stock-prices API](https://kr-stock-prices.benepass-mcp-cloudflare.workers.dev/v1/prices?codes=042510) (Cloudflare Worker)
- 장중(09:00–15:30 KST)에는 1분마다, 장 마감 후에는 5분마다 자동으로 새로 받습니다.
- 페이지는 `index.html` 한 파일이며 GitHub Pages로 공개합니다.

시가총액은 기준일 주가 × 최신 상장주식수로 계산한 추정치이고, 매출·영업이익은 전년 연간 실적입니다. 투자 판단의 근거로 쓰지 마세요.
