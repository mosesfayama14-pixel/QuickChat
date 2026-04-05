/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 */

package com.mycompany.chatapp2;

/**
 *
 * @author Fayama
 */
public class ChatApp2 {

    public static void main(String[] args) {
     //Declarations
        String username = "**_**";
        String password = "*****";
        
        //Checking the Username
        if (username.contains("_") && username.length()<= 5){
        System.out.println("Username succssfully captured.");        
        }else {
            System.out.println("Username is not correctly formatted;plaese enssure that yor username contains an underscore and is no more than five characters in length.");            
        }
         //Check Password
         boolean hasCapital = false;
         boolean hasNumber = false;
         boolean hasSpecial = false;
         
         
         for (int i = 0; i< password.length(); i++) {
             char ch = password.charAt(i);
             
             if (Character.isUpperCase(ch)) {
                 hasCapital = true; 
             } else if(Character.isDigit(ch)) 
                 hasNumber = true;
         }  char ch = 0;
         if (!Character.isLetterOrDigit(ch)){
         }else {
             hasSpecial = true;
        }    
    
    if(password.length()>=8 && hasCapital && hasNumber && hasSpecial) {
       System.out.println("Password successfuly captured.");    
    } else {
       System.out.println("Pssword is not correctly formatted;please ensure that the password contains at least eight characters, a capital letter, a number, and a special character.");    
}
    }
public class PhoneValidator {
    public static String validatePhoneNumber(String phone) { 
        String regex = "^\\+\\d{1,3}\\d{1,10}$" ;
        
        if (phone.matches(regex)) {
           return "Cell phone number succesfully added.";
        } else {
            return "Cell phone number incorrectly formatted or does not contain international code.";
        }   
    }
    public static void main(String[] args) {
        String phoneNumber = "+27*********";
        
        String result = validatePhoneNumber(phoneNumber);
           System.out.println(result);       
    }
}
public class Login {
   //Login with the same username and password
    String savedUsername = "**_**";
    String savedPassword = "*****";
    String firstName = "Jason";
    String lastName = "Smith";
    
    public boolean checkLogin(String username, String password) {
        return savedUsername.equals(username)&& savedPassword.equals(password);
    }
    public String getMessage(boolean isValid) {
        if (isValid==true) {
            return ("Welcome" + firstName + "," + lastName + "it is great to see you again.");
        } else {
           return ("Username or password incorrect, please try again");
        }
        
    }         
    }
}
