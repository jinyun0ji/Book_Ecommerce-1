# Book_Ecommerce 중고거래 서적 사이트
## Refurbished Books



+ 매학기가 시작될때마다 교재를 사야하는 부담감을 조금 줄여주기 위한 사이트를 구상했습니다. 이전 학기에 들었던 수업에서 썼던 교재를 사고 팔 수 있는 중고서적 거래사이트입니다.

+ React JS와 Firebase등을 통해 여러가지 기능을 구현할 사이트의 이름은 “Refurbished Books” 입니다.

+ 기존의 중고거래 사이트들이 여러 개 존재하지만 각각 실제로 사용해본 결과, 몇가지의 단점이 있었기 때문에 이번 프로젝트에서 그것들을 보안해보려고 합니다.

![제품 홈페이지 시연이미지](<https://user-images.githubusercontent.com/83345831/143448306-12f251e1-8cd1-442e-8312-0550a3978fb4.png>)


*프로젝트 내용
-----------------------------------------------------------------------------------

+ 업로드되어 있는 책 목록 페이지(홈페이지)에서 구매를 희망하는 책을 오른쪽 하단에 있는 아이콘을 클릭하여 장바구니에 저장합니다.

+ 이후 결제 혹은 장바구니에 추가한 물건을 수정하기 위해서는, 페이지의 오른쪽 상단에 있는 장바구니 아이콘을 클릭하여 장바구니 페이지로 이동합니다.

+ 장바구니 페이지에서 구매하고자 하는 물건을 제외한 모든 물건을 제거한 뒤 하단에 위치한 결제 아이콘을 클릭합니다.

+ 이어서 이동된 주소 페이지에서 개인정보를 입력하고 난 뒤 다음 버튼을 누르면 마지막으로 결제페이지로 이동하게 됩니다.

+ 결제페이지에서 카드결제 관련 정보를 입력하시면 주문을 완료하게 됩니다.

+ 책 목록 페이지에서는 책 표지, 책 이름, 가격이 제공되며 장바구니 페이지에서는 표지, 책 이름, 가격, 수량 그리고 사용자가 결제할 총합 비용을 제공합니다.

+ 직접 사용자가 업로드하는 기능이 있습니다. 홈페이지에서 장바구니 아이콘 옆에 있는 업로드 버튼을 누르면 업로드 페이지로 이동하게 됩니다.

+ 업로드 페이지에서는 입력란 3개와 파일추가란이 하나가 있습니다. 각각 책제목, 가격, 장르에 대해서 입력하면 되고 책의 이미지를 첨부하면 됩니다. 모든 이미지 종류 파일 가능합니다.

+ 업로드 버튼을 누르고 홈페이지로 이동하면 업로드 된 책이 실시간으로 렌더링되어서 나은 것을 확인하실 수 있습니다.

+ 결제 정보를 다 입력하면 결제가 끝나게 되고 왼쪽 상단의 Refurbished Books를 누르면 메인 화면으로 돌아가고, 장바구니에 담긴 서적들은 초기화가 되게됩니다.

+ 결제에 대한 정보들은 Firebase에 넘어와 정보들이 기록되어 누가, 어떤 책을, 얼마나 시켰는지 등 자세한 정보를 알 수 있습니다.


*설치 방법
-------------------------------------------------------------------------------------

1. Node.js LTS 버전으로 설치, 깃허브에서 레지스토리 주소를 복사하고 visual studio code에 로드하고 터미널을 연 뒤 다음을 입력합니다.


2. npm install react react-router-dom react-hook-form firebase


*사용 방법
------------------------------------------------------------------------------------------

+ 위 설명을 따라 설치를 완료하고, 터미널에 npm start를 입력하면 홈페이지에 접속할 수 있습니다.
