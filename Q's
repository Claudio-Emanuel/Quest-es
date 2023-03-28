// Q1
import 'dart:io';

void main(){
  //Criação das variáveis
  double salario;
  double imposto;
  double s_final;

  //Inserção do Input e converção
  print("Escreva o seu salario:");
  String? input= stdin.readLineSync();
  salario= double.parse(input!);

  //Cálculos e resultados 
  imposto=salario*0.10;
  s_final=salario-imposto;

  print("Salario Bruto: $salario \n Imposto: $imposto \n Salario liquido ou final: $s_final");
}

//Q2
import 'dart:io';

void main(){
  double C;
  double F;
  double K;

  print("Digite a temperatura desejada em Celsius:");
  String? input= stdin.readLineSync();
  C= double.parse(input!);

  F=C*1.8+32;
  K=(F+459.67) / 1.8;
  print("C: $C \n F: $F \n K: $K");

}

//Q3
import 'dart:io';

void main(){
  //Declarar variáveis
  int Seg;
  int Min;
  int Hr;
  //Inserção e Modificação do Input
  print("Digite um tempo em segundos:");
  String? input= stdin.readLineSync();
  Seg= int.parse(input!);
  //Cálculos e Resultados
  Hr= (Seg ~/ 3600);
  Min= (Seg % 3600 ~/60);
  Seg= Seg %  3600 %60 %60;
  print("$Hr"+":"+"$Min"+":"+"$Seg");
}

//Q4 
import 'dart:io';

void main(){
  int cem;
  int cin;
  int vin;
  int dez;
  int doi;
  int um;
  int n_cedulas;

  print("Digite o numero de cedulas:");
  String? input= stdin.readLineSync();
  n_cedulas=int.parse(input!);

  cem= n_cedulas ~/ 100;
  cin= n_cedulas % 100 ~/50;
  vin= n_cedulas % 100 %50 ~/20;
  dez= n_cedulas % 100 %50 %20 ~/10;
  doi= n_cedulas % 100 %50 %20 %10 ~/2;
  um= n_cedulas % 100 %50 %20 %10 %2 ~/1;

  print("Notas de 100: $cem \n Notas de 50: $cin \n Notas de 20: $vin \n Notas de 10: $dez \n Notas de 2: $doi \n Notas de 1: $um");

}
