---
title: 초간단 Github Pages 튜토리얼 (with. Jekyll Chirpy Theme) - 0
author: Devisoun
date: 2024-07-07 15:16:00 +0900
categories: [Github Page]
tags: [development, github pages, jekyll, blog]
render_with_liquid: false
---

<!-- markdownlint-disable-next-line -->
![preview](/assets/img/preview/2024-07-07-초간단%20Github%20Pages%20튜토리얼%20(with.%20Jekyll%20Chirpy%20Theme)%20-%200.png)

## 블로그를 운영하려는 이유?

저는 새로운 기술 스택을 마주하고 경험하는 것을 참 좋아합니다!
개발자로서의 식견을 넓히거나 업계 트렌드를 파악하는 것에 큰 도움이 되기 때문이죠.

하지만 여러 종류의 기술 스택을 익히다보면 예전에는 일정 수준 다뤘던 것들도 종종 잊어버리거나 버벅이게 되는 일이 생기기 마련입니다.

가령, 하나의 프로젝트를 마치고 얼마 뒤에 새 프로젝트를 구축하려고 할 때

***내가 이거 초기 설정을 어떻게 잡았더라..?***<br/>
***전에 겪어본 에러인데 이거 어떻게 해결했었지..?***

하면서 바보가 되기도 하죠ㅎㅎ;

물론 이는 잠시 시간내어 구글링하면 금방 해결되겠지만 직접 블로그에 포스팅 하면서 개발 로그를 남기다보면 머릿속에서 쉽게 지워지지 않을 것이고 이를 여러 사람들과 공유할 수 있다는 점에 메리트를 느껴 블로그 운영을 결심하게 되었습니다.

## 왜 Github Pages를 선택하였는가?

<span style="background-color:#fff5b1;font-weight:bold;">Tistory, Velog, WordPress</span> 등등.. 여러 좋은 플랫폼들이 있지만 제가 <span style="background-color:#DCFFE4;font-weight:bold;">Github Pages</span>를 선택한 이유는 아래와 같습니다.

1. **마크다운(Markdown) 지원**
    - 마크다운은 코드 블록을 포함하여 다양한 프로그래밍 언어의 구문 강조(syntax highlighting)를 지원하기에 매우 유용합니다.
    - 대부분의 블로그 플랫폼에서 마크다운을 지원하므로, 추후 블로그 이전 시에 포스트 재사용이 간편합니다.
2. **완전 무료 이용 가능**
    - Github Pages는 도메인 비용을 제외하고는 별도의 비용이 발생하지 않습니다. 이마저도 기본 도메인 형태 `<사용자명>.github.io`를 사용한다면 완전 무료죠.
    - 무료로 제공되는 서비스임에도 불구하고, 높은 안정성과 성능을 보장받을 수 있습니다.
3. **작성한 포스트가 플랫폼의 것이 아닌, 온전히 내 소유여야 함**
    - Github Pages는 정적 블로그 플랫폼으로 로컬 저장소와 Github 리포지토리에서 마크다운으로 작성된 포스트를 직접 관리할 수 있습니다. 이는 서버가 다운되거나 서비스 종료될 경우 그간 작성해온 모든 포스트가 사라져버리는 타 플랫폼에 비해 매우 강력한 장점입니다!

그럼 다음 챕터부터는 본격적으로 Github Pages 설치 방법에 대해서 포스팅하겠습니다.