# JavaExtendedForStatement
拡張for文

## 処理
配列の内容を拡張for文を使って出力します。

## コード
```
public class sample13 {

	public static void main(String[] args) {
		String[] team = {"佐藤","鈴木","田中","岸田","有森"};
		for (String member : team) {
			System.out.println(member + "さん");
		}

	}

}
```

## 出力結果
```
佐藤さん  
鈴木さん  
田中さん  
岸田さん  
有森さん
```
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| 統合開発環境(IDE) | Eclipse 4.7.0 Oxygen |
| 開発言語 | Java8 |
