# Mini-projeto
import java.util.Scanner;


    public class App {
        public static void main(String[] args) {
            String v = ("vitoria");
            String d =("derrota");
            

            System.out.print("Estamos na Copa do Mundo 2014. Após uma copa surpreedente e favoritas eliminadas na fase de grupos"+
            ", um grade exemplo disto é a campeã de 2010: a Espanha."+
            "\n Que fez uma campanha surpreende na África do Sul em 2010 "+
            "\n Ganhando da seleção Holandesa com um placar de 1x0"+
            "\n Joga acirrado com gol marcado nos acréscimos."+
            "\n A seleção brasileira ficou na metade do caminho,"+
            "\n perdendo nas quartas de finais de 2x1 para a seleção holandesa."+
            "\n Mas voltando ao que interessa, agora disputada no Brasil, Brasil 2014, é Copa do Mundo "+
            "\n e estamos nas Semifinais com a seleção brasileira."+
            "\n Os confrotos diretos dessas semifinais são entre: "+
            "\n Brasil x Alemanha"+
            "\n Holanda x Argentina");
                            
            Scanner time = new Scanner(System.in);

            System.out.print("\n ------ SEMIFINAL ------");

            System.out.print("\n Vamos agora acompanhar o jogo de Brasil x Alemanha.");
            System.out.print("\n O jogo termina com a ");
            String partida = time.nextLine();
            System.out.print("do Brasil.");

            if(partida.equals(v)){
               System.out.println("\n Impressioante o Brasil bate a Alemanha e está na final!" );
                
               System.out.print("\n Agora temos informações que Argentina venceu a Holanda nos pênaltis."+
               " Portanto, também está na final. Uma final épica sulamericana entre Brasil e Argentina"+
               "\n Estamos na grande final da copa do mundo 2014, "+
               "onde se enfrenta os dois times da América do Sul: Brasil x Argentina.");

               System.out.print("\n ----- FINAL -----");

               System.out.println("\n O Brasil sai do jogo com a ");
               String parti = time.nextLine();

               
               if(parti.equals(d)){
                  System.out.print(" \n O Brasil perde na final para Argentina com o placar de 1x0."+
                  " A Argentina é a campeã da copa do mundo 2014.");

                }
                else if(parti.equals(v)){
                  System.out.print("\n O Brasil é Hexa. Em uma campanha impecável é o campeão do mundo em 2014."+
                  "única seleção do mundo a cosquistar seis títulos mundiais. O Brasil vence a Argentina com o placar de 1x0");}

                
                }else if(partida.equals(d)){
               System.out.print(" \n O Brasil perde para Alemanha com placar de 7x1. "+
               "Apesar da decepçao, ainda poderá disputar o terceiro lugar com Holanda que perdeu para a Argentina com placar de 1x0");

               System.out.print("\n ------ TERCEIRO LUGAR ------");

               System.out.print("\n Estamos aqui no jogo de disputa pelo terceiro lugar entre Brasil x Holanda." + 
               "A seleção brasileira termina o jogo com a ");
               String part = time.nextLine();
               if(part.equals(v)){
                  System.out.print("\n O Brasil fica em terceiro lugar na Copa do Mundo 2014.");
               }
               if(part.equals(d)){
                  System.out.print("\n O Brasil perde para Holanda e Holanda fica com o terceiro lugar.");

               }
            }

                  System.out.print("\n Essa foi a Copa Mundo 2014, meus amigos! Muitíssimo obrigado pela a presença"+
                  " Nos vemos em 2018 na Rússia. Até mais!");

                  time.close();


                



            }

             
                       

            
            }
 
