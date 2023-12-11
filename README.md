public class EvenNumber {
public static void main(String args[]) {
int number = 6;
if(isEven(number)) {
System.out.println(number + "is even.");
} else {
System.out.println(number + "is odd.");
 }
}
private static boolean isEven(int num) {
if (num ==0) {
return true;
}nelse if (num == 1){
return false;
}
else {
return isEven(num - 2);
}
}
}
