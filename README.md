# byteDemo
byte
pull by sourceTree

public class ByteTest {
    public static void main(String[] args) {
        byte[] a = new byte[10];
        a[0]= -127;
        System.out.println(a[0]);
        int c = a[0]&0xff;
        System.out.println(c);
    }

}
