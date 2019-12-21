# java-chicken-2019
<h2>기능 요구사항</h2>
<ul>
<li>치킨집사장님이사용하는간단한포스(POS)프로그램을구현한다.</li>
<li>주문등록,결제하기,프로그램종료기능을가진다.</li>
<li>메뉴기본정보가주어지며메뉴번호,종류,이름,가격을가진다.</li>
<li>테이블기본정보가주어지며테이블번호를가진다.</li>
<li>한테이블에서주문할수있는한메뉴의최대수량은99개이다.</li>
<li>주문이등록된테이블은결제가이루어지기전까지테이블목록에별도로표시한다.</li>
<li>주문내역에대한계산을할때는결제유형에따라할인율이달라진다.</li>
<ul>
<li>치킨종류메뉴의수량합이10개가넘는경우10,000원씩할인된다.</li>
<li>e.g.10개는10,000원할인,20개는20,000원할인</li>
<li>현금결제는5%가할인되며할인된금액에서한번더할인이가능하다.</li>
</ul>
<li>주문혹은결제가불가능한경우그이유를보여주고,다시주문혹은결제가가능하도록해야한다.</li>
<li>최종결제금액을보여준다.</li>
</ul>


<h2>기능 구현 목록</h2>
<ul>
<li>주문등록, 결제하기, 프로그램 종료 구현</li>
<li>결제 전 테이블목록 별도표시 구현</li>
<li>한 테이블 메뉴 최대 수량 99로 제한</li>
<li>결제 할인율 적용(현금시 5%할인) + 치킨 종류로 10마리 단위로 10000원씩 할인</li>
<li>결제 불가능의 경우 예외처리</li>
<li>최종 결제 금액 출력</li>
</ul>
