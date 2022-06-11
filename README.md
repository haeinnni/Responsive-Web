# Portfolio website clone

기간: 2022.03
HTML, CSS, JavaScript로 동적인 반응형 웹사이트 구현. 

----------

[구현 기능]

-   Transparent navbar
-   Scroll to section
-   Arrow up button
-   Project filtering & animation

----------

[문제해결과정]

-   position: sticky  
https://blog.naver.com/cc6575448/222673186649  
부모 노드 안에서만 움직인다. (blue-box)  
위치값을 지정해줘야 한다. 만약, 값을 지정해주지 않는다면, relative positioning과 다를게 없다.   
[브라우저 호환성] Internet Explorer에서는 호환되지 않는다.  

- Transformable element   
https://blog.naver.com/cc6575448/222673640939  
목표 : 아이콘 border가 아닌 아이콘에 호버가 되면 transform  
문제 : color만 변경되고 transform이 작동되지 않음.  
해결 : box-type을 inline-block으로 변경.(inline box는 transformable elements 가 아니다.)
