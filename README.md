# [Start Bootstrap - Clean Blog Jekyll](https://startbootstrap.com/themes/clean-blog-jekyll/) - Official Jekyll Version

[Clean Blog Jekyll](https://startbootstrap.com/themes/clean-blog-jekyll/) is a stylish, responsive blog theme for [Bootstrap](https://getbootstrap.com/) created by [Start Bootstrap](https://startbootstrap.com/). This theme features a blog homepage, about page, contact page, and an example post page along with a working contact form powered by [Formspree](https://formspree.io/).

This repository holds the official Jekyll version of the Clean Blog theme on Start Bootstrap!

## Preview

[![Clean Blog (Jekyll) Preview](https://startbootstrap.com/assets/img/screenshots/themes/clean-blog-jekyll.png)](http://StartBootstrap.github.io/startbootstrap-clean-blog-jekyll/)

**[View Live Preview](http://StartBootstrap.github.io/startbootstrap-clean-blog-jekyll/)**

## Installation & Setup

### Using RubyGems

When installing the theme using RubyGems, demo images, posts, and pages are not included. Follow the instructions below for complete setup.

1. (Optional) Create a new Jekyll site: `jekyll new my-site`
2. Replace the current theme in your `Gemfile` with `gem "jekyll-theme-clean-blog"`.
3. Install the theme (run the command inside your site directory): `bundle install`
4. Replace the current theme in your `_config.yml` file with `theme: jekyll-theme-clean-blog`.
5. Build your site: `bundle exec jekyll serve`

Assuming there are no errors and the site is building properly, follow these steps next:

1. Create the following pages if they do not exist already (or change the extension of existing markdown files from `.md` to `.html`):

   * `index.html` - set to `layout: home`
   * `about.html` - set to `layout: page`
   * `contact.html` - set to `layout: page`
   * `posts/index.html` - set to `layout: page` (you will also need to create a `posts` directory)

2. Configure the `index.html` front matter. Example:

    ```markdown
    ---
    layout: home
    background: '/PATH_TO_IMAGE'
    ---
    ```

3. Configure the `about.html`, `contact.html`, and `posts/index.html` front matter. Example:

    ```markdown
    ---
    layout: page
    title: Page Title
    description: This is the page description.
    background: '/PATH_TO_IMAGE'
    ---
    ```

4. For each post in the `_posts` directory, update the front matter. Example:

    ```markdown
    ---
    layout: post
    title: "Post Title"
    subtitle: "This is the post subtitle."
    date: YYYY-MM-DD HH:MM:SS
    background: '/PATH_TO_IMAGE'
    ---
    ```

    For reference, look at the [demo repository](https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll) to see how the files are set up.

5. Add the form to the `contact.html` page. Add the following code to your `contact.html` page:

    ```html
    <form name="sentMessage" id="contactForm" novalidate>
      <div class="control-group">
        <div class="form-group floating-label-form-group controls">
          <label>Name</label>
          <input type="text" class="form-control" placeholder="Name" id="name" required data-validation-required-message="Please enter your name.">
          <p class="help-block text-danger"></p>
        </div>
      </div>
      <div class="control-group">
        <div class="form-group floating-label-form-group controls">
          <label>Email Address</label>
          <input type="email" class="form-control" placeholder="Email Address" id="email" required data-validation-required-message="Please enter your email address.">
          <p class="help-block text-danger"></p>
        </div>
      </div>
      <div class="control-group">
        <div class="form-group col-xs-12 floating-label-form-group controls">
          <label>Phone Number</label>
          <input type="tel" class="form-control" placeholder="Phone Number" id="phone" required data-validation-required-message="Please enter your phone number.">
          <p class="help-block text-danger"></p>
        </div>
      </div>
      <div class="control-group">
        <div class="form-group floating-label-form-group controls">
          <label>Message</label>
          <textarea rows="5" class="form-control" placeholder="Message" id="message" required data-validation-required-message="Please enter a message."></textarea>
          <p class="help-block text-danger"></p>
        </div>
      </div>
      <br>
      <div id="success"></div>
      <div class="form-group">
        <button type="submit" class="btn btn-primary" id="sendMessageButton">Send</button>
      </div>
    </form>
    ```

    Make sure you have the `email` setting in your `_config.yml` file set to a working email address! Once this is set, fill out the form and then check your email, verify the email address using the link sent to you by Formspree, and then the form will be working!

6. Build your site: `bundle exec jekyll serve`

### Using Core Files

When using the core files, the demo images, posts, and pages are all included with the download. After following the instructions below, you can then go and change the content of the pages and posts.

1. [Download](https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll/archive/master.zip) or Clone the repository.
2. Update the following configuration settings in your `_config.yml` file:

    * `baseurl`
    * `url`
    * `title`
    * `email` (after setting this setting to a working email address, fill out the form on the contact page and send it - then check your email and verify the address and the form will send you messages when used)
    * `description`
    * `author`
    * `twitter_username` (Optional)
    * `facebook_username` (Optional)
    * `github_username` (Optional)
    * `linkedin_username` (Optional)
    * `instagram_username` (Optional)

3. Build your site: `bundle exec jekyll serve`

## Bugs and Issues

Have a bug or an issue with this template? [Open a new issue](https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll/issues) here on GitHub!

## About

Start Bootstrap is an open source library of free Bootstrap templates and themes. All of the free templates and themes on Start Bootstrap are released under the MIT license, which means you can use them for any purpose, even for commercial projects.

* <https://startbootstrap.com>
* <https://twitter.com/SBootstrap>

Start Bootstrap was created by and is maintained by **[David Miller](http://davidmiller.io/)**.

* <http://davidmiller.io>
* <https://twitter.com/davidmillerhere>
* <https://github.com/davidtmiller>

Start Bootstrap is based on the [Bootstrap](https://getbootstrap.com/) framework created by [Mark Otto](https://twitter.com/mdo) and [Jacob Thorton](https://twitter.com/fat).

## Copyright and License

Copyright 2013-2021 Start Bootstrap LLC. Code released under the [MIT](https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll/blob/master/LICENSE) license.

---

## 한국어 번역 (원문 유지)

### Start Bootstrap - Clean Blog Jekyll (공식 Jekyll 버전)

[Clean Blog Jekyll](https://startbootstrap.com/themes/clean-blog-jekyll/)은 [Start Bootstrap](https://startbootstrap.com/)에서 만든 Bootstrap 기반의 세련되고 반응형 블로그 테마입니다. 이 테마는 블로그 홈, 소개 페이지, 연락처 페이지, 예시 포스트 페이지를 제공하며, [Formspree](https://formspree.io/)를 이용한 동작 가능한 문의 폼도 포함합니다.

이 저장소는 Start Bootstrap의 Clean Blog 테마 Jekyll 공식 버전을 담고 있습니다.

### 미리보기

- 라이브 미리보기: <http://StartBootstrap.github.io/startbootstrap-clean-blog-jekyll/>

### 설치 및 설정

#### RubyGems 방식

RubyGems로 테마를 설치하면 데모 이미지/포스트/페이지는 기본 포함되지 않습니다. 전체 구성을 위해 아래 순서를 따르세요.

1. (선택) 새 Jekyll 사이트 생성: `jekyll new my-site`
2. `Gemfile`의 테마를 `gem "jekyll-theme-clean-blog"`로 변경
3. 사이트 디렉터리에서 의존성 설치: `bundle install`
4. `_config.yml`의 테마를 `theme: jekyll-theme-clean-blog`로 변경
5. 사이트 빌드/서버 실행: `bundle exec jekyll serve`

빌드가 정상이라면 추가로 아래를 진행합니다.

1. 아래 페이지를 생성(또는 `.md`를 `.html`로 변경)
   - `index.html`: `layout: home`
   - `about.html`: `layout: page`
   - `contact.html`: `layout: page`
   - `posts/index.html`: `layout: page` (`posts` 디렉터리 필요)

2. `index.html` front matter 설정 예시

```markdown
---
layout: home
background: '/PATH_TO_IMAGE'
---
```

3. `about.html`, `contact.html`, `posts/index.html` front matter 설정 예시

```markdown
---
layout: page
title: Page Title
description: This is the page description.
background: '/PATH_TO_IMAGE'
---
```

4. `_posts` 안 각 포스트 front matter 설정 예시

```markdown
---
layout: post
title: "Post Title"
subtitle: "This is the post subtitle."
date: YYYY-MM-DD HH:MM:SS
background: '/PATH_TO_IMAGE'
---
```

5. `contact.html`에 폼 추가 (원문 코드 블록 참고)
6. 다시 빌드: `bundle exec jekyll serve`

#### Core Files 방식

코어 파일 방식은 다운로드 시 데모 이미지/포스트/페이지가 포함됩니다.

1. 저장소 다운로드 또는 클론
2. `_config.yml`의 설정값 갱신
   - `baseurl`, `url`, `title`, `email`, `description`, `author`
   - 선택: `twitter_username`, `facebook_username`, `github_username`, `linkedin_username`, `instagram_username`
3. 빌드: `bundle exec jekyll serve`

### 버그 및 이슈

- 템플릿 버그 제보: <https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll/issues>

### About / 라이선스

Start Bootstrap은 오픈소스 Bootstrap 템플릿/테마 라이브러리이며, 무료 템플릿/테마는 MIT 라이선스로 배포됩니다.

---

## 이 저장소용 배포 전 점검 가이드 (Docker)

로컬 Ruby/Jekyll 설치 없이 Docker로 미리보기/검증하도록 구성했습니다.

### 추가된 파일

- `docker-compose.yml`
- `Dockerfile.jekyll`
- `.dockerignore`

### 사용 명령

1. 로컬 미리보기 서버

```bash
docker compose up --build
```

2. 배포 전 production 빌드 점검

```bash
docker compose run --rm jekyll-build
```

3. 종료

```bash
docker compose down --remove-orphans
```

### 최근 반영 사항 (2026-04-14)

- `_posts/2025-11-10-paper.html` front matter YAML 오류 수정
  - `journal` 값(콜론 포함)과 `author` 값을 따옴표로 감싸 파싱 오류 해결
- 동일 출력 경로 충돌이 나던 포스트들에 `slug` 추가
  - 충돌 경고(`Conflict: destination is shared by multiple files`) 해소
- Docker 이미지 정리
  - 테스트 중 사용했던 `jekyll/builder:latest`, `jekyll/jekyll:pages` 정리
