import java.util.Scanner;

public class Main {
    public static void main(String[] args){
        int[][] arr = new int[3][3];
        arr[0][0] = 1;
        arr[0][1] = 2;
        arr[0][2] = 3;
        arr[1][0] = 4;
        arr[1][1] = 5;
        arr[1][2] = 6;
        arr[2][0] = 7;
        arr[2][1] = 8;
        arr[2][2] = 9;

        Scanner s = new Scanner(System.in);
        System.out.println("|"+arr[0][0]+"|"+arr[0][1]+"|"+arr[0][2]+"|");
        System.out.println("|"+arr[1][0]+"|"+arr[1][1]+"|"+arr[1][2]+"|");
        System.out.println("|"+arr[2][0]+"|"+arr[2][1]+"|"+arr[2][2]+"|");

        System.out.println("Move X");
        System.out.println("Choice number from 1-9");

        String one = "1";
        String two = "2";
        String trea = "3";
        String four = "4";
        String five = "5";
        String six = "6";
        String seven = "7";
        String eight = "8";
        String nine = "9";
        String x = "x";
        String o = "o";



        int move1 = s.nextInt();
        if (move1 == 1) {one = x;}
        else if (move1 == 2) {two = x;}
        else if (move1 == 3) {trea = x;}
        else if (move1 == 4) {four = x;}
        else if (move1 == 5) {five = x;}
        else if (move1 == 6) {six = x;}
        else if(move1 == 7) {seven = x;}
        else if (move1 == 8) {eight = x;}
        else if (move1 == 9) {nine = x;}
        System.out.println("|"+one+"|"+two+"|"+trea+"|");
        System.out.println("|"+four+"|"+five+"|"+six+"|");
        System.out.println("|"+seven+"|"+eight+"|"+nine+"|");


        System.out.println("Move Y");
        System.out.println("Choice number from 1-9");


        while (true) {
        int move2 = s.nextInt();
            if (move2 == move1) {
                System.out.println("This cell is lock");
                return;}

            if (move2 == 1) {one = o;}
            else if (move2 == 2) {two = o;}
            else if (move2 == 3) {trea = o;}
            else if (move2 == 4) {four = o;}
            else if (move2 == 5) {five = o;}
            else if (move2 == 6) {six = o;}
            else if(move2 == 7) {seven = o;}
            else if (move2 == 8) {eight = o;}
            else if (move2 == 9) {nine = o;}
            System.out.println("|"+one+"|"+two+"|"+trea+"|");
            System.out.println("|"+four+"|"+five+"|"+six+"|");
            System.out.println("|"+seven+"|"+eight+"|"+nine+"|");

        System.out.println("Move X");
        System.out.println("Choice number from 1-9");

        int move3 = s.nextInt();
        if (move3 == move1)  {
            System.out.println("This cell is lock");
            return;}
        else if (move3 == move2)  {
            System.out.println("This cell is lock");
            return;}
            if (move3 == 1) {one = x;}
            else if (move3 == 2) {two = x;}
            else if (move3 == 3) {trea = x;}
            else if (move3 == 4) {four = x;}
            else if (move3 == 5) {five = x;}
            else if (move3 == 6) {six = x;}
            else if(move3 == 7) {seven = x;}
            else if (move3 == 8) {eight = x;}
            else if (move3 == 9) {nine = x;}
            System.out.println("|"+one+"|"+two+"|"+trea+"|");
            System.out.println("|"+four+"|"+five+"|"+six+"|");
            System.out.println("|"+seven+"|"+eight+"|"+nine+"|");

        System.out.println("Move Y");
        System.out.println("Choice number from 1-9");

        int move4 = s.nextInt();
        if (move4 == move1)  {
            System.out.println("This cell is lock");
            return;}
        else if (move4 == move2)  {
            System.out.println("This cell is lock");
            return;}
        else if (move4 == move3)  {
            System.out.println("This cell is lock");
            return;}
            if (move4 == 1) {one = o;}
            else if (move4 == 2) {two = o;}
            else if (move4 == 3) {trea = o;}
            else if (move4 == 4) {four = o;}
            else if (move4 == 5) {five = o;}
            else if (move4 == 6) {six = o;}
            else if(move4 == 7) {seven = o;}
            else if (move4 == 8) {eight = o;}
            else if (move4 == 9) {nine = o;}
            System.out.println("|"+one+"|"+two+"|"+trea+"|");
            System.out.println("|"+four+"|"+five+"|"+six+"|");
            System.out.println("|"+seven+"|"+eight+"|"+nine+"|");

        System.out.println("Move X");
        System.out.println("Choice number from 1-9");

        int move5 = s.nextInt();
        if (move5 == move1)  {
            System.out.println("This cell is lock");
            return;}
        else if (move5 == move2)  {
            System.out.println("This cell is lock");
            return;}
        else if (move5 == move3)  {
            System.out.println("This cell is lock");
            return;}
        else if (move5 == move4)  {
            System.out.println("This cell is lock");
            return;}
            if (move5 == 1) {one = x;}
            else if (move5 == 2) {two = x;}
            else if (move5 == 3) {trea = x;}
            else if (move5 == 4) {four = x;}
            else if (move5 == 5) {five = x;}
            else if (move5 == 6) {six = x;}
            else if(move5 == 7) {seven = x;}
            else if (move5 == 8) {eight = x;}
            else if (move5 == 9) {nine = x;}
            System.out.println("|"+one+"|"+two+"|"+trea+"|");
            System.out.println("|"+four+"|"+five+"|"+six+"|");
            System.out.println("|"+seven+"|"+eight+"|"+nine+"|");

        if (one == two && two == trea);{System.out.println("X Win");}
        if (four == five && five == six);{System.out.println("X Win");}
        if (seven == eight && eight == nine);{System.out.println("X Win");}
        if (one == four && four == seven);{System.out.println("X Win");}
        if (two == five && five == eight);{System.out.println("X Win");}
        if (trea == six && six == nine);{System.out.println("X Win");}
        if (one == five && five == nine);{System.out.println("X Win");}
        if (trea == five && five == seven);{System.out.println("X Win");}

            System.out.println("Move Y");
            System.out.println("Choice number from 1-9");

        int move6 = s.nextInt();
        if (move6 == move1)  {
            System.out.println("This cell is lock");
            return;}
        else if (move6 == move2)  {
            System.out.println("This cell is lock");
            return;}
        else if (move6 == move3)  {
            System.out.println("This cell is lock");
            return;}
        else if (move6 == move4)  {
            System.out.println("This cell is lock");
            return;}
        else if (move6 == move5)  {
            System.out.println("This cell is lock");
            return;}
            if (move6 == 1) {one = o;}
            else if (move6 == 2) {two = o;}
            else if (move6 == 3) {trea = o;}
            else if (move6 == 4) {four = o;}
            else if (move6 == 5) {five = o;}
            else if (move6 == 6) {six = o;}
            else if(move6 == 7) {seven = o;}
            else if (move6 == 8) {eight = o;}
            else if (move6 == 9) {nine = o;}
            System.out.println("|"+one+"|"+two+"|"+trea+"|");
            System.out.println("|"+four+"|"+five+"|"+six+"|");
            System.out.println("|"+seven+"|"+eight+"|"+nine+"|");

            if (one == two && two == trea);{System.out.println("Y Win");}
            if (four == five && five == six);{System.out.println("Y Win");}
            if (seven == eight && eight == nine);{System.out.println("Y Win");}
            if (one == four && four == seven);{System.out.println("Y Win");}
            if (two == five && five == eight);{System.out.println("Y Win");}
            if (trea == six && six == nine);{System.out.println("Y Win");}
            if (one == five && five == nine);{System.out.println("Y Win");}
            if (trea == five && five == seven);{System.out.println("Y Win");}

        System.out.println("Move X");
        System.out.println("Choice number from 1-9");

        int move7 = s.nextInt();
        if (move7 == move1)  {
            System.out.println("This cell is lock");
            return;}
        else if (move7 == move2)  {
            System.out.println("This cell is lock");
            return;}
        else if (move7 == move3)  {
            System.out.println("This cell is lock");
            return;}
        else if (move7 == move4)  {
            System.out.println("This cell is lock");
            return;}
        else if (move7 == move5)  {
            System.out.println("This cell is lock");
            return;}
        else if (move7 == move6)  {
            System.out.println("This cell is lock");
            return;}
            if (move7 == 1) {one = x;}
            else if (move7 == 2) {two = x;}
            else if (move7 == 3) {trea = x;}
            else if (move7 == 4) {four = x;}
            else if (move7 == 5) {five = x;}
            else if (move7 == 6) {six = x;}
            else if(move7 == 7) {seven = x;}
            else if (move7 == 8) {eight = x;}
            else if (move7 == 9) {nine = x;}
            System.out.println("|"+one+"|"+two+"|"+trea+"|");
            System.out.println("|"+four+"|"+five+"|"+six+"|");
            System.out.println("|"+seven+"|"+eight+"|"+nine+"|");

            if (one == two && two == trea);{System.out.println("X Win");}
            if (four == five && five == six);{System.out.println("X Win");}
            if (seven == eight && eight == nine);{System.out.println("X Win");}
            if (one == four && four == seven);{System.out.println("X Win");}
            if (two == five && five == eight);{System.out.println("X Win");}
            if (trea == six && six == nine);{System.out.println("X Win");}
            if (one == five && five == nine);{System.out.println("X Win");}
            if (trea == five && five == seven);{System.out.println("X Win");}

        System.out.println("Move Y");
        System.out.println("Choice number from 1-9");

        int move8 = s.nextInt();
        if (move8 == move1)  {
            System.out.println("This cell is lock");
            return;}
        else if (move8 == move2)  {
            System.out.println("This cell is lock");
            return;}
        else if (move8 == move3)  {
            System.out.println("This cell is lock");
            return;}
        else if (move8 == move4)  {
            System.out.println("This cell is lock");
            return;}
        else if (move8 == move5)  {
            System.out.println("This cell is lock");
            return;}
        else if (move8 == move6)  {
            System.out.println("This cell is lock");
            return;}
        else if (move8 == move7)  {
            System.out.println("This cell is lock");
            return;}
            if (move8 == 1) {one = o;}
            else if (move8 == 2) {two = o;}
            else if (move8 == 3) {trea = o;}
            else if (move8 == 4) {four = o;}
            else if (move8 == 5) {five = o;}
            else if (move8 == 6) {six = o;}
            else if(move8 == 7) {seven = o;}
            else if (move8 == 8) {eight = o;}
            else if (move8 == 9) {nine = o;}
            System.out.println("|"+one+"|"+two+"|"+trea+"|");
            System.out.println("|"+four+"|"+five+"|"+six+"|");
            System.out.println("|"+seven+"|"+eight+"|"+nine+"|");

            if (one == two && two == trea);{System.out.println("Y Win");}
            if (four == five && five == six);{System.out.println("Y Win");}
            if (seven == eight && eight == nine);{System.out.println("Y Win");}
            if (one == four && four == seven);{System.out.println("Y Win");}
            if (two == five && five == eight);{System.out.println("Y Win");}
            if (trea == six && six == nine);{System.out.println("Y Win");}
            if (one == five && five == nine);{System.out.println("Y Win");}
            if (trea == five && five == seven);{System.out.println("Y Win");}

        System.out.println("Move X");
        System.out.println("Choice number from 1-9");

        int move9 = s.nextInt();
        if (move9 == move1)  {
            System.out.println("This cell is lock");
            return;}
        else if (move9 == move2)  {
            System.out.println("This cell is lock");
            return;}
        else if (move9 == move3)  {
            System.out.println("This cell is lock");
            return;}
        else if (move9 == move4)  {
            System.out.println("This cell is lock");
            return;}
        else if (move9 == move5)  {
            System.out.println("This cell is lock");
            return;}
        else if (move9 == move6)  {
            System.out.println("This cell is lock");
            return;}
        else if (move9 == move7)  {
            System.out.println("This cell is lock");
            return;}
        else if (move9 == move8)  {
            System.out.println("This cell is lock");
            return;}
            if (move9 == 1) {one = x;}
            else if (move9 == 2) {two = x;}
            else if (move9 == 3) {trea = x;}
            else if (move9 == 4) {four = x;}
            else if (move9 == 5) {five = x;}
            else if (move9 == 6) {six = x;}
            else if(move9 == 7) {seven = x;}
            else if (move9 == 8) {eight = x;}
            else if (move9 == 9) {nine = x;}
            System.out.println("|"+one+"|"+two+"|"+trea+"|");
            System.out.println("|"+four+"|"+five+"|"+six+"|");
            System.out.println("|"+seven+"|"+eight+"|"+nine+"|");

            if (one == two && two == trea);{System.out.println("X Win");}
            if (four == five && five == six);{System.out.println("X Win");}
            if (seven == eight && eight == nine);{System.out.println("X Win");}
            if (one == four && four == seven);{System.out.println("X Win");}
            if (two == five && five == eight);{System.out.println("X Win");}
            if (trea == six && six == nine);{System.out.println("X Win");}
            if (one == five && five == nine);{System.out.println("X Win");}
            if (trea == five && five == seven);{System.out.println("X Win");}





























}}

}
