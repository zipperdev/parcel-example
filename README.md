# Parcel Bundler

Parcel 번들러는 소형 또는 중형의 크기의 프로젝트에
많이 사용되는 가벼운 번들러이다. _쉽게_ **커스터마이징이**
**가능한 것**이 특징이다

### Parcel 사용법

- #### Parcel에 플러그인을 삽입하고 싶다면?
  플러그인을 다운 받은 후 그에 맞는 확장자에 세부사항을 명시를 하기만 하면 적용이 가능하다. <br />
  ※ 자세한 사항은 <a href="https://parceljs.org/plugins.html">여기서</a> 확인 ※
- #### Parcel 번들러에 다른 파일을 첨부하고 싶다면?
  parcel-plugin-static-files-copy를 개발용으로 다운받은 후 package.json에 "staticFiles": { "staticPath": <다른 파일이 들어있는 폴더> }를 추가하여 다른 파일을 별도로 첨부할 수 있다.
- #### Parcel의 명령어에 다른 사항을 명시하고 싶다면?
  package.json에 있는 parcel 명령어의 후렴부에 --port <원하는 포트>같이 따로 명시해주면 다른 옵션을 추가할 수 있다. <br />
  ※ 자세하 사항은 <a href="https://parceljs.org/cli.html#commands">여기서</a> 확인 ※
