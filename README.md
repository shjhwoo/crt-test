https://changhee.tistory.com/61

signCert.der 파일을 서버로 넘겨야만 함.
보안상으로도, js 상으로도 클라이언트에서 바로 변환하기 무리임.

해당 파일을 pem으로 바꾸고 해독해서 만료일자를 계산해서 돌려주도록 한다.

궁금한점

만료일자 정보는 어디에 저장해야 할까요?
그래야 접수단에서도 보여줄건데

중개서버 쪽에 이런 인증서 넣어두는거는 어떻게 하자는건지? 그림이 안그려진다.

인증서 파일 4개나 올리던데.. 파일 4개는 어디에다가 올리고 저장하는건지..
