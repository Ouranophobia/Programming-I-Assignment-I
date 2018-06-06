# Programming-I-Assignment-I

//********************************************************************************
// STUDENT NAME:  Antonio Suarez    
// FIU EMAIL: asuar199@fiu.edu
// CLASS: COP 2210 – 2014
// ASSIGNMENT # 1
// DATE: September 14, 2014
//
// I hereby swear and affirm that this work is solely my own, and not the work 
// or the derivative of the work of someone else.
//********************************************************************************


package programming.assignment.pkg1;

import java.util.Random;
import javax.swing.JOptionPane;

public class ProgrammingAssignment1 {

    public static void main(String[] args) {
        
        Random r = new Random();
        
        // Interger variables for Fantasy 5 winning numbers
        int fv1 = 1 + r.nextInt(36);
        int fv2 = 1 + r.nextInt(36);
        int fv3 = 1 + r.nextInt(36);
        int fv4 = 1 + r.nextInt(36);
        int fv5 = 1 + r.nextInt(36);
        
        // Int variables for Lotto winning numbers
        int lotto1 = 1 + r.nextInt(53);
        int lotto2 = 1 + r.nextInt(53);
        int lotto3 = 1 + r.nextInt(53);
        int lotto4 = 1 + r.nextInt(53);
        int lotto5 = 1 + r.nextInt(53);
        int lotto6 = 1 + r.nextInt(53);
        
        // To display output of the winning numbers in a panel on different lines
        JOptionPane.showMessageDialog
        
        // Displays the following string       
        (null, "Here are your winning numbers for Fantasy 5!\n" + 
                
                // Displays winning numbers for Fatasy 5
                "     " + fv1 + "     " + fv2 + "     " + fv3 + "     " + fv4 + "     " + fv5 + 
            
                // Displays following string
                "\n" + "Here are your winning numbers for the Lotto!\n" + 
               
                 // Displays winning numbers for the Lotto
                "     " + lotto1 + "     " + lotto2 + "     " + lotto3 + "     " + lotto4 + "     " + lotto5 + "     " + lotto6);
       
        return;
        
    }
    
}

