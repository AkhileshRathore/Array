class Array {
public static int  firstIndx(int[]arr,int idx,int x){
if (idx==arr.length){
return -1;
}
if (arr[idx]==x){
return idx;
}
else{
int first=firstIndx(arr,idx=1,x)
return;
}
}
public static void main (String args[]){
Scanner scan=new Scanner (System.in);
int a=scan.nextInt();
int []arr=new int [a];
for (int i=0;i<arr.length;i++){
arr[i]=scan.nextInt();
}
int x=scan.nextInt();
int find=firstIndx(arr,0,x)
System.out.println(find);
}
}
