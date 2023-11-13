## next.js란
Next.js는 JavaScript 프레임워크 중 하나로서, React 기반의 서버 사이드 렌더링(SSR)과 정적 사이트 생성(SSG)에 특화되어 있습니다. 그 외에도 Next.js는 다음과 같은 특징들을 가지고 있습니다:

1. 페이지 기반 라우팅 시스템: 각 파일이 URL에 직접적으로 연결되는 파일시스템 기반 라우팅을 사용합니다. 예를 들어, pages/about.js 파일은 /about URL에 매핑됩니다.
2. 핫 코드 리로딩: 파일을 저장할 때마다 페이지가 자동으로 새로 고침되어 개발 과정을 더욱 효율적으로 만듭니다.
3. 서버사이드 렌더링(SSR): 초기 페이지 로딩 시 서버에서 렌더링하여 사용자에게 보내줍니다. 이를 통해 초기 로딩 성능을 향상시키고, 검색 엔진 최적화(SEO)에 유리합니다.
4. 정적 사이트 생성(SSG): 빌드 시점에 HTML 파일을 생성하여, 요청 시마다 이를 제공하므로 성능이 빠르고 안정적입니다.
5. API 라우트 지원: API 라우트를 통해 백엔드 기능을 구현할 수 있으며, 이를 통해 API를 손쉽게 구축할 수 있습니다.
6. 타입스크립트 지원: 기본적으로 TypeScript를 지원하여, 타입 안정성을 제공합니다.
7. 자동 코드 분할: 각 페이지는 그 페이지에서만 사용하는 JavaScript를 로드합니다. 이로 인해 불필요한 코드가 로드되는 것을 방지하고, 성능을 향상시킬 수 있습니다.

# 설치
npx create-next-app@latest

What is your project named? my-app
Would you like to use TypeScript? <span "style=color=blue">No</span> / Yes
Would you like to use ESLint? No / <span "style=color=blue">Yes</span>
Would you like to use Tailwind CSS? <span "style=color=blue">No</span> / Yes
Would you like to use `src/` directory? No / <span "style=color=blue">Yes</span>
Would you like to use App Router? (recommended) No / Yes
Would you like to customize the default import alias (@/*)? No / <span"style=color=blue">Yes</span>
What import alias would you like configured? @/*

## ssr과 csr의 차이점