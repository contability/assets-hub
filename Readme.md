# Assets Hub 📦

정적 파일 저장소로 활용하는 Git 리포지토리이다.
이미지, 문서, 아이콘 등 다양한 정적 자산을 호스팅하고 웹에서 직접 접근할 수 있다.

## 사용 방법 🚀

리포지토리에 업로드된 파일은 다음 URL 패턴으로 직접 접근할 수 있다:

```
https://raw.githubusercontent.com/contability/assets-hub/main/경로/파일이름.확장자
```

### 예시:

```
https://raw.githubusercontent.com/contability/assets-hub/main/images/shiba_inu.webp
```

## 구조 📂

```
/
├── images/       # 이미지 파일 저장 (PNG, JPG, WEBP 등)
├── documents/    # 문서 파일 (PDF, DOCX 등)
├── icons/        # 아이콘 (SVG, ICO 등)
└── ...
```

## 장점 💡

- **간편한 배포**: Git을 통해 파일을 쉽게 관리하고 업데이트할 수 있다
- **버전 관리**: 자산 파일의 이력 관리가 가능하다
- **무료 호스팅**: GitHub의 인프라를 활용하여 비용 부담 없이 파일을 호스팅한다
- **신뢰성**: GitHub의 안정적인 인프라를 기반으로 높은 가용성 제공

## Git 리포지토리를 정적 파일 저장소로 활용할 때 주의사항 ⚠️

- 대용량 파일이나 매우 자주 접근하는 파일의 경우 CDN 서비스 사용을 고려해야 함
- GitHub의 저장소 크기 및 트래픽 제한을 고려해야 함
- 민감한 정보는 포함하지 말 것 (이 저장소는 PUBLIC)
