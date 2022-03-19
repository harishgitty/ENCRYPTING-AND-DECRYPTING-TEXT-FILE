# ENCRYPTING-AND-DECRYPTING-TEXT-FILE
ENCRYPTING AND DECRYPTING TEXT FILE USING HYBRID CRYPTOSYSTEM
# READING THE FILE USING
try {
 File myObj = new File("demo.txt");
 Scanner myReader = new Scanner(myObj);
 while (myReader.hasNextLine()) {
 BigInteger data = myReader.nextBigInteger();
 System.out.println(data);
}
}

# Calculating the time using
long start=System.currentTimeMillis();
long enc_time =System.currentTimeMillis();
long dec_time =System.currentTimeMillis();

# Printing the time

System.out.println("Time taken to Encrypt the text file : " + (enc_time - start) + " ms ");
System.out.println("Time taken to Decrypt the text file : " + (dec_time -
enc_time) + " ms ")

#Architecture

![image](https://user-images.githubusercontent.com/101494813/159124701-5138a5f1-bdb5-47c6-9ed1-500680d79bea.png)




