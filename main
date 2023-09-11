import java.util.*; 

public class main { 
  public static void calculaBinario(int decimal){ 
    if(decimal == 1){ 
      System.out.print("1"); 
    }else{ 
      calculaBinario(decimal/2); 
      System.out.print(decimal%2); 
    } 
  } 

  public static void main(String[] args){ 
    Scanner sc = new Scanner(System.in); 
    System.out.print("Digite o valor do decimal: "); 
    int decimal = sc.nextInt(); 
    calculaBinario(decimal); 
    sc.close(); 
  } 
}
