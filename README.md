# Uncomplete-Time-Project


package time;

import java.time.LocalTime;
import java.time.format.DateTimeFormatter;

public class Time {

    public static void main(String[] args) {
        LocalTime time=LocalTime.now();
        System.out.println(time);
        //its done
        DateTimeFormatter formater=DateTimeFormatter.ofPattern("hh:mm:ss");
        String t = time.format(formater);
        System.out.println(t);
    }      
    
}
