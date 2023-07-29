# ThirdLargestNumberwiouthsorting
public class ThirdlargestNumberWiouthsortingh {
    public static void main(String[] args) {
         int[] a={3,5,14,52,41,42,85};
         int max1=a[0];
         int max2=a[0];
         int max3=a[0];


         for(int i=1;i<a.length;i++){
             if(a[i]>max1){
                 max3=max2;
                 max2=max1;
                 max1=a[i];

             } else if (a[i]>max2) {
                 max3=max2;
                 max2=a[i];

             } else if (a[i]>max3 ) {
                 max3=a[i];

             }

         }
        System.out.println("Second largest Number ::" +
                max3);
         }
}
