# Arrays-min-max-method-


//To find min and max numbers in an array and accessing from the method

class Array {

    void method(){

        int a[]=new int[10];

        a=new int[]{1,2,3,44,443};

        int max = a[0]; int min=a[0];

        for(int i=0;i<a.length;i++){

            if(a[i]>max){

                max=a[i];

            }

            else if(a[i]<max){

                min=a[i];

            }

        }

        System.out.println(" The maximum number in the array is : "+ max);

        System.out.println(" The minimum number in the array is : "+min);

    }

    public static void main(String... test) {

        Array arr=new Array();

        arr.method();

    }

}

/*

 The maximum number in the array is : 443

 The minimum number in the array is : 1

 */
