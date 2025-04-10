AIM: to build a two way wheeldrive which can go forward backward front and reverse
given two motors , so using the four pins of motor ,we can combine them in different permutations of high and low for the desired output 
for high ,first pin of both motors are high,for low second pin of both motors are high 
left - second pin of motor 1 and first pin of motor 2 are high
right- first pin of motor 1 and second pin of motor 2 are high
declared the inputs respectively and gave the commands.
used a keyboard input string funnctions for the operator to perform,w-front,s-back,s-left,d-right
i chose pins 8,10 for motor 1 and pins 12,5 for motor 2 terminals
gave analog output for the speed of motor,250 for front and back ; 190 for left and right;
gave all the connections accordingly to the aurduino 

coming to my code,the part where the string input has to be taken,that was the problem
i compared string to char which i realised at the end and made a change by adding a new function equals() when comparing the keyboarrd input that is char and string
