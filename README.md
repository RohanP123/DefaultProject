# DefaultProject
package stringProgram;

public class SwapTwoWords {

	public static void main(String[] args) {
		String s1="Java";
		String s2="Program";
		
	System.out.println("Before line: "+s1+" "+s2);
	
	s1=s1+s2;
	s2= s1.substring(0,s1.length()-s2.length());  //from s1(s1+s2) 0 to s1(s1+s2)length-s2 length
	s1=s1.substring(s2.length()); // from s1(s1+s2) only length of s2
	System.out.println("After line: "+s1+" "+s2); // Program Java
	
	}
}

