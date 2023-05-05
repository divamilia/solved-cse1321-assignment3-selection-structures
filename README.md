Download Link: https://assignmentchef.com/product/solved-cse1321-assignment3-selection-structures
<br>
<strong><u>Program 1:</u></strong> Design (pseudocode) and implement (source code) a program (name it PhoneBill) that calculates the bill for a cellular telephone company. The company offers two types of service: regular servicer and premium service. The rates vary depending on the type of service. The rates are computed as follows:

<u>Regular service:</u>    $15.00 fee covering first 50 minutes. Charges for over 50 minutes are computed at the rate of $0.50 per minute.

<u>Premium service:</u>  $25.00 fee plus:




<ol>

 <li>For daytime calls (between 6:00AM to 6:00PM), the first 50 minutes are free; charges for over 50 minutes are computed at the rate of $0.20 per minute.</li>

 <li>For nighttime calls (between 6:00PM to 6:00AM), the first 100 minutes are free; charges for over 100 minutes are computed at the rate of 0.10 per minute.</li>

</ol>




The program prompts the user to enter an account number, a service code (of type char), and the number of minutes the service was used. A service code <strong>r</strong> (or <strong>R</strong>) means regular service; while code <strong>p</strong> (or <strong>P</strong>) means premium service.




If the service is premium (code <strong>p</strong> or <strong>P</strong>), the customer may be using the service during both the day and night. Therefore, the program must ask the user to input the number of minutes used during daytime and nighttime in separate prompts.




Document your code and properly label the input prompts and the outputs as shown below.




<u>Sample run 1:</u>




Account Number:      12345Service type:        RegularTotal minutes:       50Amount due:          $15.00

<u>Sample run 2:</u>




Account Number:      32145Service type:        PremiumDaytime minutes:      40

Nighttime minutes:    200Amount due:           $35.00




<u>Sample run 3:</u>




Account Number:       78654Service type:         PremiumDaytime minutes:      60

Nighttime minutes:    120Amount due:           $29.00

<strong><u>Program 2:</u></strong> Design (pseudocode) and implement (source code) a program (name it BestDeal) to determine the best deal when buying a small box of apples vs. a large box of apples. The program asks the user to enter the weight and price of each box and then determines which box has a better value. The boxes may have the same value. Document your code and properly label the input prompts and the outputs as shown below.




<u>Sample run 1:</u>




Small box weight:     5 Pounds

Small box price:      10 Dollars

Large box weight:     12 Pounds

Large box price:      18 Dollars

Judgment:             The large box is a better deal




<u>Sample run 2:</u>




Small box weight:     5 Pounds

Small box price:      10 Dollars

Large box weight:     10 Pounds

Large box prices:     20 Dollars

Judgment:             Both boxes are of the same value




<u>Sample run 3:</u>




Small box weight:     5 Pounds

Small box price:      10 Dollars

Large box weight:     10 Pounds

Large box price:      28 Dollars

Judgment:             The smaller box is a better deal







<strong><u>Program 3:</u></strong> Design (pseudocode) and implement (source code) a program (name it Circles) to determine if a circle is either completely inside, overlapping with, or completely outside another circler. The program asks the user to enter the center point (X1, Y1) and the radius (R1) for the first circle C1, and the center point (X2, Y2) and the radius (R2) for the second circle C2. The program then determines if the second circle C2 is either completely inside, or overlapping with, or completely outside the first circle C1. Hint: use the sum of R1 and R2 and the distance between the centers to solve the problem. Document your code, properly label the input prompts, and organize the outputs as shown in the following sample runs.




<u>Sample run 1:</u>




Circle 1 center is:   (0,0)

Circle 1 radius is:   6

Circle 2 center is:   (1,1)

Circle 2 radius is:   1

Judgment:             Circle 2 is completely inside circle 1




<u>Sample run 2:</u>




Circle 1 center is:   (0,0)

Circle 1 radius is:   2

Circle 2 center is:   (7,7)

Circle 2 radius is:   1

Judgment:             Circle 2 is completely outside circle 1




<u>Sample run 3:</u>




Circle 1 center is:   (0,0)

Circle 1 radius is:   3

Circle 2 center is:   (2,2)

Circle 2 radius is:   3

Judgment:             Circle 2 is overlapping with circle 1







<strong><u>Program 4:</u></strong> Design (pseudocode) and implement (source code) a program (name it IncomeTax) that reads from the user annual income, as integer value, and calculates the income tax based on the tax table below.




<table width="474">

 <tbody>

  <tr>

   <td width="348"><strong>Income</strong></td>

   <td width="126"><strong>Tax bracket</strong></td>

  </tr>

  <tr>

   <td width="348">           Annual income &lt;= $50,000</td>

   <td width="126">5%</td>

  </tr>

  <tr>

   <td width="348">$50,000  &lt; Annual income &lt;= $200,000</td>

   <td width="126">10%</td>

  </tr>

  <tr>

   <td width="348">$200,000 &lt; Annual income &lt;= $400,000</td>

   <td width="126">15%</td>

  </tr>

  <tr>

   <td width="348">$400,000 &lt; Annual income &lt;= $900,000</td>

   <td width="126">25%</td>

  </tr>

  <tr>

   <td width="348">$900,000 &lt; Annual income</td>

   <td width="126">35%</td>

  </tr>

 </tbody>

</table>




The program output should include the entered annual income followed by the applied tax bracket and the tax amount. Document your code and properly label the input prompts and the outputs as shown below.




<strong><u>Note:</u></strong> Taxes are computed based on brackets. For example, if one’s income falls in the 25% bracket, the first $50,000 is taxed at 5% rate, the next $150,000 is taxed at the 10% rate, the next $200,000 is taxed at 15% rate, and the remaining income is taxed at the 25% rate. See sample run 3 below.




<u>Sample run 1:</u>




Annual Income:        $25,000

Tax Bracket:          5%

Tax due amount:       $1250




<u>Sample run 2:</u>




Annual Income:        $350,000

Tax Bracket:          15%

Tax due amount:       $40,000




<u>Sample run 3:</u>




Annual Income:        $800,000

Tax Bracket:          25%

Tax due amount:       $147500




<u>Sample run 4:</u>




Annual Income:        $1000,000

Tax Bracket:          35%

Tax due amount:       $172500










<strong><u>Program 5:</u></strong>  The concept of a 5-digit palindrome number is a 5-digit number that reads the same from left to right and from right to left. For example, 12121, 45454, and 14741 are valid 5-digit palindrome numbers. Design (pseudocode) and implement (source code) a program (name it FiveDigitPalindrom) that reads a 5-digit number from the user (as integer value, not string) and then <u>mathematically</u> (using division and remainder operations) determines whether the entered number is a 5-digit palindrome or not. Assume valid inputs are from 11111 to 9999. The program rejects any input outside that range with the message “Invalid 5-digit number. Try again”. Document your code and properly label the input prompts and the outputs as shown below.




<u>Sample run 1:</u>




Entered number: 6754

Judgment:       Invalid 5-digit number. Try again




<u>Sample run 2:</u>




Entered number: 12321

Judgment:       Valid 5-digit palindrome




<u>Sample run 3:</u>




Entered number: 12324

Judgment:       Invalid 5-digit palindrome




<strong><u> </u></strong>