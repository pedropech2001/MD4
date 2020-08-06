**Arrays data structure**

In a nutshell an array can be defined as an ordered collection of elements indexed by contiguous integers.
Depending on the language, array types may overlap (or be identified with) other data types that describe aggregates of values, such as lists and strings. Array types are often implemented by array data structures, but sometimes by other means, such as hash tables, linked lists, or search trees.In Python, the built-in array data structure is a list.

[Reference](https://beginnersbook.com/2014/01/c-arrays-example/#:~:text=An%20array%20is%20a%20group,the%20elements%20of%20float%20types.)

*-Example of Array In C programming-*

#include <stdio.h>
int main()
{
    int avg = 0;
    int sum =0;
    int x=0;

    /* Array- declaration – length 4*/
    int num[4];

    /* We are using a for loop to traverse through the array
     * while storing the entered values in the array
     */
    for (x=0; x<4;x++)
    {
        printf("Enter number %d \n", (x+1));
        scanf("%d", &num[x]);
    }
    for (x=0; x<4;x++)
    {
        sum = sum+num[x];
    }

    avg = sum/4;
    printf("Average of entered number is: %d", avg);
    return 0;
    
    
   **Two dimensional arrays**
   
   
An array of arrays is known as 2D array. The two dimensional array, is also known as matrix. A matrix can be represented as a table of rows and columns. Before we discuss more about two Dimensional array lets have a look at the following C program.

*-Two-dimensional array example in C-*

```
#include<stdio.h>
int main(){
   /* 2D array declaration*/
   int disp[2][3];
   /*Counter variables for the loop*/
   int i, j;
   for(i=0; i<2; i++) {
      for(j=0;j<3;j++) {
         printf("Enter value for disp[%d][%d]:", i, j);
         scanf("%d", &disp[i][j]);
      }
   }
   //Displaying array elements
   printf("Two Dimensional array elements:\n");
   for(i=0; i<2; i++) {
      for(j=0;j<3;j++) {
         printf("%d ", disp[i][j]);
         if(j==2){
            printf("\n");
         }
      }
   }
   return 0;
   ```
   
   
   output
1 2 3 
4 5 6 

**Dataflow**

[Reference](https://pdfs.semanticscholar.org/6869/4d0a776b55459392a1fdead1bad5266f4b38.pdf)

Is a software architecture where variables have a defined relationship with one another. If the value of one variable changes, the values of the other variables are automatically updated. An everyday example of dataflow programming is a spreadsheet, where changing one value automatically changes many others based on a pre-defined formula.

**Files**

Is an object on a computer that stores data, information, settings, or commands used with a computer program. In a GUI (graphical user interface), such as Microsoft Windows, files display as icons that relate to the program that opens the file. For example, the picture is an icon associated with Adobe Acrobat PDF files. If this file was on your computer, double-clicking the icon opens it in Adobe Acrobat or the PDF reader installed on the computer.

A file is created using a computer software program. For example, to create a text file you would use a text editor, to create an image file you would use an image editor, and to create a document you would use a word processor.

[*-Text file-*](https://www.computerhope.com/jargon/t/textfile.htm)

A text file is a computer file that only contains text and has no special formatting such as bold text, italic text, images, etc. With Microsoft Windows computers text files are identified with the .txt file extension, as shown in the example picture.

An example of a text file and ASCII art is shown in the Kirk text file. You can click this link to open the .txt file in your browser or right-click the file to save the text file to your computer.

[*-Binary file-*](https://www.computerhope.com/jargon/b/binaryfi.htm)

Any file that contains formatted text, non-text characters, or other data not interpreted as text is considered a binary file. Some examples of binary files are program files, image files, and most other program data files.

When used as a noun, the term "binary" may refer to an executable binary file on a computer. For example, "locate the binary named program.exe, and double-click it."

