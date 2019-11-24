/*
# hello-world
My first repository //getting_started

These changes are made in order to understand the working of branch and master, nothing more
*/


class firstJava{
	public static void main(String[] args) {
		int [] arr={1,4,3,7,5,0,2};
		int pass=1;
    while(pass==1)
    {
        pass=0;
        for(int i=0;i<6;i++)
        {
                if(arr[i]<arr[i+1])
                {
                    int temp=arr[i];
                    arr[i]=arr[i+1];
                    arr[i+1]=temp;
                    pass=1;
                }
        }
    }
		for(int i=0;i<arr.length;i++){
			System.out.println(arr[i]);
		}
	}
}

