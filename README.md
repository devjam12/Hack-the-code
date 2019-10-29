/* Hack-the-code*/
#include "stdafx.h"
#include "stdio.h"
using namespace System;

void main()
{
    int row = 0;
    int col = 0;
    int numberOfRows = 5;
    for (row = 0; row < numberOfRows; row++)
    {
        
        for (col = numberOfRows - 1; col>row; col--)
        {
            putchar(' ');
        
        }
        for (col = row; col >= 0; col--)
        {
            putchar('*');
        }

        putchar('\n');
    }
    return 0;
}
