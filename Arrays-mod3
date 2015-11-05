import java.util.Arrays;
import java.util.Collections;
import java.util.Scanner;

//import java.utilsCollections;

public class arrr {
	public static void main(String[] args){

		
//Задача 1:
		
//1. Задать массив целых чисел длинной 10 эл.
int[] mass1 = {37, 55, 89, 33, 87, 26, 98, 14, 44, 18};
//2.1 Отсортировать числа в массиве Min-max
Arrays.sort(mass1);		
		
//3. Вывести на экран результат
System.out.println(Arrays.toString(mass1)); 
System.out.println();		

/*2.2 Отсортировать числа в массиве Max-min,
 * для этого используем тип Integer, вместо int
 */
Integer[] mass2 = new Integer[] {37, 55, 89, 33, 87, 26, 98, 14, 44, 18};			
		
Arrays.sort(mass2, Collections.reverseOrder());

//3.2. Вывести на экран результат
String s2 = Arrays.toString(mass2);
System.out.println(s2);

//4. Сделать возможность наполнения массива с клавиатуры
Scanner array_console = new Scanner(System.in);

Integer array_handmade1[] = new Integer[10];
System.out.println();
System.out.println("ВВедите 10 элементов массива array_handmade1");		 
//Вводим вручную каждый эелемент
array_handmade1 [0] = array_console.nextInt();
array_handmade1 [1] = array_console.nextInt();
array_handmade1 [2] = array_console.nextInt();
array_handmade1 [3] = array_console.nextInt();
array_handmade1 [4] = array_console.nextInt();
array_handmade1 [5] = array_console.nextInt();
array_handmade1 [6] = array_console.nextInt();
array_handmade1 [7] = array_console.nextInt();
array_handmade1 [8] = array_console.nextInt();
array_handmade1 [9] = array_console.nextInt();

//Сортировка с меньшего по большее
Arrays.sort(array_handmade1);


System.out.println();
System.out.println("Массив отсортирован с меньшего по большее");
System.out.println(Arrays.toString(array_handmade1));

//Сортировка с большего по меньшее
//использую тип Integer, скопируем массив array_handmade2 из array_handmade1
Integer array_handmade2[] = Arrays.copyOf(array_handmade1,10);
Arrays.sort(array_handmade2, Collections.reverseOrder());

System.out.println();
System.out.println("Массив отсортирован с большего по меньшее");
System.out.println(Arrays.toString(array_handmade2));


//Задача 2:

//1. Задать массив целых чисел длинной N эл. - N - введется с консоли, элементы - генерацией случайных чисел
System.out.println();
System.out.println("Введите количество элементов массива array_2");
int N = array_console.nextInt();
int array_2[] = new int [N];
for(int i_2=0; i_2<N; i_2++){
	array_2[i_2]=(int)(Math.random()*100+1);
}
System.out.println();
System.out.println("Полученный массив array_2");
System.out.println(Arrays.toString(array_2));
//2. Поменять 1-й и последний элемент местами.
int first = array_2[0];
array_2[0] = array_2[N-1];
array_2[N-1] = first;

//3. Вывести массив на экран.
System.out.println();
System.out.println("В массиве array_2 первый элемент заменен на последний");
System.out.println(Arrays.toString(array_2));



//Задача 3:
//1. Ввести с клавиатуры массив из 10 чисел. - Имя array_3
Integer array_3[] = new Integer[10];
System.out.println();
System.out.println("ВВедите 10 элементов массива array_3");		 

for(int i_3=0; i_3<10; i_3++){
	
	array_3[i_3]=array_console.nextInt();
}
System.out.println();
System.out.println("Полученный массив array_3");	
System.out.println(Arrays.toString(array_3));
//2. Разбить его на 2 массива равной длинны.

Integer [] array_first = Arrays.copyOfRange(array_3, 0, 5);
Integer [] array_second = Arrays.copyOfRange(array_3, 5, 10);
System.out.println();
System.out.println("Разобьем массив array_3 на массивы array_first и array_second ");
System.out.println();
System.out.println("Первая часть - 5 элементов");
System.out.println(Arrays.toString(array_first));
System.out.println();
System.out.println("Вторая часть - 5 элементов");
System.out.println(Arrays.toString(array_second));

//3. Отсортировать каждую из половинок и вывести их содержимое на экран.
		//array_first
		//array_second
		//Сортировка и вывод с меньшего по большее
		Arrays.sort(array_first);
		Arrays.sort(array_second);
		
		System.out.println();
		System.out.println("Сортировка Min-Max Первой части");
		System.out.println(Arrays.toString(array_first));
		System.out.println();
		System.out.println("Сортировка Min-Max Второй части");
		System.out.println(Arrays.toString(array_second));
			
		//Сортировка с большего по меньшее
		
	Arrays.sort(array_first, Collections.reverseOrder());
	Arrays.sort(array_second, Collections.reverseOrder());
	System.out.println();
	System.out.println("Сортировка Max-Min Первой части ");
	System.out.println(Arrays.toString(array_first));
	System.out.println();
	System.out.println("Сортировка Max-Min Второй части ");
	System.out.println(Arrays.toString(array_second));

//Задача 4:	
//Среднее арифметическое элементов массива
//N4 - количество элементов, i_4 - индекс
				System.out.println();
		System.out.println("Введите число элементов массива array4");	
		int N4 = array_console.nextInt();
		float array_4 [] = new float [N4];

		for(int i_4=0; i_4<N4; i_4++){
			array_4[i_4]=(float)(Math.random()*10+10);
		}
		System.out.println();
		System.out.println("Получаем массив array_4");
		System.out.println(Arrays.toString(array_4));
	
		//Вычисляем Среднее арифметичное	
		//i_4 - индекс
float Srednee=0;
for(int i_4 = 0; i_4<N4; i_4++){

Srednee+=array_4[i_4]/N4;
}
System.out.println();
System.out.println("Cреднее арифметическое введенного массива array_4 =  " + Srednee);
	
	}
}
