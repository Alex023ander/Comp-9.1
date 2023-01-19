# Comp-9.1

public static void main(String[] args) {
        MonetaryCoin coin1=new MonetaryCoin();
	        MonetaryCoin coin2=new MonetaryCoin();
	        coin1.flip();
	        coin1.addValue(3);
	        coin2.addValue(5);
	        System.out.println(coin1);
	        System.out.println(coin1.value());
	        System.out.println(coin1.value()+coin2.value());

	    }
	    
	}
