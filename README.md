# DECODER2TO4
# Truth Table and Circuit Diagram
![image](https://github.com/RESMIRNAIR/DECODER2TO4/assets/154305926/e565d523-f8b2-4e01-8888-0eed4d07ec24)
# aim

# program
~~~
module decoder_8(a,b,c,y);
input a,b,c;
output [7:0]y;
and gl (y[0], (~a), (~b), (~c));
and g2 (y[1], (~a), (~b), (c));
and g3 (y[2], (~a), (b), (~c));
and g4 (y[3], (~a), (b), (c));
and g5(y[4], (a), (~b), (~c));
and g6(y[5], (a), (~b), (c));
and g7(y[6], (a), (b), (~c));
and g8 (y[7], (a), (b), (c));
endmodule
~~~
# output
![WhatsApp Image 2024-03-18 at 13 54 10_92a9c8a7](https://github.com/jenesh12/DECODER2TO4/assets/163829923/b4522532-315f-42cc-87f9-2d39ea274b07)
# result
hence the decoder is verified sucessfully.
