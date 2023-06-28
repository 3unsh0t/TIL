<h1>java에서 스택 사용하는법</h1>
<h3>Stack 선언</h3>
<ul>
import java.util.Stack; //import
Stack<Integer> stack = new Stack<>(); //int형 스택 선언
Stack<String> stack = new Stack<>(); //char형 스택 선언
</ul>
<h3>Stack 값 추가</h3>
<ul>
Stack<Integer> stack = new Stack<>(); //int형 스택 선언
stack.push(1);     // stack에 값 1 추가  
</ul>
<h3>Stack 값 삭제</h3>
<ul>
stack.pop();       // stack에 값 제거
stack.clear();     // stack의 전체 값 제거 (초기화)
</ul>
<h3>Stack의 상단값 출력</h3>
<ul>
stack.peek();     // stack의 가장 상단의 값 출력
</ul>
<h3>기타</h3>
<ul>
stack.size();      // stack의 크기 출력 : 2
stack.empty();     // stack이 비어있는제 check (비어있다면 true)
stack.contains(1) // stack에 1이 있는지 check (있다면 true)
</ul>

