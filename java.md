# java

## テストテンプレート

```java
public class TestWagomu {
  Wagomu test = new Wagomu();
  test.run();
}

class Wagomu {
  public void run() {
  }
}

```

## 標準入力の取得

```java
import java.util.Scanner;

// 1行だけ
String input = new Scanner( System.in).next();      //空白までを1行とする
String input = new Scanner( System.in).nextLine();  //改行までを1行とする
int input = new Scanner( System.in).nextInt();      //int型に変換して取得する

// 複数行をまとめて
Scanner scan = new Scanner( System.in);
while ( scan.hasNext() ) {
  String input = scan.nextLine();
}

```
