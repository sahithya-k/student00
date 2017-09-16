public class Main {

	public static void main(String[] args) throws ParseException {
		SimpleDateFormat sdf=new SimpleDateFormat("yyyy-mm-dd");
		ArrayList<Student>sg=new ArrayList<student>();
		Student student = new Student(1001,"sai",sdf.parse("06-04-1995"),75.00);
		Student student1 = new Student(1002,"sandy",sdf.parse("05-08-1995"),85.00);
		Student student2 = new Student(1003,"sanju",sdf.parse("02-05-1994")65.00);
		Student student3 = new Student(1004,"sasi",sdf.parse("03-04-1996"),85.00);
		sg.add(student);
		sg.add(student1);
		sg.add(student2);
		sg.add(student3);
		StudentGroup sgb=new StudentGroup(sg.size());
		sgb.add(sg.get(0),0);
		sgb.add(sg.get(1),1);
		sgb.add(sg.get(2),2);
		System.out.println(sgb.getstudents());
		sg.remove(3);
		sgb.setstudent(student3,3);
		sgb.removeFromIndex(3);
		//You may test that your code works find here
		//Please check that your code works and has no 
		//compilation problems before to submit
	}

}
