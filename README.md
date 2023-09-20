}
#include <cs50.h>
#include <stdio.h>
int main(void)
I/ TODO: Prompt for start size
int start;
do
start = get_int("Start: ");
while (start < 9);
I/ TODO: Prompt for end size
int end;
do
end = get int("End: ");
while (end < start);
I/ TODO: Calculate number of years until
we reach threshold
int years = 0;
while (start != end)
start = start + start / 3 + start / 4;
years++;
I/ TODO: Print number of years
printf("Years: %d\n", years);
