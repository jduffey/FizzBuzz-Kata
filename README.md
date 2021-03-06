# FizzBuzz-Kata
:sparkles:The classic FizzBuzz coding kata.

- For each number 1 through 100:
  - Print "Fizz" if the number is divisible by 3
  - Print "Buzz" if the number is divisible by 5
  - Print "FizzBuzz" if the number is divisible by both 3 and 5
  - Otherwise just print the number
  
# Core Code

		// Creating a loop with 100 iterations.
		for (int i = 1; i <= 100; i++) {

			// Not strictly necessary for completion of the exercise but I want
			// my output to display the iteration number on each line.
			// I use 'print' instead of 'println' so as to keep the overall
			// output on the same line.
			System.out.print("(" + i + ")" + " : ");

			// First find if the number is divisible by both 3 and 5.
			// Some completions of this exercise recognize that if a number is
			// divisible by both 3 and both then it is divisible by 15, and thus
			// use "if (i % 15 == 0 )" for this conditional. For clarity I prefer
			// to code this with an AND operator.
			if (i % 5 == 0 && i % 3 == 0) {

				// If so, print "FizzBuzz". The use here (and in the other
				// conditionals) of 'println' will add a
				// line break after the output so that the overall output of the
				// loop is not on a single long line.
				System.out.println("FizzBuzz");

			} else

			// If not, check next if number is divisible by 5.
			if (i % 5 == 0) {

				// Print "Buzz" if it is.
				System.out.println("Buzz");

			} else

			// If not, check next if number is divisible by 3.
			if (i % 3 == 0) {

				// Print "Fizz" if it is.
				System.out.println("Fizz");

			} else

				// If the number is not divisible by either 3 or 5 (i.e. if none
				// of the previous conditionals are met) then display just the
				// number itself.
				System.out.println(i);

		}

# Output

(1) : 1<br />
(2) : 2<br />
(3) : Fizz<br />
(4) : 4<br />
(5) : Buzz<br />
(6) : Fizz<br />
(7) : 7<br />
(8) : 8<br />
(9) : Fizz<br />
(10) : Buzz<br />
(11) : 11<br />
(12) : Fizz<br />
(13) : 13<br />
(14) : 14<br />
(15) : FizzBuzz<br />
(16) : 16<br />
(17) : 17<br />
(18) : Fizz<br />
(19) : 19<br />
(20) : Buzz<br />
(21) : Fizz<br />
(22) : 22<br />
(23) : 23<br />
(24) : Fizz<br />
(25) : Buzz<br />
(26) : 26<br />
(27) : Fizz<br />
(28) : 28<br />
(29) : 29<br />
(30) : FizzBuzz<br />
(31) : 31<br />
(32) : 32<br />
(33) : Fizz<br />
(34) : 34<br />
(35) : Buzz<br />
(36) : Fizz<br />
(37) : 37<br />
(38) : 38<br />
(39) : Fizz<br />
(40) : Buzz<br />
(41) : 41<br />
(42) : Fizz<br />
(43) : 43<br />
(44) : 44<br />
(45) : FizzBuzz<br />
(46) : 46<br />
(47) : 47<br />
(48) : Fizz<br />
(49) : 49<br />
(50) : Buzz<br />
(51) : Fizz<br />
(52) : 52<br />
(53) : 53<br />
(54) : Fizz<br />
(55) : Buzz<br />
(56) : 56<br />
(57) : Fizz<br />
(58) : 58<br />
(59) : 59<br />
(60) : FizzBuzz<br />
(61) : 61<br />
(62) : 62<br />
(63) : Fizz<br />
(64) : 64<br />
(65) : Buzz<br />
(66) : Fizz<br />
(67) : 67<br />
(68) : 68<br />
(69) : Fizz<br />
(70) : Buzz<br />
(71) : 71<br />
(72) : Fizz<br />
(73) : 73<br />
(74) : 74<br />
(75) : FizzBuzz<br />
(76) : 76<br />
(77) : 77<br />
(78) : Fizz<br />
(79) : 79<br />
(80) : Buzz<br />
(81) : Fizz<br />
(82) : 82<br />
(83) : 83<br />
(84) : Fizz<br />
(85) : Buzz<br />
(86) : 86<br />
(87) : Fizz<br />
(88) : 88<br />
(89) : 89<br />
(90) : FizzBuzz<br />
(91) : 91<br />
(92) : 92<br />
(93) : Fizz<br />
(94) : 94<br />
(95) : Buzz<br />
(96) : Fizz<br />
(97) : 97<br />
(98) : 98<br />
(99) : Fizz<br />
(100) : Buzz<br />
