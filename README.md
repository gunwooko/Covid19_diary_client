# [Covid19 Diary](https://bit.ly/30afmrl) (by C-Lab)
A diary for **communication**, building **empathy**, and even faster **recovery**.

It is a web platform where covid19-confirmed people write and share the recovery process in a diary format until they recover.

Through various people's diaries, you can indirectly experience how Covid19 can affect your life today.

Take a look at the changes in the lives of Pre-Covid19 and Post-Covid19.

You can check your changes from specific health data.

The whole world is suffering from Covid19, economic activity stops, and someone's family dies of Corona. Nevertheless, looking at the current society, many people do not seem to know the seriousness of Covid19.

To solve the above problems, Covid19 Diary gives people awareness of Covid19 and gives strength to many people who are struggling with this Pandemic.

## Stack Arquitecture
![stack (1)](https://user-images.githubusercontent.com/39975889/110224406-af327c80-7f1e-11eb-9104-d0388e46ff77.jpg)

## Functional flow
### Flow chart
- Client
   - Login & Signup
   
   ![1before-login](https://user-images.githubusercontent.com/39975889/110239470-5dbfd700-7f8a-11eb-984a-bf7f48f5dc78.png)

   - Post diary
   
   ![2post -diary](https://user-images.githubusercontent.com/39975889/110239474-62848b00-7f8a-11eb-9d7c-30080f84bad6.png)

   - My page
   
   ![3mypage](https://user-images.githubusercontent.com/39975889/110239476-67493f00-7f8a-11eb-9d46-dbd1093fdd64.png)

   - My diaries
   
   ![4mydiaries](https://user-images.githubusercontent.com/39975889/110239480-6c0df300-7f8a-11eb-9f79-d936f2661302.png)

   - Log out
   
   ![5logout](https://user-images.githubusercontent.com/39975889/110239483-70d2a700-7f8a-11eb-88d3-53b14d1cae2c.png)

   - Home page
   
   ![6homepage](https://user-images.githubusercontent.com/39975889/110239489-76c88800-7f8a-11eb-8deb-790b6749e740.png)

   - Diary detail
   
   ![7diarydetail](https://user-images.githubusercontent.com/39975889/110239497-7b8d3c00-7f8a-11eb-9c5f-ba5018b54b73.png)

- Server
   - Login flow
   
   ![s1-loginflow](https://user-images.githubusercontent.com/39975889/110239561-f48c9380-7f8a-11eb-9498-61c6a22ec48c.png)

   - Social login flow
   
   ![s2-sociallogin](https://user-images.githubusercontent.com/39975889/110239566-f7878400-7f8a-11eb-9d5f-54411ac52272.png)

   - Image flow
   
   ![s3-imageflow](https://user-images.githubusercontent.com/39975889/110239567-fa827480-7f8a-11eb-9d4e-808b6da506be.png)

   - API flow
   
   ![s4-apiflow](https://user-images.githubusercontent.com/39975889/110239568-fe15fb80-7f8a-11eb-9efa-9c09f3b60f5d.png)

### DB schema
![db_schema](https://user-images.githubusercontent.com/39975889/110224454-15b79a80-7f1f-11eb-8c6d-53cb9a47e55d.png)


## Commit Rule

1. 커밋전에 롤 첵크 필수 하기
2. 머지 전에 코드리뷰 받기
3. eslint:recommended 따르기
4. 커밋 메세지는 한글로 작성하기
5. 커밋 메세지 => "이모지 [커밋목적] 커밋제목"
6. 이모지 =>  
   :books: [패키지 설치]
   :sparkles: [추가]
   :hammer: [수정]
   :broken_heart: [버그]
   :nail_care: [CSS]
   :guitar: [기타]
