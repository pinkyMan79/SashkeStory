# SashkeStory
import java.util.ArrayList;
import java.util.Scanner;

public class Main {

   private static  Scanner sc = new Scanner(System.in);

    public static void main(String[] args) {

        String line = sc.nextLine();

        ArrayList<Integer> array = new ArrayList<>();

        String charger = "";
        int num = 0;

        for (int i = 0; i < line.length() ; i++) {

            if (line.charAt(i) != ' '){

                charger += line.charAt(i);

            }else {

                num = Integer.parseInt(charger);
                array.add(num);
                num = 0;
                charger = "";

            }


        }

        Integer[] fastArray  = array.toArray(new Integer[array.size()]);
        String lineComplete = "";

        for (int i = 0; i < fastArray.length ; i++) {

            switch (fastArray[i]){

                case 1:
                    lineComplete += "А";
                    break;
                case 2:
                    lineComplete += "Б";
                    break;
                case 3:
                    lineComplete += "В";
                    break;
                case 4:
                    lineComplete += "Г";
                    break;
                case 5:
                    lineComplete += "Д";
                    break;
                case 6:
                    lineComplete += "Е";
                    break;
                case 7:
                    lineComplete += "Ё";
                    break;
                case 8:
                    lineComplete += "Ж";
                    break;
                case 9:
                    lineComplete += "З";
                    break;
                case 10:
                    lineComplete += "И";
                    break;
                case 11:
                    lineComplete += "Й";
                    break;
                case 12:
                    lineComplete += "К";
                    break;
                case 13:
                    lineComplete += "Л";
                    break;
                case 14:
                    lineComplete += "М";
                    break;
                case 15:
                    lineComplete += "Н";
                    break;
                case 16:
                    lineComplete += "О";
                    break;
                case 17:
                    lineComplete += "П";
                    break;
                case 18:
                    lineComplete += "Р";
                    break;
                case 19:
                    lineComplete += "С";
                    break;
                case 20:
                    lineComplete += "Т";
                    break;
                case 21:
                    lineComplete += "У";
                    break;
                case 22:
                    lineComplete += "Ф";
                    break;
                case 23:
                    lineComplete += "Х";
                    break;
                case 24:
                    lineComplete += "Ц";
                    break;
                case 25:
                    lineComplete += "Ч";
                    break;
                case 26:
                    lineComplete += "Ш";
                    break;
                case 27:
                    lineComplete += "Щ";
                    break;
                case 28:
                    lineComplete += "Ь";
                    break;
                case 29:
                    lineComplete += "Ъ";
                    break;
                case 30:
                    lineComplete += "Ы";
                    break;
                case 31:
                    lineComplete += "Э";
                    break;
                case 32:
                    lineComplete += "Ю";
                    break;
                case 33:
                    lineComplete += "Я";
                    break;



            }




            }
        System.out.println(lineComplete);

        }

    }


