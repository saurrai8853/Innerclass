# Innerclasspackage mypackage;

public class InnerClass {
	private class innerClass{
		private String msg="inner classes";
		void display() {
			class Inner{
				void msg() {
					System.out.println(msg);
				}
			}
			Inner I=new Inner();
		I.msg();

		}
		public static void main(String[]args) {
			innerClass ob= new innerClass();
			ob.display();
			
		}
//	private String msg="Welcome to java";
//	class inner{
//		void hello() {
//			System.out.println(msg+",Let us Start learning Inner class");
//		}
//	}
//
//	public static void main(String[] args) {
//		// TODO Auto-generated method stub
//		InnerClass obj=new InnerClass();
//		InnerClass.inner in=obj.new inner();
//		in.hello();

	}

}
