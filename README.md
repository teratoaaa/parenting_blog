# 육아 성장 블로그 배포 저장소

이 저장소는 Cloudflare Pages에 연결할 정적 블로그 산출물만 담습니다.
원본 루프 엔지니어링 코드와 초안 데이터는 포함하지 않습니다.

## Cloudflare Pages 설정

- Framework preset: None 또는 Static HTML
- Build command: 비워두기
- Build output directory: `/`
- Production branch: `main`

## 발행

원본 프로젝트에서 다음 명령으로 다시 생성합니다.

```bash
python3 scripts/publish_parenting_blog.py --push
```

- image_optimized: True
- converted_webp: 160
