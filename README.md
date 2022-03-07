# jQuery
jQuery는 라이브러리 = 재사용을 위해서

- 엘리먼트를 선택하는 방법
- 선택된 엘리먼트를 효율적으로 제어할 수 있는 다양한 수단을 제공
- 자바스크립트 라이브러리 


- javaScriptEx.html vs jqeryEx.html


- 레퍼(wrapper)란?

    jQuery(엘리먼트 오브젝트 | 'CSS스타일 선택자')

    jQuery부분이 wrapper, 인자로 전달된 요소들에 jQuery의 기능성을 부가해서 반환

                <script type="text/javascript">
                //$를 함수의 지역변수로 선언해서 외부에 있을지 모르는 타 라이브러리의 $와의 충돌을 예방
                (function($){
                    $('body').html('hello world');
                })(jQuery)
                </script>