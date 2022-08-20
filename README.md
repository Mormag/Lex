import java.util.Scanner;

class Main {


    public static void main(String[] args){
    String[][] massive =  {{"1", "2", "3"},
                        {"4", "5", "6"},
                        {"7", "8", "9"}};
        Scanner s = new Scanner(System.in);



        for (int i = 0; i <massive.length ; i++) {
            for (int j = 0; j < massive[i].length ; j++) {
                System.out.print(massive[i][j] + " ");
            }
            System.out.println();

            }
        System.out.println("X move");
        int move1 = s.nextInt();
        if (move1 == 1){
            massive[0][0] = "x";}
        if (move1 == 2){
            massive[0][1] = "x";}
        if (move1 == 3){
            massive[0][2] = "x";}
        if (move1 == 4){
            massive[1][0] = "x";}
        if (move1 == 5){
            massive[1][1] = "x";}
        if (move1 == 6){
            massive[1][2] = "x";}
        if (move1 == 7){
            massive[2][0] = "x";}
        if (move1 == 8){
            massive[2][1] = "x";}
        if (move1 == 9){
            massive[2][2] = "x";}

        for (int i = 0; i <massive.length ; i++) {
            for (int j = 0; j < massive[i].length ; j++) {
                System.out.print(massive[i][j] + " ");
            }
            System.out.println();
}
        System.out.println("O move");
        while (true) {
            int move2 = s.nextInt();
            if (move2 == move1) {
                System.out.println("This cell is lock");
                continue;
            }

            if (move2 == 1){
            massive[0][0] = "o";}
        if (move2 == 2){
            massive[0][1] = "o";}
        if (move2 == 3){
            massive[0][2] = "o";}
        if (move2 == 4){
            massive[1][0] = "o";}
        if (move2 == 5){
            massive[1][1] = "o";}
        if (move2 == 6){
            massive[1][2] = "o";}
        if (move2 == 7){
            massive[2][0] = "o";}
        if (move2 == 8){
            massive[2][1] = "o";}
        if (move2 == 9){
            massive[2][2] = "o";}

        for (int i = 0; i <massive.length ; i++) {
            for (int j = 0; j < massive[i].length ; j++) {
                System.out.print(massive[i][j] + " ");
            }
            System.out.println();
        }

        System.out.println("X move");
            while (true) {
                int move3 = s.nextInt();
                if (move3 == move1 || move3 == move2) {
                    System.out.println("This cell is lock");
                    continue;}
        if (move3 == 1){
            massive[0][0] = "x";}
        if (move3 == 2){
            massive[0][1] = "x";}
        if (move3 == 3){
            massive[0][2] = "x";}
        if (move3 == 4){
            massive[1][0] = "x";}
        if (move3 == 5){
            massive[1][1] = "x";}
        if (move3 == 6){
            massive[1][2] = "x";}
        if (move3 == 7){
            massive[2][0] = "x";}
        if (move3 == 8){
            massive[2][1] = "x";}
        if (move3 == 9){
            massive[2][2] = "x";}

        for (int i = 0; i <massive.length ; i++) {
            for (int j = 0; j < massive[i].length ; j++) {
                System.out.print(massive[i][j] + " ");
            }
            System.out.println();
        }

        System.out.println("O move");
                while (true) {
                    int move4 = s.nextInt();
                    if (move4 == move1 || move4 == move2 || move4 == move3) {
                        System.out.println("This cell is lock");
                        continue;}
        if (move4 == 1){
            massive[0][0] = "o";}
        if (move4 == 2){
            massive[0][1] = "o";}
        if (move4 == 3){
            massive[0][2] = "o";}
        if (move4 == 4){
            massive[1][0] = "o";}
        if (move4 == 5){
            massive[1][1] = "o";}
        if (move4 == 6){
            massive[1][2] = "o";}
        if (move4 == 7){
            massive[2][0] = "o";}
        if (move4 == 8){
            massive[2][1] = "o";}
        if (move4 == 9){
            massive[2][2] = "o";}

        for (int i = 0; i <massive.length ; i++) {
            for (int j = 0; j < massive[i].length ; j++) {
                System.out.print(massive[i][j] + " ");
            }
            System.out.println();
        }

        System.out.println("X move");
                    while (true) {
                        int move5 = s.nextInt();
                        if (move5 == move1 || move5 == move2 || move5 == move3 || move5 == move4) {
                            System.out.println("This cell is lock");
                            continue;}
        if (move5 == 1){
            massive[0][0] = "x";}
        if (move5 == 2){
            massive[0][1] = "x";}
        if (move5 == 3){
            massive[0][2] = "x";}
        if (move5 == 4){
            massive[1][0] = "x";}
        if (move5 == 5){
            massive[1][1] = "x";}
        if (move5 == 6){
            massive[1][2] = "x";}
        if (move5 == 7){
            massive[2][0] = "x";}
        if (move5 == 8){
            massive[2][1] = "x";}
        if (move5 == 9){
            massive[2][2] = "x";}

        for (int i = 0; i <massive.length ; i++) {
            for (int j = 0; j < massive[i].length ; j++) {
                System.out.print(massive[i][j] + " ");
            }
            System.out.println();

        }
                        if(
                             ((massive[0][0] == massive[0][1]) && (massive[0][1] == massive[0][2])) ||
                            ((massive[1][0] == massive[1][1]) && (massive[1][1] == massive[1][2])) ||
                            ((massive[2][0] == massive[2][1]) && (massive[2][1] == massive[2][2])) ||
                            ((massive[0][0] == massive[1][0]) && (massive[1][0] == massive[2][0])) ||
                            ((massive[0][1] == massive[1][1]) && (massive[1][1] == massive[2][1])) ||
                            ((massive[0][2] == massive[1][2]) && (massive[1][2] == massive[2][2])) ||
                            ((massive[0][0] == massive[1][1]) && (massive[1][1] == massive[2][2])) ||
                            ((massive[0][2] == massive[1][1]) && (massive[1][1] == massive[2][0]))){
                            System.out.println("X WINER");
                            return;}
        System.out.println("O move");
                        while (true) {
                            int move6 = s.nextInt();
                            if (move6 == move1 || move6 == move2 || move6 == move3 || move6 == move4 || move6 == move5) {
                                System.out.println("This cell is lock");
                                continue;}
        if (move6 == 1){
            massive[0][0] = "o";}
        if (move6 == 2){
            massive[0][1] = "o";}
        if (move6 == 3){
            massive[0][2] = "o";}
        if (move6 == 4){
            massive[1][0] = "o";}
        if (move6 == 5){
            massive[1][1] = "o";}
        if (move6 == 6){
            massive[1][2] = "o";}
        if (move6 == 7){
            massive[2][0] = "o";}
        if (move6 == 8){
            massive[2][1] = "o";}
        if (move6 == 9){
            massive[2][2] = "o";}
                            if(
                                    ((massive[0][0] == massive[0][1]) && (massive[0][1] == massive[0][2])) ||
                                            ((massive[1][0] == massive[1][1]) && (massive[1][1] == massive[1][2])) ||
                                            ((massive[2][0] == massive[2][1]) && (massive[2][1] == massive[2][2])) ||
                                            ((massive[0][0] == massive[1][0]) && (massive[1][0] == massive[2][0])) ||
                                            ((massive[0][1] == massive[1][1]) && (massive[1][1] == massive[2][1])) ||
                                            ((massive[0][2] == massive[1][2]) && (massive[1][2] == massive[2][2])) ||
                                            ((massive[0][0] == massive[1][1]) && (massive[1][1] == massive[2][2])) ||
                                            ((massive[0][2] == massive[1][1]) && (massive[1][1] == massive[2][0]))){
                                System.out.println("O WINER");
                                return;}


        for (int i = 0; i <massive.length ; i++) {
            for (int j = 0; j < massive[i].length ; j++) {
                System.out.print(massive[i][j] + " ");
            }
            System.out.println();
        }

        System.out.println("X move");
                            while (true) {
                                int move7 = s.nextInt();
                                if (move7 == move1 || move7 == move2 || move7 == move3 || move7 == move4 || move7 == move5 || move7 == move6) {
                                    System.out.println("This cell is lock");
                                    continue;}
        if (move7 == 1){
            massive[0][0] = "x";}
        if (move7 == 2){
            massive[0][1] = "x";}
        if (move7 == 3){
            massive[0][2] = "x";}
        if (move7 == 4){
            massive[1][0] = "x";}
        if (move7 == 5){
            massive[1][1] = "x";}
        if (move7 == 6){
            massive[1][2] = "x";}
        if (move7 == 7){
            massive[2][0] = "x";}
        if (move7 == 8){
            massive[2][1] = "x";}
        if (move7 == 9){
            massive[2][2] = "x";}
                                if(
                                        ((massive[0][0] == massive[0][1]) && (massive[0][1] == massive[0][2])) ||
                                                ((massive[1][0] == massive[1][1]) && (massive[1][1] == massive[1][2])) ||
                                                ((massive[2][0] == massive[2][1]) && (massive[2][1] == massive[2][2])) ||
                                                ((massive[0][0] == massive[1][0]) && (massive[1][0] == massive[2][0])) ||
                                                ((massive[0][1] == massive[1][1]) && (massive[1][1] == massive[2][1])) ||
                                                ((massive[0][2] == massive[1][2]) && (massive[1][2] == massive[2][2])) ||
                                                ((massive[0][0] == massive[1][1]) && (massive[1][1] == massive[2][2])) ||
                                                ((massive[0][2] == massive[1][1]) && (massive[1][1] == massive[2][0]))){
                                    System.out.println("X WINER");
                                    return;}
        for (int i = 0; i <massive.length ; i++) {
            for (int j = 0; j < massive[i].length ; j++) {
                System.out.print(massive[i][j] + " ");
            }
            System.out.println();
        }

        System.out.println("O move");
        while (true) {
            int move8 = s.nextInt();
            if (move8 == move1 || move8 == move2 || move8 == move3 || move8 == move4 || move8 == move5 || move8 == move6 || move8 == move7) {
                System.out.println("This cell is lock");
                continue;}
        if (move8 == 1){
            massive[0][0] = "o";}
        if (move8 == 2){
            massive[0][1] = "o";}
        if (move8 == 3){
            massive[0][2] = "o";}
        if (move8 == 4){
            massive[1][0] = "o";}
        if (move8 == 5){
            massive[1][1] = "o";}
        if (move8 == 6){
            massive[1][2] = "o";}
        if (move8 == 7){
            massive[2][0] = "o";}
        if (move8 == 8){
            massive[2][1] = "o";}
        if (move8 == 9){
            massive[2][2] = "o";}
            if(
                    ((massive[0][0] == massive[0][1]) && (massive[0][1] == massive[0][2])) ||
                            ((massive[1][0] == massive[1][1]) && (massive[1][1] == massive[1][2])) ||
                            ((massive[2][0] == massive[2][1]) && (massive[2][1] == massive[2][2])) ||
                            ((massive[0][0] == massive[1][0]) && (massive[1][0] == massive[2][0])) ||
                            ((massive[0][1] == massive[1][1]) && (massive[1][1] == massive[2][1])) ||
                            ((massive[0][2] == massive[1][2]) && (massive[1][2] == massive[2][2])) ||
                            ((massive[0][0] == massive[1][1]) && (massive[1][1] == massive[2][2])) ||
                            ((massive[0][2] == massive[1][1]) && (massive[1][1] == massive[2][0]))){
                System.out.println("O WINER");
                return;}

        for (int i = 0; i <massive.length ; i++) {
            for (int j = 0; j < massive[i].length ; j++) {
                System.out.print(massive[i][j] + " ");
            }
            System.out.println();
        }

        System.out.println("X move");
            while (true) {
                int move9 = s.nextInt();
                if (move9 == move1 || move9 == move2 || move9 == move3 || move9 == move4 || move9 == move5 || move9 == move6 || move9 == move7 || move9 == move8) {
                    System.out.println("This cell is lock");
                    continue;}
        if (move9 == 1){
            massive[0][0] = "x";}
        if (move9 == 2){
            massive[0][1] = "x";}
        if (move9 == 3){
            massive[0][2] = "x";}
        if (move9 == 4){
            massive[1][0] = "x";}
        if (move9 == 5){
            massive[1][1] = "x";}
        if (move9 == 6){
            massive[1][2] = "x";}
        if (move9 == 7){
            massive[2][0] = "x";}
        if (move9 == 8){
            massive[2][1] = "x";}
        if (move9 == 9){
            massive[2][2] = "x";}
                if(
                        ((massive[0][0] == massive[0][1]) && (massive[0][1] == massive[0][2])) ||
                                ((massive[1][0] == massive[1][1]) && (massive[1][1] == massive[1][2])) ||
                                ((massive[2][0] == massive[2][1]) && (massive[2][1] == massive[2][2])) ||
                                ((massive[0][0] == massive[1][0]) && (massive[1][0] == massive[2][0])) ||
                                ((massive[0][1] == massive[1][1]) && (massive[1][1] == massive[2][1])) ||
                                ((massive[0][2] == massive[1][2]) && (massive[1][2] == massive[2][2])) ||
                                ((massive[0][0] == massive[1][1]) && (massive[1][1] == massive[2][2])) ||
                                ((massive[0][2] == massive[1][1]) && (massive[1][1] == massive[2][0]))){
                    System.out.println("X WINER");
                    return;}
                else System.out.println("NO ONE WIN");
                return;

        }





            }
                            }
                        }
                        }
                    }
                }
            }


    }
}





