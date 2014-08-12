basicCountNumberInDigit
=======================
public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		Scanner in = new Scanner(System.in);
		ArrayList a = new ArrayList();
		
		while(in.hasNext()){
			
		long num = in.nextLong();
		
	//	int d = (int) (num %10);
		int count  = 0;
		int d ;
	    while(num %10 !=0)
	    {
	    	d= (int) (num %10);
	        num = num/10;
	        
	    	count++;
	    	
	    	System.out.println(d);
	    	
	    }
	    
	    a.add(count);
	    
		}
		
		for(int i = 0;i<a.size();i++){
			System.out.println(a.get(i));
			
		}
	}
