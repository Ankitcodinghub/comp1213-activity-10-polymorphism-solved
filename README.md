# comp1213-activity-10-polymorphism-solved
**TO GET THIS SOLUTION VISIT:** [COMP1213 Activity 10-Polymorphism  Solved](https://www.ankitcodinghub.com/product/comp1213-activity-10-polymorphism-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95528&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP1213 Activity 10-Polymorphism&nbsp; Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Activity: Polymorphism

</div>
</div>
<div class="layoutArea">
<div class="column">
Goals:

By the end of this project you should:

Ø Have an understanding of polymorphism via inheritance

Ø Be able to create methods that use polymorphism to deal with multiple types of objects

Directions:

Don’t forget to add your Javadoc comments for your classes, constructor, and methods in this activity.

For this assignment, you will need your classes from Activity on “Inheritance” except for the driver program. If you haven’t created these classes, you’ll need to do them as part of this activity.

ItemsList

<ul>
<li>Create a class called ItemsList. This class will hold an array of InventoryItem objects (which includes objects of subclasses of InventoryItem; recall an instance of a subclass of InventoryItem is an InventoryItem).</li>
<li>Declare an instance variable in your class of type InventoryItem array which is called inventory and an int called count to track the number items in inventory.
<pre>        private _________[] inventory;
        private _____ count;
</pre>
</li>
<li>Create a constructor for ItemsList that has no parameters. Add the following code to instantiate the InventoryItem array.
<pre>        _____ = new InventoryItem[20];
        count = ____;
</pre>
</li>
<li>Create the following method stubs for your class:

o addItem: with parameter InventoryItem itemIn; no return.</li>
</ul>
o calculateTotal: with parameter double electronicsSurcharge; double return.

<ul>
<li>The addItem method takes an InventoryItem as a parameter, assigns it to the element at positon count in the inventory array, and then increments count. No need to worry about exceeding the capacity of the array in this activity.</li>
<li>Create a toString method in ItemsList. The toString method should iterate through inventory from 0 up to count (but not including count) to append the toString for each item to output:</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Page 1 of 5

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Activity: Polymorphism Page 2 of 5

</div>
</div>
<div class="layoutArea">
<div class="column">
Recall, the Object class has a toString method, which is inherited by its subclasses. When you define a toString method in your class, you are overriding an inherited toString method.

InventoryListApp – driver class and main method

<ul>
<li>Create a class called InventoryListApp and add a main method. In the main method, instantiate a ItemsList object called myItems.</li>
<li>In the main method, set the tax rate to 0.05 by invoking the InventoryItem.setTaxRate method.</li>
<li>Instantiate the following 4 items in the main method and add them to myItems:</li>
</ul>
o ElectronicsItem:name=“laptop”,price=$1234.56,weight=10lbs

myItems._____(new ElectronicsItem(_____, 1234.56, 10));

o InventoryItem:price=$9.8,name=“motoroil”

o OnlineBook:price=$12.3,name=”AllThingsJava”

o OnlineArticle:price=$3.4,name=“UsefulAcronyms”

• Print the toString return value of the ItemsList object myItems to standard output:

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
ÏÏ«Ï —-jGRASP exec: java -ea InventoryListApp ÏÏ§ÏAll inventory:

ÏÏ§Ï

ÏÏ§Ïlaptop: $1311.288

ÏÏ§Ïmotor oil: $10.290000000000001

ÏÏ§ÏAll Things Java – Author Not Listed: $12.3 ÏÏ§ÏUseful Acronyms: $3.4

ÏÏ§Ï

ÏÏ©Ï —-jGRASP: operation complete.

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
ItemsList: calculateTotal

• The calculateTotal method in ItemsList accepts surcharge for electronics items as a parameter and returns the total price of all of the items. You’ll have to iterate through each of the items in inventory and add the cost for each item to a running sum (price below). If the item is an ElectronicItem, invoke calculateCost method and add the electronics surcharge that was passed as a parameter to calculateTotal.

o Usetheinstanceofoperatortodeterminewhetheranobjectisaninstanceof Page 2 of 5

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Activity: Polymorphism Page 3 of 5

</div>
</div>
<div class="layoutArea">
<div class="column">
particular class (place this if-else inside the for loop). If the object is of type ElectronicsItem, the following code shows how the instanceof operator is used to add the small surcharge to an ElectronicsItem:

Add an else clause to calculate the cost without adding the surcharge:

• Be sure to return total after the loop.

Main Method

<ul>
<li>In the main method, add code to print the total of all items and include an electronics surcharge of 2.0:</li>
<li>Your output should appear as follows.</li>
</ul>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
ÏÏ«Ï —-jGRASP exec: java -ea InventoryListApp ÏÏ§Ï

ÏÏ§ÏAll inventory:

ÏÏ§Ï

ÏÏ§Ïlaptop: $1311.288

ÏÏ§Ïmotor oil: $10.290000000000001

ÏÏ§ÏAll Things Java – Author Not Listed: $12.3 ÏÏ§ÏUseful Acronyms: $3.4

ÏÏ§Ï

ÏÏ§ÏTotal: 1339.278

ÏÏ§Ï

ÏÏ©Ï —-jGRASP: operation complete.

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Page 3 of 5

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Activity: Polymorphism Page 4 of 5

</div>
</div>
<div class="layoutArea">
<div class="column">
UML Class Diagram

<ul>
<li>If you have not already done so, create a jGRASP project called InventoryListApp and add all of your classed for this activity.</li>
<li>Generate theUML class diagram and arrange the class as shown below.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Page 4 of 5

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Activity: Polymorphism Page 5 of 5

</div>
</div>
<div class="layoutArea">
<div class="column">
Viewer Canvas

<ul>
<li>Create a canvas for your program as follows:
<ol>
<li>(1) &nbsp;Run your program in the canvas . After the canvas opens, single step your program
until you see myItems in the Debug tab.
</li>
<li>(2) &nbsp;Drag myItems onto the canvas. Then select the inventory field in myItems and drag it
out onto the canvas.
</li>
<li>(3) &nbsp;Drag myItems onto the canvas again and change the viewer to the “toString” viewer. To
do this, select the viewer window, click the menu button on the top-right of the viewer

frame, then select “Viewer” then “toString”.
</li>
<li>(4) &nbsp;Save the canvas then end the program. Run your program in the canvas . Now single
step your program and watch the objects appear on the canvas.
</li>
<li>(5) &nbsp;Run your program in the canvas . Click the play button and watch the canvas and
stepping in the program as the objects appear on the canvas. Notice that the debugger is stepping into each of your constructors and method as they are called. You should be sure that your understand “how” your program is running to accomplish its task. Note that you can pause the canvas and then hit play to continue auto stepping-in. You

can also set one or more breakpoints and then resume to breakpoint.
</li>
</ol>
</li>
<li>You should become comfortable using the canvas and debugger so that when needed, you will be able to use them to help find and correct errors in your projects.</li>
<li>Finally, submit your files to the grading system.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Page 5 of 5

</div>
</div>
</div>
