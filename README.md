# 自分のBMIを知って健康になろう！！
### 身長と体重を入力することでBMI値の計算をするプログラムです。

import java.util.*;

public class Main{
	public static void main (String[] args ){
		Scanner stdIn = new Scanner(System.in);

        double sintyou = stdIn.nextDouble(); 
        double taijyu = stdIn.nextDouble(); 

		double bmi = taijyu / Math.pow(sintyou, 2);

		System.out.println(bmi);
	}
}
