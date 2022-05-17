package Relacionamento;
public class Luta {
    public static void main(String[]args){
       Lutador l[] = new Lutador[6];
       Ringue r1 = new Ringue();
       l[0]= new Lutador("Adelso","Brasil",20,1.70f,20,0,60,0);
       l[1]= new Lutador("Afonso","Eua",30,1.72f,1,2,78.2f,2);
       l[2]= new Lutador("adelirio","Uruguai",22,1.90f,5,0,90,1);
       l[3]= new Lutador("marcio","Chile",40,1.70f,2,7,90,5);
       l[4]= new Lutador("reis","Canada",32,1.82f,50,5,62.2f,0);
       l[5]= new Lutador("julio","Russo",25,1.80f,0,0,50,0); 
       
      r1.marcarLuta(l[0], l[4]);
      r1.luta();
        System.out.println("\n\n\n");
      l[0].apresentar();
      l[4].apresentar();
    }
}
