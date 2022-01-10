1. 로컬에서 가장 최근 커밋 내용 수정

![기존 커밋 로그](https://user-images.githubusercontent.com/47783128/148753957-110f8be2-5533-432c-bef5-82453ecfb7c1.png)

2. git commit --amend

![명령어](https://user-images.githubusercontent.com/47783128/148754064-d22e9012-cd1e-42e2-ae2c-fbd9800d8c4c.png)

3. 커밋 내용 수정

![커밋 내용 수정](https://user-images.githubusercontent.com/47783128/148754134-0b0e2818-88be-4ffa-b822-2ea5dacfc4cb.png)

4. 기존 커밋  SHA-1 값이 바뀜 => 유의해서 수정


![KakaoTalk_20220110_194013195](https://user-images.githubusercontent.com/47783128/148754249-93718bab-44e0-4d50-8c99-ed917a511f5e.png)

5. 4.번내용 추가로 마지막 커밋에 추가하고 싶음

![image](https://user-images.githubusercontent.com/47783128/148754444-970aae89-45b3-4047-8489-bb6478904246.png)


![KakaoTalk_20220110_194013195](https://user-images.githubusercontent.com/47783128/148754600-f4aac92c-c3ab-4437-9179-379a5f079ec7.png)

6. 커밋 내용이 충분하고, 단순히 오탈자면 --no-edit 옵션 쓰기

![image](https://user-images.githubusercontent.com/47783128/148754770-33822c22-6cb7-4281-bbc1-c548002eb9fe.png)


=> 계속해서 SHA-1 값이 바뀌기 때문에 원격에 push하기전에 잘 생각해서 push

push가 되고서 수정되면 협력하기 힘들다고 pro git에 나옴 [7.6 Git 도구 - 히스토리 단장하기](https://git-scm.com/book/ko/v2/Git-%EB%8F%84%EA%B5%AC-%ED%9E%88%EC%8A%A4%ED%86%A0%EB%A6%AC-%EB%8B%A8%EC%9E%A5%ED%95%98%EA%B8%B0)
