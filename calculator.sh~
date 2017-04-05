clear
result=0
i="y"

while [ $i = "y" ]
	do
		echo "1.Addition"
		echo "2.Subtraction"
		echo "3.Multiplication"
		echo "4.Division"
		echo "5.Exit"
		echo "Enter your choice"
		read ch
		if [ $ch != 5 ]
		then
			echo "Enter first No."
			read n1	
			echo "Enter second No."
			read n2
		fi
		case $ch in
			 1)result=`expr $n1 + $n2`
			  echo "result ="$result;;
				  2)result=`expr $n1 - $n2`
			  echo "Sub = "$result;;
			 3)result=`expr $n1 \* $n2`
			  echo "Mul = "$result;;
			 4)result=`expr $n1 / $n2`
			  echo "Div = "$result;;
			5)exit;;
			 *)echo "Invalid choice";;
		esac
	done    
