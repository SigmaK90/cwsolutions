#include <stdlib.h>
#include <math.h>
int *race(int v1, int v2, int g)
{
  int* res = (int)malloc(3*sizeof(int));
  if (v1 > v2) {
    res[0] = -1;
    res[1] = -1;
    res[2] = -1;
    return res;
  }
  int time = floor(3600*g/(v2-v1));
  res[0] = floor(time/3600);
  res[1] = floor((time/60)%60);
  res[2] = time%60;
	return res;
}
