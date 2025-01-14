<p align="center">
 <img width="100px" src="https://res.cloudinary.com/anuraghazra/image/upload/v1594908242/logo_ccswme.svg" align="center" alt="GitHub Readme Stats" />
 <h2 align="center">GitHub Readme Stats</h2>
 <p align="center">동적으로 생성되는 GitHub 사용량 통계를 여러분의 README 에 추가해보세요!</p>
</p>
  <p align="center">
    <a href="https://github.com/anuraghazra/github-readme-stats/actions">
      <img alt="Tests Passing" src="https://github.com/anuraghazra/github-readme-stats/workflows/Test/badge.svg" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/graphs/contributors">
      <img alt="GitHub Contributors" src="https://img.shields.io/github/contributors/anuraghazra/github-readme-stats" />
    </a>
    <a href="https://codecov.io/gh/anuraghazra/github-readme-stats">
      <img alt="Tests Coverage" src="https://codecov.io/gh/anuraghazra/github-readme-stats/branch/master/graph/badge.svg" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/issues">
      <img alt="Issues" src="https://img.shields.io/github/issues/anuraghazra/github-readme-stats?color=0088ff" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/pulls">
      <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/anuraghazra/github-readme-stats?color=0088ff" />
    </a>
    <a href="https://securityscorecards.dev/viewer/?uri=github.com/anuraghazra/github-readme-stats">
      <img alt="OpenSSF Scorecard" src="https://api.securityscorecards.dev/projects/github.com/anuraghazra/github-readme-stats/badge" />
    </a>
    <br />
    <br />
  </p>

  <p align="center">
    <a href="#미리보기">미리보기 확인</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new?assignees=&labels=bug&projects=&template=bug_report.yml">버그 제보하기</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new?assignees=&labels=enhancement&projects=&template=feature_request.yml">기능 추가 요청하기</a>
  </p>
  <p align="center">
    <a href="/docs/readme_fr.md">Français </a>
    ·
    <a href="/docs/readme_cn.md">简体中文</a>
    ·
    <a href="/docs/readme_es.md">Español</a>
    ·
    <a href="/docs/readme_de.md">Deutsch</a>
    ·
    <a href="/docs/readme_ja.md">日本語</a>
    ·
    <a href="/docs/readme_pt-BR.md">Português Brasileiro</a>
    ·
    <a href="/docs/readme_it.md">Italiano</a>
    ·
    <a href="/docs/readme_kr.md">한국어</a>
    .
  </p>
</p>
<p align="center">기능들이 마음에 드시나요? 괜찮으시다면, 서비스 개선을 위해 <a href="https://www.paypal.me/anuraghazra">기부</a>를 고려해주세요!
# 기능들 <!-- omit in toc -->

- [GitHub 통계](#github-통계)
    - [개별 통계 숨기기](#개별-통계-숨기기)
    - [총 커밋 수에 비공개 기여도 (private contribs) 수 추가하기](#총-커밋-수에-비공개-기여도-private-contribs-수-추가하기)
    - [아이콘 표시하기](#아이콘-표시하기)
    - [테마 설정하기](#테마-설정하기)
    - [커스터마이징](#커스터마이징)
- [GitHub 저장소 핀](#github-저장소-핀)
    - [사용법](#사용법)
    - [미리보기](#미리보기)
- [언어 사용량 통계](#언어-사용량-통계)
    - [사용법](#사용법-1)
    - [통계에서 제외할 저장소 지정하기](#통계에서-제외할-저장소-지정하기)
    - [통계에서 특정 언어 제외하기](#통계에서-특정-언어-제외하기)
    - [표시할 언어 수 지정하기](#표시할-언어-수-지정하기)
    - [컴택트한 카드 레이아웃 설정하기](#컴택트한-카드-레이아웃-설정하기)
    - [미리보기](#미리보기-1)
- [WakaTime 주간 통계](#wakatime-주간-통계)
    - [미리보기](#미리보기-2)
    - [전체 미리보기](#전체-미리보기)
    - [꿀팁 (저장소 핀 정렬하기)](#꿀팁-저장소-핀-정렬하기)
  - [나만의 Vercel 인스턴스에 직접 배포하기](#나만의-vercel-인스턴스에-직접-배포하기)
  - [:sparkling\_heart: 프로젝트 지원하기!](#sparkling_heart-프로젝트-지원하기)
 
  - # GitHub 통계

아래 코드를 복사해서 마크다운 파일에 붙여넣으면 끝이에요, 아주 간단해요!

`?username=` 속성의 값을 GitHub 계정의 사용자 명(닉네임)으로 바꿔주세요.

```md
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
```

_참고:_

_랭크는 S+ (상위 1%), S (상위 25%), A++ (상위 45%), A+ (상위 60%), 그리고 B+ (전체) 로 구성되어 있습니다._

_커밋의 수(commits), 기여도(contribution), 이슈의 수(issues), 즐겨찾기(star), 작업내용 반영 요청(Pull Request),
팔로워 수, 그리고 보유 중인 저장소 등의 항목들에 대해 [누적 분포 함수](https://ko.wikipedia.org/wiki/%EB%88%84%EC%A0%81_%EB%B6%84%ED%8F%AC_%ED%95%A8%EC%88%98) 를 이용해 계산됩니다._

_[src/calculateRank.js](../src/calculateRank.js) 에서 수행되는 계산 작업의 내용을 확인할 수 있습니다._

### 개별 통계 숨기기

특정 통계를 숨기려면 `콤마(,)`로 구분된 값들을 `?hide=` 속성의 값으로 넣어주세요.

> 사용 가능한 항목들: `&hide=stars,commits,prs,issues,contribs`

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=contribs,prs)
```

### 총 커밋 수에 비공개 기여도 (private contribs) 수 추가하기

`?count_private=true` 속성을 추가하시면, 여러분의 모든 비공개 기여도까지 반영됩니다.

_참고: 프로젝트를 직접 배포하신 경우, 비공개 기여도는 기본적으로 반영됩니다. 원하지 않는 경우엔 직접 설정해야 합니다._

> 예시: `&count_private=true`

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&count_private=true)
```

### 아이콘 표시하기

아이콘 항목을 활성화 하기 위해선, 다음과 같이 `show_icons=true` 속성을 추가해주세요.

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true)
```

### 테마 설정하기

내장 테마를 사용하시면, 별도의 [커스터마이징](#커스터마이징) 없이 GitHub 통계 카드를 꾸미실 수 있어요.

다음과 같이 `?theme=THEME_NAME` 속성을 이용해주세요.

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)
```

#### 지원하는 내장 테마 목록

dark, radical, merko, gruvbox, tokyonight, onedark, cobalt, synthwave, highcontrast, dracula

<img src="https://res.cloudinary.com/anuraghazra/image/upload/v1595174536/grs-themes_l4ynja.png" alt="GitHub Readme Stat Themes" width="600px"/>

[사용 가능한 모든 테마](../themes/README.md) 에서 미리보기를 확인하실 수 있어요.

원하신다면 [테마 설정하기](../themes/index.js) 항목에서  **새로운 테마를 직접 만드실수 있어요.** :D

### 커스터마이징

여러가지 추가 속성을 통해, 원하는대로 `Stats Card` 또는 `Repo Card` 모양을 커스터마이징할 수 있어요.

#### 기본 옵션:

- `title_color` - 카드 타이틀 색상 _(hex color)_
- `text_color` - 카드 본문 글씨 색상 _(hex color)_
- `icon_color` - 아이콘 색상 (활성화된 경우) _(hex color)_
- `bg_color` - 카드의 배경 색상 _(hex color)_ **혹은** 다음 양식으로 그라데이션 주기 _angle,start,end_
- `hide_border` - 카드의 테두리 표시 여부 _(boolean)_
- `theme` - 테마의 이름, [사용 가능한 모든 테마](../themes/README.md) 에서 선택
- `cache_seconds` - 수동으로 캐시 헤더 설정 _(min: 14400, max: 86400)_
- `locale` - 카드에 표시할 언어 _(e.g. kr, cn, de, es, etc.)_

##### 배경에 그라데이션 주기

그라데이션이 적용된 카드를 표시하고 싶으시다면, 여러가지 쉼표(,) 로 구분된 값을 추가할 수 있어요.

양식은 다음과 같습니다.

```
&bg_color=DEG,COLOR1,COLOR2,COLOR3...COLOR10
```

> 캐시에 대한 참고사항:
> 포크와 스타 수가 1,000 개 미만인 저장소의 카드는 기본적으로 4시간 (14,400초) 으로 설정되어 있습니다.
> 그 외에는, it's 2시간 (7,200초) 입니다. 또한, 캐시설정 시간의 범위는 최소 2시간, 최대 24시간입니다.


#### 통계 카드의 표시 제한 옵션:

- `hide` - 통계에서 특정한 값 제외 _(Comma-separated values)_
- `hide_title` - 타이틀 표시 여부 _(boolean)_
- `hide_rank` - 랭크 표시 여부 _(boolean)_
- `show_icons` - 아이콘 표시 여부 _(boolean)_
- `include_all_commits` - 올해가 아닌 전체 연도에 대한 커밋 포함 여부 _(boolean)_
- `count_private` - 비공개 기여도 포함 여부 _(boolean)_
- `line_height` - 텍스트 간 줄 높이 설정(자간) _(number)_
- `custom_title` - 카드의 타이틀 값 설정
- `disable_animations` - 카드의 모든 에니메이션 활성 여부 _(boolean)_

#### 저장소 카드의 표시 제한 옵션:

- `show_owner` - 저장소 소유자 닉네임 표기 여부 _(boolean)_

#### 언어 사용량 통계 카드의 표시 제한 옵션:

- `hide` - 카드에서 특정 언어 제외 _(Comma-separated values)_
- `hide_title` - 타이틀 제외 _(boolean)_
- `layout` - 5가지 값 사용 가능, `normal` & `compact` & `donut` & `donut-vertical` & `pie` 중 표시 형태 선택
- `card_width` - 카드 너비 직접 설정 _(number)_
- `langs_count` - 카드에 표시할 언어의 수 (1-10 사이, 기본 값 : 5) _(number)_
- `exclude_repo` - 통계에 제외할 저장소 지정 _(Comma-separated values)_
- `custom_title` - 카드의 타이틀 값 설정

##### 경고! **매우 중요**
>
> 언어의 이름은 [퍼센트 인코딩](https://ko.wikipedia.org/wiki/%ED%8D%BC%EC%84%BC%ED%8A%B8_%EC%9D%B8%EC%BD%94%EB%94%A9) 에 지정된 URI 방식으로 표기되어야 합니다.
> ( 예를 들면, `c++` 는 `c%2B%2B`, `jupyter notebook` 는 `jupyter%20notebook`, 등등. )
> [urlencoder.org](https://www.urlencoder.org/) < 서비스를 이용하면 자동으로 생성할 수 있습니다.

#### WakaTime 카드의 표시 제한 옵션:

- `hide_title` - 타이틀 제외 _(boolean)_
- `line_height` - 텍스트 간 줄 높이 설정(자간) _(number)_
- `hide_progress` - 퍼센트와 표기바 표시 여부 _(boolean)_
- `custom_title` - 카드의 타이틀 값 설정
- `layout` - 사용 가능한 두 가지 값, `default` & `compact` 중 표시 형태 선택
